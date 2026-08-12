# Declarative diversity batch — 2026-08-12

This is a bounded candidate ref based directly on public `main` commit `77cbf469f31ed3c90702aa289caa4282b1ce6143` (catalog revision 19, 25 entries). It does not alter `catalog.json`, increment a revision, touch private product branches, or reuse the rejected revision 108/305 aggregate chains.

The batch contains exactly three signed schema-2 data-only packs:

| Game | Engine | Distinct rule | Declared players | Replay evidence |
| --- | --- | --- | --- | --- |
| `pack-three-line` / Three Line / 三连方阵 | `gridBoard` | Free placement, no gravity, first straight line of three | 2 | `games/pack-three-line-v1.playablepack.json` test vector ends in `4586d29f0a423abe` |
| `pack-secret-majority` / Secret Majority / 暗票多数 | `hiddenRole` | Private roles, one ballot, deterministic majority elimination | 2–4 | `games/pack-secret-majority-v1.playablepack.json` has terminal vectors for 2/3/4: `c09fe47fcb2f2816`, `cccb780b0db24a3b`, `c6ff2a71f58d588c` |
| `pack-sketch-relay` / Sketch Relay / 画猜接力 | `canvasGuess` | Rotating drawer, private prompt, stroke + guess scoring over four rounds | 2–4 | `games/pack-sketch-relay-v1.playablepack.json` has terminal vectors for 2/3/4: `baedc990861cc7ca`, `dde8a836c2ba1a6a`, `0f4356f2bca3bc96` |

## Completed machine checks

- The official declarative pack tool validated every definition and generated every checksum before signing.
- Every envelope is schema 2, uses the existing official content key ID `playable-content-2026-02`, contains no resources, and binds byte count, envelope SHA-256 and content SHA-256 in `factory-candidate-manifest.json` and `tag-audit.json`.
- English and Simplified Chinese metadata, source URL, `LicenseRef-Playable`, deterministic legal vectors, bounded rules and mechanism-difference notes are present.
- The isolated installed runtime/provider contract has deterministic fair local Bot coverage for `gridBoard`, `hiddenRole` and `canvasGuess`; core/UI package tests and an App candidate build passed. The Bot uses only legal observable state: it never reads hidden roles or a drawer’s prompt.
- The UI sidecars record the lower-half thumb layout, 44pt controls and non-color state contract. They intentionally leave normal App import, Result/Rematch screenshots, GitHub Pages mirroring and offline Add/Play as `open` publisher evidence rather than fabricating a release claim.

## Publisher handoff / remaining gate

The only remaining work before a catalog revision can change is publisher-controlled replay from Home → Setup → Solo/local Bot → legal actions → terminal Result → Rematch, followed by publishing the same exact pack bytes to GitHub Pages and verifying the public URL, signature, hash, byte count and offline Add/Play. Until those checks are closed, this ref remains a candidate and `catalogRevision` stays 19.
