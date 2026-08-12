# Sketch Relay candidate evidence

- Source base: public catalog `main` `77cbf469f31ed3c90702aa289caa4282b1ce6143`, revision 19.
- Pack source commit: `5dfc999f5f0c12de618d3dc2b2ac16308900c193`.
- Engine: `canvasGuess` v1; two to four players; eight bounded prompts; four drawer rotations; at most eight strokes per round.
- Rule difference: the drawer sees a private prompt, submits bounded strokes, another seat submits a prompt guess, scores are assigned to drawer and guesser, and the drawer rotates. It is a drawing/guessing relay, not a tile or hidden-vote ruleset.
- Legal replay: stroke + correct-guess vectors cover every declared count. Checksums are 2 seats `baedc990861cc7ca`, 3 seats `dde8a836c2ba1a6a`, and 4 seats `0f4356f2bca3bc96`; winner seat is 0 in each vector.
- Pack gate: schema 2, official signature key ID `playable-content-2026-02`, 3,655 bytes, content SHA-256 `bf27c30b63871d71954a1b32e5c33d31c0a6324b12b2d02eb066a472aded19f2`, no resources.
- Fair-Bot contract: the Bot draws a fixed legal two-point stroke when it is drawer and chooses a legal prompt index when it is guesser; it never reads the drawer’s private prompt outside its own observation.
- UI contract: the canvas and prompt/score summary occupy the playfield; draw, guess and submit controls are large lower-band actions reachable by either thumb and include non-color labels/state.
- Open publisher evidence: normal current-Build import, screenshot on a short iPhone, Result/Rematch, public Pages URL and offline Add/Play have not been claimed on this candidate ref.
