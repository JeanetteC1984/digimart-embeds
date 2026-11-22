# Digimart embeds

Mini apps by Digimart, made to embed in Notion with `/embed`.

## Glitchfolio creator portfolio
- Sample mini app: https://jeanettec1984.github.io/digimart-embeds/glitchfolio/
- Link builder (make your own): https://jeanettec1984.github.io/digimart-embeds/glitchfolio/builder.html

Pick one of 3 templates (Glitch, Showcase, Profile), 5 color themes and 4 font pairs in the builder. The builder puts your details into the link itself (`?d=...`), so nothing is stored on a server. Without that part, the page shows the sample, and the sample works without JavaScript.

## Gig goal tracker bar
- Embed: https://jeanettec1984.github.io/digimart-embeds/gig-goal/

A neon weekly goal bar for the Gig Worker Tracker template. Log each shift with the quick buttons, set a goal, and the bar shows progress, a pace marker for the day, what's left, and what's needed per day. It resets each Monday (`?weekstart=sun` for Sunday weeks) and saves only in the viewer's browser. `?goal=800&earned=512&shifts=6` shows fixed numbers with no buttons; `?currency=£` changes the symbol.
