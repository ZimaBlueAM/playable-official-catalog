# Last One Loses runtime audit

Date: 2026-08-11  
Evidence: live iPhone 17e Simulator UI, software only.

## Observed

- Games displayed the bilingual title `最后一个输` / `Last One Loses` and bilingual summary.
- The directory card declared exactly two players.
- Add completed and the card changed to `已添加 · 可离线游玩`.
- Play opened Setup. The visible preset was `快速 · 17 颗`, marked recommended and described as a two-player match.
- The primary Add/Play and Create Room actions were in the lower portion of the iPhone layout and reachable in the thumb zone.
- The room action entered the room/chat flow without a visible crash or deadlock.

## Not claimed

Only one simulator was available for this run. Since the game declares a two-player minimum and maximum, no complete match, Result, or Rematch was fabricated from a single-seat room flow. Physical-device and human evidence remain OPEN. Touch target sizes were not measured with a calibrated geometry tool.

Verdict: `SOFTWARE PARTIAL / FULL MATCH OPEN`.
