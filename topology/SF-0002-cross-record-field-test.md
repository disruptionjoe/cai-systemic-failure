---
test_id: SF-0002-CROSS-TEST-1
status: provisional_cross_record_test
records: [SF-0001, SF-0002]
lane: "1"
created: 2026-07-18
external_action: none
---

# SF-0002 Cross-Record Field Test

## Boundary

This test compares `SF-0001` and `SF-0002` only to decide whether the first
candidate topology fields are still useful. It does not create an accepted
ontology, intervention program, aviation/spaceflight remedy, or CAI doctrine.

## Result

The field set survives as a provisional review-chain pattern, but one field
must broaden and two candidate pressures must remain under watch.

## Field Decision

| Field | Decision | Reason |
|---|---|---|
| assumption identifier and source revision | keep provisional | Both records require a load-bearing assumption tied to a source context. |
| assumption owner and accountable review owner | keep provisional | Both records need owner distinction rather than generic accountability. |
| affected system and affected-party standing | keep provisional | Both records fail if affected-party standing is hidden behind procedure. |
| change event | broaden provisional | `SF-0001` uses changed function/input path; `SF-0002` uses observed anomaly/damage concern. |
| validation method and validation burden | keep provisional | Both records turn on whether a previous assumption remains valid under changed conditions. |
| operating or observation environment | rename provisional | This absorbs the narrower alert/workload field without losing the SF-0001 case. |
| delegation path and visibility gap | keep provisional | Both records need the review path and unresolved uncertainty to remain visible. |
| counterevidence or absorber model | keep provisional | Both records have a plausible narrow absorber that would hide the systemic pattern. |
| correction route and stop condition | keep provisional | Both records need a way to stop reuse of an old assumption or escalate unresolved evidence. |

## Candidate Additions

Do not promote these yet:

- `hazard_history`: repeated non-catastrophic anomalies can make a live event
  appear normal;
- `observation_request_path`: evidence requests can fail without any one owner
  explicitly accepting the unresolved contradiction.

## Next Test

The next useful test is an absorber or third source-backed record from a
different domain. It should try to break the provisional fields by showing a
systemic failure where assumption validation is not the central review object.

