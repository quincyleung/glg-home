# GLG Home — 25 prototypes (MPCS 51238, Assignment 1)

## The idea
The home screen a Girls Lift Girls member sees when she opens the app. GLG is a women's fitness community ("Strength in Community") with city chapters in Hong Kong, Dubai, Sydney, Brisbane, Gold Coast, Heidelberg and Shanghai.

- **Who it's for:** a GLG member, usually on her phone, checking what's on.
- **What she should understand or do in a few seconds:** what's coming up in her city, how to book a spot, and the latest update from her chapter.

## The assignment
- 25 distinct versions (v01–v25), plus a gallery at `index.html` that tells the story of the process and presents the final pick.
- Early versions go wide: layout, mood, era, tone, metaphor. Changing only colors or fonts is not a new direction.
- Later versions narrow down: combine what works from earlier versions and converge, so v25 is the final choice.
- Graded on breadth, choosing well, and telling the story, not polish. At least 20 versions must look unlike anyone else's in a class of 28, so avoid generic SaaS or fitness-template looks.

## Constraints
- Plain HTML and CSS, optional vanilla JS. No frameworks, packages, build step, external APIs, or data storage. If you think one is needed, ask me first.
- Mobile-first, and still readable on desktop.
- All content is hardcoded and fictional: invented member names and events. No real member photos, emails or phone numbers.

## Structure
- `index.html`: the gallery. A grid of all versions; each thumbnail links to its page and has a one-line note on what changed. Final pick highlighted.
- `v01/index.html` … `v25/index.html`: each version is self-contained and has a "← Gallery" link back.
- Never edit an earlier version when making a new one.

## Workflow
- One version at a time. After each one, add it to the gallery and commit with a message like `v07: editorial magazine spread`.
- After each version, append a few lines to `process-log.md`: what I asked for, what you made, and anything I pushed back on.
