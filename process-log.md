# Process log

## Setup
- **Asked for:** shared fictional content for all versions, plus a gallery shell with a short project intro. No versions yet.
- **Made:** `content.md` (Sofie Tran, Hong Kong chapter; 5 events covering strength, hiking, running, boxing and paddleboarding, two of them free and Barbell Basics nearly full with 2 spots left; 2 chapter announcements; 1 global update about Global Lift Day) and `index.html` (intro, empty versions grid, placeholder for the final pick).
- **Pushback:** none yet.

## Directions (before v01)
- **Asked for:** 12 radically different directions, then sketches of them in the gallery.
- **Made:** round 1, 12 themed sketches (Departures, Chalkboard, Group Chat, Dim Sum sheet, VHS, Zine, Swiss, Neon, Plates, Quest, Logbook, Letter).
- **Pushback:** they had to work as a practical web app, not posters. I reworked them with a shared tab bar and Book buttons. Then: "i want it to still look like a homepage of an app with beautiful smooth UI/UX." I kept Tape Shelf and Zine Feed and added 7 women-focused movement ideas drawn from other clubs (Black Girls RUN!, Outdoor Voices, Hike Clerb, Girls on the Run…). Tabs renamed to Home, Events, Community, Profile.
- **Pushback:** the round 2 sketches looked like an events page. The home page also needs something personal, the user's booked events and a mix of community updates. Picked Energy Check-in, Doing Things, Stories, City Map and Never Alone to build. Added personal stats, a second booking (5K) and community snippets to `content.md`.

## Energy Check-in (built as v01, renumbered to v06)
- **Asked for:** develop the Energy Check-in direction into a full home page.
- **Made:** a lilac, soft-card home that opens with "How's your energy today?" (Low / Steady / High). Picking one changes the suggested events below. Also has a streak / sessions / PB strip, an optional cycle-aware toggle, "Your upcoming" (hike and 5K) and a community digest (announcement, member win with a Hype button, chat thread, Lift a Million progress, global update). Booking turns the button into "Going ✓" with a toast.
- **Pushback:** none yet.

## Restructure
- **Pushback:** no sketch sections in the gallery. Just 25 real pages, with the versions themselves telling the story. The first five should be Departures, Order Sheet, Tape Shelf, Zine Feed and Morning Briefing.
- **Made:** Energy Check-in moved from v01 to v06. Doing Things (in progress as v02) became v07. The gallery now lists built versions only, with live previews. Also fixed the tab bar so it sticks inside the phone frame on desktop.

## v07: Doing Things
- **Asked for:** develop the Doing Things direction into a full home page.
- **Made:** a cream page with pastel colour blocks where verbs lead everything. Verb-led personal stats on a dark card ("27× moved with GLG"), "You're doing" (Hike. / Run.), "Up for grabs" tiles (Lift. with a "2 left!" sticker, Punch., Paddle.), and a swipeable community rail (Heard. / Lifted. / Asked. / Lifting. / Together.). Floating dark tab bar.
- **Pushback:** none yet.

## v01: Departures
- **Asked for:** Departures as the first version (from the round 1 sketches).
- **Made:** a black and amber transit board. Each event is a "departure" with time, venue as the platform, and a status (blinking "2 LEFT", "BOOKED", "ON TIME"). Tap a row to expand the details and "BOOK SEAT". Chapter news and the global update scroll as a ticker.
- **Pushback:** none yet.

## v02: Order Sheet
- **Asked for:** Order Sheet as the second version.
- **Made:** a cream and red 點心紙 (dim sum order sheet). Events are grouped as Strength / Outdoors, with tick boxes and prices. Booked events carry a red 已訂 BOOKED stamp. A sticky button keeps a running total ("Book 2 events · HK$430") and stamps everything at once. News sits in a "Today's notes" box.
- **Pushback:** none yet.

## v03: Tape Shelf
- **Asked for:** Tape Shelf as the third version, a direction you liked from round 1.
- **Made:** the polished round 2 take. A purple night gradient with a "GLG GET PHYSICAL!" header. The next bookable event is a cassette (handwritten label, "Only 2 spots left") whose reels start spinning when you book. Other events are tapes on a swipeable shelf. News is "Liner notes" as numbered tracks.
- **Pushback:** none yet.

## Fix: direct links
- **Asked for:** clicking a gallery tile should open the page, not a folder listing.
- **Made:** gallery links, preview iframes and every version's "← Gallery" link now point at `index.html` files directly, so they work when opened locally.

## v04: Zine Feed
- **Asked for:** Zine Feed as the fourth version, the other round 1 direction you liked.
- **Made:** a dotted-paper, neo-brutalist zine. "GIRLS LIFT" as a ransom-note headline and "Issue #41 · hey Jasmine". Barbell Basics is the cover story, with a "2 LEFT!" sticker and highlighter. The other events are chunky cards with offset shadows and "YOU'RE IN" stickers. News is taped-on "Cut-outs", with a striped Lift a Million meter.
- **Pushback:** none yet.

## v05: Morning Briefing
- **Asked for:** Morning Briefing as the fifth version.
- **Made:** an editorial "Morning Brief" masthead and a short letter from Hana with a drop cap. "save me a spot" in the text books Barbell Basics inline. Then a calm "At a glance" list of all five events and "Also in the brief" news. Still event-first, but the first version with a personal voice, which leads into v06+ adding personal stats and community.
- **Pushback:** none yet.

## v08: Stories
- **Asked for:** develop the Stories direction (Nike Training Club / Instagram).
- **Made:** a white page with story rings at the top for Hana, Chloe, Priya, the challenge and GLG HQ. Tapping one opens a full-screen story viewer with progress bars, tap-to-advance and an action ("Hype her", "I'm in 🚕", "Remind me"). Below that: a streak ring and stats, a swipeable deck of gradient event cards with dots, "Your tickets" as perforated stubs, and two community tiles.
- **Pushback:** none yet.

## v09: City Map
- **Asked for:** develop the City Map direction (Hike Clerb / Brown Girl Surf: the city as your playground).
- **Made:** an SVG map of Hong Kong (harbour, Kowloon, the island, Sai Kung) with event pins: green for booked, pink for open, and a pulsing pin for "2 left". Plus a "You" dot and All / Booked / Open filters. A bottom sheet holds a district-explorer stat (6 of 18 districts, 3-week streak), "Your plans" cards, "Open near you" with distances (tapping a pin highlights its card), and "Around the city" community notes tagged by place.
- **Pushback:** none yet.

## v10: Never Alone
- **Asked for:** develop the Never Alone direction (Girls on the Run / Sweaty Betty: first-timer nerves, never go alone).
- **Made:** a warm peach and espresso page headed "Never lift alone." It has a dark "Your crew" card (Priya 8×, Chloe 5×, 14 women met, streak) and a buddy-match hero ("Chloe is going to Barbell Basics solo too": Pair up / Just book). "Your plans" shows who else is going, with actions (join Priya's taxi, run with Aisha). "Try something new" uses first-timer and bring-a-friend badges, and "Cheer them on" mixes wins with Cheer buttons, chapter news, Lift a Million and the global update.
- **Pushback:** none yet.

## Round of tone changes (v06, v08, v10 restyled; v11–v15 added)
- **Pushback:** "I like the different layouts and features. I want to vary it more based on font, mood, and tone. I feel like V6 to V10 are a bit similar." Asked to change some and add 5 more themes (strong, girly, community-focused, cool, chic…).
- **Decision:** kept v07 (playful pastel) and v09 (clean map) as they are. Restyled v06, v08 and v10 in place, keeping each one's layout and features. Used built-in font stacks only (no Google Fonts, per the AGENTS.md rule on external resources).

## v06 restyled: calm
- **Made:** Optima headings with Avenir body text, sage, sand and clay, and hairline borders instead of shadows. The energy picker became three breathing circles (Resting / Steady / Energised), and the copy is gentler ("How does your body feel today?", "Rest is part of training", "From the circle", "Send love").

## v08 restyled: hype
- **Made:** a dark, loud sports-brand mood: black with volt yellow and an orange-to-violet gradient, condensed Impact caps for headings, square-cornered buttons and hype copy ("Let's go, Jasmine.", "Locked in", "The squad", "3 weeks straight. Don't break it."). The story viewer and swipe deck still work.

## v10 restyled: warm and sisterly
- **Made:** cream lined paper with terracotta, italic Hoefler/Baskerville headings and Bradley Hand notes ("Morning, Jasmine ♡", "psst, a buddy match →"). The crew card is dashed and slightly tilted, and the buddy match is a taped-on note. The copy is softer ("You never have to lift alone.", "Cheer your girls on").

## v11: Strong
- **Asked for:** a "strong" theme.
- **Made:** a speckled concrete background with black and red, Arial Black caps, monospace details, no rounded corners and 3px rules. The tone is a coach's ("Jasmine. Saturday. 2 spots.", "Book it or miss it."). Has a PR board (squat 60 kg → next target 65, sessions, streak, your share of the million), "Your program" as a numbered training log, "Load the week" with intensity bars and square red BOOK buttons, Lift a Million drawn as a barbell loaded with plates, and "The floor" community feed with RESPECT buttons.

## v12: Girly
- **Asked for:** a "girly" theme.
- **Made:** a pink gingham background with Snell Roundhand script headings, rounded UI type, a 🎀 and "Hi Jasmine!". The streak is a beating heart with sticker badges on a washi-taped card. Booked events are dashed "You're going ♡" invitation cards. Bookable events are tilted polaroids with "Save my spot" buttons, and the community is "Girl talk" chat bubbles with ✨ reactions and a candy-striped Lift a Million meter.

## v13: Community
- **Asked for:** a community-focused theme.
- **Made:** teal and mustard with Gill Sans, in a "we" voice. The hero is "48 of us moved together" as a mosaic of dots with Jasmine in gold. Then: "New faces" (three new members, Wave button), a cork noticeboard with pinned notes, "Who's going" (every event shown by its people: "You, Priya + 21 others", "Join them"), "Talking about" threads with Cheer buttons, "You in the community" stats, and the global update with chapter chips. Added the new members and chapter size to `content.md`.

## v14: Cool
- **Asked for:** a "cool" theme.
- **Made:** cool grey with ink and one electric blue, Helvetica with tight tracking plus monospace, all lowercase ("morning jasmine. here's what's dropping."). There's a holographic animated member card (member #0412, sessions, streak, PB). Booked events are "claimed", and the bookable ones are numbered "drops" with live ticking countdowns (from a fixed prototype "now" of 07:42 Tue 6 Oct), fill meters and "claim spot". The community is a terse lowercase feed with ↑ reactions.

## v15: Chic
- **Asked for:** a "chic" theme.
- **Made:** quiet luxury in ivory and ink with Didot/Bodoni italics, Avenir spaced caps and hairline rules. The tone is refined ("Your week, considered.", "Two places remain"). Has an "In numbers" strip, "Your itinerary" with dotted leaders, "To reserve" with roman numerals and underlined text links, "Notes from the chapter" as italic quotes with an Applaud action, and Global Lift Day as a double-ruled save-the-date card.
- Also updated the gallery's intro to the versions to tell the v06–v15 part of the story.

## v13 redone: Together
- **Pushback:** "v13 is too similar to v10. Can you redo v13 so it's giving sporty, photo based (like Strava), and together."
- **Made:** a Strava-style white-and-orange activity app. "Your week" has planned sessions, km and time with a day-by-day bar chart and streak. "You're going" shows route-map thumbnails. "Join a group session" cards have photo headers and "14 of 16" with avatars. The feed has group activities ("Harbourfront 5K: 31 of us": distance, pace, together count, a dusk harbour photo, route map, kudos and comments) and Chloe's PR as a strength activity. Plus a Lift a Million club challenge with leaderboard (you're #38) and club news. The photos are illustrated SVG scenes, because AGENTS.md rules out real photos and external images. Added the activity stats and leaderboard to `content.md`.

## v07 recoloured: full pastel
- **Pushback:** "make v7 more colorful… fully embody the pastel colorful theme (feel like the black doesn't quite fit)."
- **Made:** replaced every black surface. Text is now a deep grape, the headline is a pink→lilac→blue gradient, and the stats card is a peach→pink→lilac gradient. Book buttons are white pills tinted to match their tile, the tab bar is white with a pastel active pill, and the page has a soft rainbow wash.

## v13 tweaked: less Strava, purple
- **Pushback:** remove the feed posts (Hana, Chloe) and the planned km, since GLG isn't only running. It looked too similar to Strava. Change the colourway to purple.
- **Made:** removed both activity posts and their styles and scripts. Replaced "planned km" with a sport-agnostic "Activities: Hike · Run" and "Hours: 3h 45m". Swapped orange for purple (#6c3ce0) throughout, including routes, badges, the chart, buttons and the leaderboard. Kept the week chart, route thumbnails, photo cards for group sessions, the challenge leaderboard and club news.

## Converging: v16–v18 (brand-led improved versions)
- **Asked for:** think about which direction best matches the real Girls Lift Girls brand (girls-lift-girls.com). You like v14, v13, v8 and v7 and "Morning, Jasmine." The home should show what she's signed up for, events she could sign up for, streaks, and community announcements/feed, and be photo-heavy like the website. Make 3 improved versions.
- **Brand research (from the site):** headings in Oswald (condensed caps), body in Arimo. Purple and white logo ("purple on purple", "white with purple"); I couldn't extract an exact hex. The voice is inclusive and community-first: "women of all fitness levels", "built for every body", "lifts each other up". Values: Finding Strength In · Redefining Norms · Accepting Challenges · Being Stronger Together. Events pair workouts with talks, coffee and pastries, often as brand collabs ("X Girls Lift Girls"). Each chapter has a WhatsApp chat, and the site is full of group photos of women at events.
- **Photos:** AGENTS.md rules out real member photos and external images, so I wrote a small SVG generator that draws illustrated group "photos" (gym, harbour, trail, beach, studio scenes with diverse women, celebrating poses, optional purple duotone and grain). It's inlined in each page.
- **Fonts:** the CSS asks for Oswald and Arimo first, with built-in fallbacks (Avenir Next Condensed / Arial). They'll render exactly once Google Fonts is approved.

## v16: Strength in Community
- **Made:** the most brand-faithful version (from v13 + v8). A full-bleed duotone group photo hero with "MORNING, JASMINE." in condensed caps, then an overlapping "3 weeks strong" streak card with this week's planned days and stats. "You're signed up" is photo tickets with who's going. "Sign up next" has big photo cards ("Only 2 spots left", "3 first-timers going") with Join buttons. "From the community" has a pinned chapter update, Chloe's PR with a photo and "💜 Lift her up", Lift a Million, a chapter chat preview and Global Lift Day with city chips. A scrolling band of the GLG values sits at the end.

## v17: Lavender Drop
- **Made:** a cross of v14 (cool drops, lowercase, mono details, live countdowns) and v7 (pastels, no black), kept in the purple family. "morning, jasmine." with a pink→purple gradient, then a holographic pastel member card that holds the streak ring, this week's day tiles and stats. "Claimed" sessions have square photo thumbnails, countdowns and "you + 22". "This week's drops" are photo cards in pastel duotones with fill meters and "claim spot". "The feed" is a 3-column photo mosaic (run club "31 of us" big tile, Chloe's PR, new faces, sunrises) with ♡ reactions, plus pastel announcement notes (pinned run club update, Lift a Million, chapter chat, Global Lift Day).
- **Fix:** the photo generator was replacing badges and date chips placed inside photos. It now inserts the drawing underneath. v16 is patched too.

## v18: Night Session
- **Made:** a cross of v8 (loud hype, story viewer) and v13 (photos, together) in a dark GLG-purple night mode. Story rings are circular photos and open a full-screen photo story with progress bars and actions ("👋 Wave", "💜 Lift her up", "Remind me"). Then "MORNING, JASMINE." in big condensed caps, a pink streak ring ("3-week streak. Make it 4."), "Locked in" as full-bleed photo cards with who's going, "Up next" as a swipeable deck of tall photo cards with Join buttons, and "The squad": a pinned update, two photo moments, Lift a Million, chapter chat and Global Lift Day.
- **Pushback:** "please make sure you are committing and pushing changes to github as you go." v16 and v17 had been committed but not pushed. Pushed straight away, and from now on every commit is pushed in the same step.
- Updated the gallery story text to cover v16–v18.

## Renumbering: converge from v20
- **Asked for:** start converging at v20 to leave room for more variety. Insert a few new on-brand versions between v16 and v17.
- **Decision (you picked):** 2 new versions as v17 and v18. Lavender Drop moves from v17 to v19, and Night Session from v18 to v20. Night Session already merges v8 and v13, so it becomes the first convergence step, and convergence runs v20–v25.

## v17: Week Ahead
- **Asked for:** more on-brand variety before converging. Keep GLG's branding but change things around.
- **Made:** the v16 brand (white and GLG purple, Oswald-style caps, Arimo, illustrated group photos) reorganised around time. "MORNING, JASMINE." with no hero photo, then a 12-week streak heatmap ("3 weeks strong") with stats, then a sticky date scroller (dots: booked / open / news). One vertical timeline: today's community moments (Chloe's PR with Lift her up, new members), Barbell Basics to join, her booked hike (solid purple) with Priya's taxi under it, the run club start-line announcement pinned right above her booked 5K, boxing and paddle to join, the Lift a Million deadline on 31 Oct, and Global Lift Day on 7 Nov. Then "Looking back" photo postcards and the GLG values.

## v18: Cover Story
- **Made:** the brand as an editorial poster, like the GLG website's bold type over photos. A purple announcement ticker, then a three-photo collage cover with "MORNING, JASMINE." on stacked purple and white labels ("HK chapter · Week 41"). Her streak is a giant purple "3" with "Weeks strong. Make it four." and a stats list. "You're in" is two tall photos with rotated "You're in" stamps. "This month at GLG" is three numbered zig-zag features, each kicked off by a GLG value (Accepting challenges → Barbell, Redefining norms → Boxing, Finding strength in → Paddle). "Being stronger together" is a dark section with Chloe's pull quote and portrait, chapter notes, and Lift a Million as a huge number. It ends with a Global Lift Day save-the-date band.
- Added a portrait mode to the photo generator (one large figure) for avatar crops.

## Renumbering again: two more innovative versions first
- **Asked for:** two more innovative versions before converging (e.g. more minimalistic, avatars instead of photos), inserted before Lavender Drop and Night Session, which become the convergence steps.
- **Made:** Lavender Drop moved v19 → v21 and Night Session v20 → v22. New versions take v19 and v20. Convergence now runs v21–v25.

## v19: Quiet
- **Asked for:** an innovative, more minimalistic version with avatars instead of photos.
- **Made:** almost no UI chrome: white, one GLG purple, Arimo at regular weight with tiny spaced Oswald labels, and lots of air. "Morning, Jasmine." with a one-line status and the streak as twelve dots (one per week, the last three purple). "Next · in 5 days" makes the hike the single focus, with the avatars of who's going. Plain hairline lists for Booked and Open. Each open session shows its seats as dots (outlined = free), and Join fills one in purple. The community has two items plus a "Show 3 more" fold. The GLG values sit in pale grey at the end.
- New: an illustrated avatar generator with fixed fictional looks per named member, so Chloe, Priya and the others stay recognisable everywhere.
