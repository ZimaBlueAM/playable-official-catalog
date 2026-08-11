# Take Five runtime audit

Date: 2026-08-11  
Evidence: live iPhone 17e Simulator UI, software only.

## Observed

- Games displayed the bilingual title `拿五` / `Take Five` and bilingual summary.
- The directory card declared `2–4` players.
- Add completed and the card changed to `已添加 · 可离线游玩`.
- Play opened Setup. The visible recommended preset was `标准`, described as twenty-one tokens and up to four players.
- The primary Add/Play and Create Room actions were in the lower portion of the iPhone layout and reachable in the thumb zone.
- The room action was available without a visible crash or deadlock.

## Complete software journey

- Two booted iPhone simulators used the normal visible App journey; no launch argument or injected state was used.
- The guest showed a catalog refresh failure while retaining the previously added pack, then joined the host room and played successfully from cache.
- Seven alternating legal `Take 3` actions reduced the visible count `21 → 18 → 15 → 12 → 9 → 6 → 3 → 0`.
- Result ranked player 1 as winner and player 2 as loser on both seats.
- The host requested another game, the guest accepted, and both returned to a fresh 21-token game.
- The full match directly verifies `carrier: tiles` and `mechanics: take-away`.

## Not claimed

Physical-device and human evidence remain OPEN. Touch target sizes were not measured with a calibrated geometry tool.

Verdict: `SOFTWARE SIMULATOR FULL MATCH + RESULT + REMATCH PASS / DEVICE + HUMAN OPEN`.
