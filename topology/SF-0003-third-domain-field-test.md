---
test_id: SF-0003-THIRD-DOMAIN-TEST
status: provisional_cross_domain_test
records: [SF-0001, SF-0002, SF-0003]
lane: "1"
created: 2026-07-18
external_action: none
---

# SF-0003 Third-Domain Field Test

## Boundary

This test compares `SF-0001`, `SF-0002`, and `SF-0003` only to decide whether
the provisional review-chain fields remain useful after a non-aerospace record.
It does not create an accepted ontology, intervention program, public-health
recommendation, water-system remedy, civil-rights judgment, or CAI doctrine.

## Result

The field set survives a third source-backed record and now deserves a separate
schema-readiness check. It is still not accepted schema. The useful pattern is
narrow: assumption reuse under changed conditions needs visible owner,
validation burden, affected-party standing, observation path, and correction
route before an old assumption is treated as adequate.

## Field Decision

| Field | Decision | Reason |
|---|---|---|
| assumption identifier and source revision | keep provisional | All three records require a load-bearing assumption tied to a source context and revision. |
| assumption owner and accountable review owner | keep provisional | The Flint record broadens owner distinction across local operation, state primacy, and federal oversight. |
| affected system and affected-party standing | keep provisional and strengthen | The third record makes affected-person standing unavoidable, not incidental. |
| changed condition | rename provisional | `Change event` is too narrow; the shared field is changed condition or evidence context. |
| validation method and validation burden | keep provisional | Each record turns on whether old assumptions were revalidated under changed conditions. |
| operating or observation environment | keep provisional | The environment includes technical operation plus how evidence becomes visible or invisible. |
| delegation path and visibility gap | keep provisional | Distributed review remains central across certification, mission review, and drinking-water oversight. |
| counterevidence or absorber model | keep provisional | Each record has a plausible domain-specific absorber that narrows but does not kill the pattern. |
| correction route and stop condition | keep provisional | The records need an owner-visible route for unresolved evidence before harm or continued exposure. |

## Candidate Pressures

Do not promote these yet:

- `hazard_history`: prior tolerated anomalies or infrastructure conditions can
  make new evidence appear normal;
- `observation_request_path`: requests, complaints, measurements, or external
  evidence can fail without becoming an accountable contradiction;
- `jurisdictional_authority_gap`: a reviewing actor can see risk but fail to
  force a stop because formal authority boundaries remain unsettled.

## Next Test

The next useful step is not immediate schema promotion. Run a compact
schema-readiness check that tries to kill or narrow the field set by asking:

1. Which fields are necessary across all three records?
2. Which candidate pressures are merely annotations?
3. What source requirements would prevent a field list from becoming an empty
   ontology?
4. What correction route is required before any schema text is accepted?

Until that check exists, the topology remains provisional.

