# Current-base declarative diversity repair — 2026-08-12

This resubmission is based directly on public `main` commit `3c0ed1e6ebda159c13446582ea3fed5b6221c029`, whose catalog is revision 19 with 25 entries. It preserves the catalog, provenance pages and all existing game packs. It does not replay revision 108/305 aggregates and does not write public `main`. It carries forward the same three draft bodies from `factory/declarative-diversity/20260812-current-base-unsigned`; it is not counted as three new games.

The bounded repair carries three body-only candidates that are absent from current main:

| ID | Engine | Rule distinction | Terminal vectors |
| --- | --- | --- | --- |
| `pack-three-line` | `gridBoard` | Free 3×3 placement, no gravity, first line of three | 2 seats: `4586d29f0a423abe` |
| `pack-secret-majority` | `hiddenRole` | Private roles plus one bounded majority ballot | 2/3/4 seats: `c09fe47fcb2f2816`, `cccb780b0db24a3b`, `c6ff2a71f58d588c` |
| `pack-sketch-relay` | `canvasGuess` | Rotating drawer, private prompt, bounded stroke/guess scoring | 2/3/4 seats: `baedc990861cc7ca`, `dde8a836c2ba1a6a`, `0f4356f2bca3bc96` |

The body drafts are non-executable JSON only. Their canonical body hashes are retained from the validated definitions and their metadata contains English and Simplified Chinese, source and `LicenseRef-Playable`. No signed envelope is included because the existing secure workstation key was proven not to match the Build runtime's trusted public key for `playable-content-2026-02`; no replacement key was generated. The latest main and Pages baseline were rechecked at revision 19/25 with matching catalog body hash `72cb26b793cf8b9b1cc284963f050e7f300f0c3071159110e156b4776c2974ed`.

## Gate state

- Body schema/rule budget/legal vectors: pass in the isolated declarative pack tool before the previous signed attempt.
- Mechanism de-duplication: pass for the three independent families; current main has no matching game IDs or rules.
- Taxonomy/provenance: recorded in `factory-candidate-manifest.json` and `tag-audit.json`; carriers are scalar.
- Official signature, envelope hash/byte binding, Pages URL and offline Add/Play: blocked because no trusted envelope can be created in this environment.
- Normal Home → Setup → Solo/fair Bot → Result → Rematch: blocked until the isolated provider contract is merged into the private App runtime and publisher replay is run. This public ref does not claim that evidence.

## Minimal handoff

1. Release owner supplies the existing approved content signing key through the secure release path; its derived public key must equal the Build trust-ring public key for `playable-content-2026-02`.
2. Product owner merges the isolated provider contract for `hiddenRole`/`canvasGuess`/`matchClear` into the private App branch and reruns the normal journey tests.
3. Publisher signs these exact body drafts, materializes only a bounded catalog delta from this current base, mirrors to Pages, verifies signatures/hashes/bytes and offline Add/Play, then alone increments the catalog revision.
