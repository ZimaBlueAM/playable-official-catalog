# Match-clear factory batch A

This directory records the public audit scope for the 2026-08-11 candidate batch.
The three packs are signed, non-executable schema-2 declarations for the installed
`matchClear` engine. No source code, scripts, runtime, or private key is included.

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Cascade Relay | 6×5, 5 colors | 3 | 12 | 2–6 | Adjacent swaps occupy the lower thumb-reach board; cascades pass scoring momentum by turn. |
| Corner Bloom | 6×6, 6 colors | 4 | 18 | 2–4 | Four-tile blooms reward deliberate corner-to-center swaps on the lower-screen board. |
| Quadra Pulse | 4×6, 4 colors | 3 | 20 | 2–4 | Narrow four-column board keeps every swap in a compact lower-half thumb zone. |

Source and license for every pack are the official `LicenseRef-Playable` declaration
with attribution to Playable Studio. Deterministic publisher vectors are sealed by the
private Playable content key locally; only their resulting signed envelopes are public.

## Batch B

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Orbit Garden | 7×5, 5 colors | 3 | 14 | 2–6 | Seven columns remain within the lower-half thumb sweep; adjacent vertical swaps create shared garden chains. |
| Switchback | 5×7, 6 colors | 3 | 15 | 2–5 | The taller five-column board preserves one-handed reach while vertical swaps reverse crowded columns. |
| Tide Three | 8×4, 4 colors | 3 | 10 | 2–4 | The low four-row board keeps horizontal tides visible and every move thumb-accessible in the lower screen. |

## Batch C

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Hexa Drift | 6×6, 5 colors | 3 | 13 | 2–6 | The square board keeps the lower-half swap grid balanced for one-handed drift moves. |
| Ladder Bloom | 5×8, 5 colors | 4 | 17 | 2–4 | Five columns keep the vertical ladder readable and reachable while four-tile blooms demand planning. |
| Shortwave | 9×4, 6 colors | 3 | 11 | 2–5 | The shallow wide board keeps short horizontal waves and all adjacent swaps in thumb range. |

## Batch D

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Mosaic March | 7×6, 4 colors | 3 | 16 | 2–6 | The seven-column lower board supports quick one-handed lane changes and passing turns. |
| Fourfold Forge | 4×7, 5 colors | 4 | 14 | 2–4 | A compact four-column tower keeps vertical four-run setup inside the thumb sweep. |
| Rainline | 8×5, 6 colors | 3 | 12 | 2–5 | The low wide board makes horizontal rain lines visible and adjacent swaps reachable. |

## Batch E taxonomy sidecars

Batch E stores bounded taxonomy only in `batch-20260811-e.manifest.json` and
`audits/batch-20260811-e.json`. The signed schema-1 catalog intentionally omits
these fields until Build107 taxonomy transport is sealed; this preserves Build106
catalog verification and old-client availability. Carrier is the homepage class;
mechanics are the secondary filters. No difficulty label is used.

## Batch F

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Crosswind | 7×7, 5 colors | 3 | 18 | 2–6 | The square lower board supports short adjacent cross-current swaps within one-thumb reach. |
| Fourbeat | 6×5, 4 colors | 4 | 12 | 2–4 | The compact grid keeps deliberate four-run setup in the lower thumb sweep. |
| Longlight | 10×4, 5 colors | 3 | 9 | 2–5 | Four shallow rows make wide horizontal triples visible and reachable for quick rounds. |

Batch F taxonomy follows the same sidecar-only contract in
`batch-20260811-f.manifest.json` and `audits/batch-20260811-f.json`. The signed
schema-1 catalog contains no taxonomy fields.

## Batch G

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Quint Arc | 8×8, 6 colors | 5 | 20 | 2–6 | Long five-tile arcs use short adjacent swaps on the lower board; the active area remains one-thumb reachable. |
| Pocket Weave | 4×10, 3 colors | 4 | 16 | 2–4 | Four narrow columns keep every vertical weave within the lower thumb sweep. |
| Flash Mosaic | 10×5, 8 colors | 3 | 7 | 2–5 | Five shallow rows expose scarce triples for quick one-thumb horizontal scanning. |

Batch G taxonomy is recorded only in `batch-20260811-g.manifest.json` and
`audits/batch-20260811-g.json`; revision 15 remains a Build106-compatible
schema-1 catalog with taxonomy stripped.

## Batch H

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Triple Canal | 5×9, 7 colors | 3 | 21 | 2–6 | Five narrow columns keep long vertical play inside a one-thumb lower-screen lane. |
| Fivefold Pocket | 5×10, 4 colors | 5 | 15 | 2–4 | Full-width five-tile bands use precise adjacent swaps in a narrow thumb-reachable tower. |
| Square Sprint | 4×4, 3 colors | 3 | 6 | 2–3 | The entire compact board fits the lower thumb sweep for six rapid turns. |

Batch H taxonomy is sidecar-only in `batch-20260811-h.manifest.json` and
`audits/batch-20260811-h.json`; revision 16 contains no taxonomy fields.

## Batch I

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Dual Beam | 6×6, 5 colors | 5 | 10 | exactly 2 | Short adjacent swaps on the lower square board create rare five-tile duel lines. |
| Party Cascade | 8×6, 3 colors | 3 | 24 | 3–6 | Dense cascades use a shallow six-row board and one-thumb turns shared by a party. |
| Twin Stripe | 10×6, 7 colors | 4 | 12 | exactly 2 | A low wide field keeps scarce four-tile stripes visible and reachable in a quick duel. |

Batch I taxonomy is sidecar-only in `batch-20260811-i.manifest.json` and
`audits/batch-20260811-i.json`. It explicitly audits single-valued player tags:
strict two-player games omit `party-3-6`, while the 3–6 player game omits
`two-player`. Revision 17 remains schema-1 compatible.

## Batch J

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Five Crown | 6×10, 3 colors | 5 | 18 | 4–6 | A six-column tower keeps long five-tile party moves inside a narrow one-thumb lane. |
| Micro Spectrum | 4×5, 8 colors | 3 | 5 | exactly 2 | The tiny lower board is fully reachable while eight colors make each five-turn duel scarce. |
| Grand Weave | 9×9, 4 colors | 4 | 30 | 2–6 | The active square is operated through short adjacent swaps, with the lower half carrying frequent input. |

Batch J taxonomy is sidecar-only in `batch-20260811-j.manifest.json` and
`audits/batch-20260811-j.json`; revision 18 remains schema-1 compatible and
contains no taxonomy fields.

## Batch K

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Four Corners | 8×10, 8 colors | 4 | 22 | 3–5 | Eight columns keep high-color four-run setup within short one-thumb adjacent swaps. |
| Tiny Crown | 5×5, 3 colors | 5 | 8 | 2–4 | The compact board fits the lower thumb sweep while every clear spans the full width. |
| Wide Current | 10×10, 6 colors | 3 | 40 | 5–6 | Frequent input remains short adjacent swaps in the lower active rows of the maximum board. |

Batch K taxonomy is sidecar-only in `batch-20260811-k.manifest.json` and
`audits/batch-20260811-k.json`; revision 19 contains no taxonomy fields.

## Batch L

| Pack | Board | Match | Turns | Players | Interaction note |
| --- | --- | --- | --- | --- | --- |
| Six Seat Spark | 7×4, 3 colors | 4 | 12 | exactly 6 | Four shallow rows keep all strict-six-player moves inside the lower thumb sweep. |
| Dual Lattice | 7×8, 8 colors | 5 | 14 | exactly 2 | Seven narrow columns support deliberate one-thumb five-line setup in a duel. |
| Party Pebbles | 4×6, 6 colors | 3 | 8 | 3–4 | The compact board is fully thumb reachable for a short party round. |

Batch L taxonomy is sidecar-only in `batch-20260811-l.manifest.json` and
`audits/batch-20260811-l.json`; revision 20 contains no taxonomy fields.
