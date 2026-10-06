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
