# Prism Shift runtime audit

Date: 2026-08-11  
Evidence: live iPhone 17e and iPhone Air Simulator UI, software only.

## Observed

- Games displayed the bilingual title `棱镜交换` / `Prism Shift` and bilingual summary.
- The directory card declared `2–4` players and retained `已添加 · 可离线游玩` while the Build 104 guest reported catalog refresh failure.
- Play opened Setup. The recommended `标准` preset described a thumb-friendly 5×5 board and sixteen turns.
- Add/Play and Create Room actions were in the lower portion of the iPhone layout.

## Complete software match

- A Build 106 host and Build 104 guest used the normal visible Games and Nearby-room journey; no launch argument or injected state was used.
- The seats completed sixteen alternating legal adjacent swaps. The accepted tile pairs were `7–8`, `9–10`, `13–14`, `3–4`, `1–6`, `1–2`, `3–4`, `2–3`, `9–10`, `2–7`, `12–17`, `2–3`, `12–17`, `7–12`, `6–11`, and `7–8`.
- Each accepted swap formed a same-color line and advanced exactly one turn. This full match directly verifies `carrier: tiles` and `mechanics: alignment, matching, spatial`.
- Result synchronized on both seats: player 1 ranked first with `49`; player 2 ranked second with `35`.

## Open defects

- **Rematch failed.** The host selected `再来一局`; the guest exposed only non-actionable `正在准备再来一局…`; the host then reported `再来一局请求已过期。`
- **End counter is inconsistent.** Both completed-game surfaces displayed `第 17 / 16 回合`.

## Not claimed

Physical-device and human evidence remain OPEN. Touch target sizes were not measured with a calibrated geometry tool.

Verdict: `SOFTWARE SIMULATOR FULL MATCH + RESULT PASS / REMATCH FAIL / DEVICE + HUMAN OPEN`.
