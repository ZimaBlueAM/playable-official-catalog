# Playable Official Catalog

This public directory contains only signed, non-executable Playable content
packs and the signed catalog that describes them. The `.playablepack.json`
suffix is intentional: GitHub Pages serves JSON with the MIME type accepted by
the Playable catalog client.

Never add signing keys, source code, or arbitrary executable content here.

## Games

- **Take Five** — take one to three tokens; the final move wins.
- **Prism Shift** — swap neighboring prisms to clear matching lines on a
  thumb-friendly 5×5 board.
- **Signal Circle** — read the table talk, find the lone signal, and vote.
- **Lantern Watch** — bluff and observe to catch the route-knowing watcher.
- **Postcard Scribble** — draw a tiny postcard clue and guess the destination.
- **Shadow Recipe** — sketch a mystery ingredient for the table to identify.
- **Ribbon Code** — read the room and vote out the false route.
- **Weather Front** — spot the calm-weather team before the vote storm.
- **Constellation Notes** — sketch a starry clue and name the pattern.
- **Whisper Sketch** — turn a quiet everyday sound into a tiny drawing.
- **Tide Mark** — watch the table and vote before the current turns.
- **Garden Keeper** — find the keeper hiding among the gardeners.
- **Tiny Toolbox** — draw an everyday tool for the table to identify.
- **Market Doodles** — sketch a market find and race to name it.
- **Mosaic Secret** — compare the room and vote before the picture breaks.
- **Orbit Signal** — notice the odd movement and vote for the quiet satellite.
- **Cabin Sketches** — draw a cozy cabin detail for the table to guess.
- **Parade Doodles** — sketch a parade favorite and race to call it out.
- **Clockwork Secret** — spot the strange rhythm and vote before the bell.
- **Bell Tower** — listen to the table and vote for the hidden ringer.
- **Picnic Pictures** — draw a picnic favorite for friends to guess.
- **Library Doodles** — sketch a quiet library object and race to recognize it.
- **Harbor Signal** — read the crew and vote before departure.
- **Kite String** — compare stories and find the hidden flyer.
- **Trail Signs** — draw a trail-side clue for friends to name.
- **Workshop Scribbles** — sketch a handmade object and race to identify it.
- **Last Platform** — compare the clues and vote before departure.
- **Teahouse Whisper** — read the table before the cups cool.
- **Seaside Sketches** — draw a beach-side clue for friends to name.
- **Garage Doodles** — sketch a garage find and race to identify it.
- **Observatory Shift** — compare the reports and vote before dawn.
- **Ferry Ticket** — read the group and find the hidden passenger.
- **Greenhouse Sketches** — draw a garden clue for friends to name.
- **Campsite Doodles** — sketch a camp object and race to identify it.
- **Museum Label** — compare the stories and vote before closing.
- **Lighthouse Log** — inspect the crew and find the hidden editor.
- **Bakery Sketches** — draw a bakery favorite for friends to name.
- **Festival Sketchbook** — sketch a festival sight and race to identify it.

Candidate taxonomy (`carrier`, `mechanics`, `players`, `pace`, `context`, and
`input`) and its audit are maintained separately from the signed schema 1
catalog so older Playable builds retain feed compatibility. `carrier` is the
homepage grouping; `mechanics` is the secondary recommendation filter.
See `factory/social-canvas/candidate-manifest.json` and
`audits/social-canvas-taxonomy.json`.

The catalog is signed and revisioned. Playable verifies the catalog and every
pack before activation, keeps a last-known-good version for offline play, and
never downloads executable code from this repository.
