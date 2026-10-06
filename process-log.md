# Process log

How the GLG home screen went from 25 open ideas to one final pick. Each section summarises a phase: what I asked for, what was made, and the pushback that steered the next step. (The full step-by-step history is in the git log.)

## Setup
- Wrote `content.md`: one fictional member (Jasmine, Hong Kong chapter), five events, two chapter announcements and a global update. Every version uses this so differences come from design, not copy.
- Built a gallery shell at `index.html`.

## v01–v05 · Going wide (event-first themes)
- **Departures** (transit board), **Order Sheet** (dim sum tick-sheet), **Tape Shelf** (80s mixtape), **Zine Feed** (punk zine), **Morning Briefing** (a letter from the chapter lead).
- **Pushback:** ideas had to work as a real, practical app home screen, not posters. Tab bar renamed to Home · Events · Community · Profile.

## v06–v10 · Real home pages
- **Energy Check-in, Doing Things, Stories, City Map, Never Alone.** Each is built around a different feature (energy picker, verbs, story rings, a map, buddy matching).
- **Pushback:** the early screens read like an events list, so every home page now adds something personal (streak, stats), her booked sessions, and community updates.

## v11–v15 · Mood and tone
- v06–v10 felt alike, so v06, v08 and v10 were restyled (calm, hype, warm) and five themes were added: **Strong, Girly, Together, Cool, Chic**.
- **Pushback:** v13 was redone as a sporty, photo-led "together" page, then simplified away from looking like Strava. v07 was made fully pastel.

## v16–v20 · Learning from the real brand
- Studied girls-lift-girls.com: purple and white, Oswald and Arimo fonts, group photos of women, an inclusive "stronger together" voice and four values.
- **Strength in Community** (brand-faithful), **Week Ahead** (timeline), **Cover Story** (editorial), **Quiet** (minimal, avatars) and **Orbit** (avatar-led, tap a seat to join).
- Photos are illustrated in code, because real member photos and external images were out of scope.

## v21–v24 · Converging
- The favourites were v16 and v21. Decisions that carried forward:
  - a one-line "Morning, Jasmine." with a profile icon
  - a streak card that flips to a check-in QR (sessions + total time)
  - "You're going" and "Join a session" (not "claimed" or "coming up")
  - a "psst, your friends are going" nudge
  - compact event cards (one info line, the instructor's photo for details, who's going + price + Join)
  - a three-item community preview you can heart, comment on and join challenges from
  - an icon tab bar
- **v21** Lavender Drop and **v22** Stronger Together (v21's features in v16's style). **v23** and **v24** apply the same decisions to v13's sporty style and v20's orbit.
- **Pushback along the way:** less clutter (no moving banner, no filters on the home, at most three faces), clearer sections, swipeable rows, a tab bar that never disappears, and v24's orbit made useful ("who can I train with, and how do I join her?").
- v22 was later rolled back to an earlier state so the step from v22 to v25 is visible.

## v25 · Final pick
- v22 polished with the best of the others:
  - live countdowns in days and hours
  - tap any friend's face to see her next session and join her
  - route maps in the hike and run details
  - the real Oswald and Arimo fonts
  - an empty-state preview (`?empty`)
  - a quote from a famous female athlete at the bottom
- **Pushback that finished it:**
  - no shimmer, a calm flat light-purple background with a soft card shadow
  - one psst card, in a deeper lavender so it stands out
  - no section dividers, non-sticky headers
  - real, sourced quotes instead of invented ones

## Notes
- **External resources:** only Google Fonts (Oswald + Arimo) in v25, approved during the process. Everything else is plain HTML, CSS and vanilla JS.
- **Content:** all members, events and posts are fictional. The athlete quotes in v25 are real, sourced public quotes, added on request.
