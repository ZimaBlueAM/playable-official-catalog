# Secret Majority candidate evidence

- Source base: public catalog `main` `77cbf469f31ed3c90702aa289caa4282b1ce6143`, revision 19.
- Pack source commit: `5dfc999f5f0c12de618d3dc2b2ac16308900c193`.
- Engine: `hiddenRole` v1; two to four players; two private teams; one bounded ballot round.
- Rule difference: each seat receives a private role projection, votes once for another active seat, and a deterministic majority/tie-break removes one seat; the survivors decide the result. This is not a card take-away, sliding puzzle or board alignment variant.
- Legal replay: terminal vectors cover every declared count. Checksums are 2 seats `c09fe47fcb2f2816`, 3 seats `cccb780b0db24a3b`, and 4 seats `c6ff2a71f58d588c`; winner seat is 1 in each vector.
- Pack gate: schema 2, official signature key ID `playable-content-2026-02`, 2,420 bytes, content SHA-256 `10f74ba9ba6e5abedb64b200a2ca80269fff314ee0acd0e3027a46d3f23c0353`, no resources.
- Fair-Bot contract: the Bot chooses a legal vote from public active-seat state and does not read `hiddenRoles`; the local player retains one real seat.
- UI contract: role/status information is observation content, while vote targets and confirmation live in the lower thumb-reach band with labels and selected-state feedback.
- Open publisher evidence: normal current-Build import, screenshot on a short iPhone, Result/Rematch, public Pages URL and offline Add/Play have not been claimed on this candidate ref.
