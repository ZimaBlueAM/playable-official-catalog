# Stack Four runtime audit

Date: 2026-08-11  
Evidence: live iPhone 17e Simulator UI, software only.

## Observed

- Games displayed the bilingual title `四连叠` / `Stack Four` and bilingual summary.
- The directory card declared `2–4` players.
- Add completed and the card changed to `已添加 · 可离线游玩`.
- Play opened Setup. The visible preset was `经典 · 7 × 6`, marked recommended and described as a two-to-four-player game.
- The primary Add/Play and Create Room actions were in the lower portion of the iPhone layout and reachable in the thumb zone.
- Create Room entered the room/chat flow without a visible crash or deadlock.

## Not claimed

Only one simulator was available for this run. Because the game declares a minimum of two players, no complete match, Result, or Rematch was fabricated from a single-seat room flow. Physical-device and human evidence remain OPEN. Touch target sizes were not measured with a calibrated geometry tool.

Verdict: `SOFTWARE PARTIAL / FULL MATCH OPEN`.
