---
test_id: SF-DTCX-APPLICATION-0001
status: synthetic_crosswalk_application
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
schema_effect: none
external_action: none
---

# SF Decision-Time Crosswalk Application 0001

## Boundary

This provisional synthetic application tests the five decision-time controls
against one fixture without merging their decision objects. It adds no field or
record, accepts no schema, infers no authority exercise, duty, cause, outcome,
or remedy, requests no action, and performs no external action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- `A-old` remains active and is reused at `T0`; the admitted sequence contains
  no retirement or replacement event.
- Owner `O-window` holds relevant review, stop, escalation, approval or
  rejection, and revision authority from `T-1` through `T+1`.
- Contradiction `K-one` is displayed, routed, and disputed at `T-1`; those
  events are owner-visible to `O-window` before `T0`.
- Validation burden `VB-new` exists at `T0`. No completed validation covers it
  before `T0`; `V-late` completes at `T1` and is then backdated to `T0`.
- Route `R-capable` can carry `K-one` to `O-window`. Synthetic condition
  `C-stop` keeps qualification stopped and unresolved at `T0` while `K-one`
  remains unresolved.
- Every non-target core gate passes only as a supplied synthetic premise. The
  fixture does not establish real-world validation adequacy, authority
  exercise, duty, cause, remedy, or outcome.

## Control Results

| Control | Result | Reason | No other effect |
|---|---|---|---|
| `SF-TC-0001` | Pass | `A-old` remains active and is reused at `T0`. | Owner authority, evidence handling, validation timing, and stop condition remain separate. |
| `SF-DRA-0001` | Pass | `O-window` holds relevant authority from `T-1` through `T+1`. | Reuse, evidence handling, validation timing, and stop condition remain separate. |
| `SF-ORC-0001` | Pass | `K-one` is displayed, routed, disputed, and owner-visible at `T-1`. | Reuse, owner authority, validation timing, and stop condition remain separate. |
| `SF-VBT-0001` | Fail | `V-late` completes at `T1` and is backdated to the `T0` decision. | Reuse, owner authority, evidence handling, and stop condition remain separate. |
| `SF-CSC-0001` | Pass | `C-stop` keeps qualification unresolved at `T0` while `K-one` remains unresolved. | Reuse, owner authority, evidence handling, and validation timing remain separate. |

## Candidate Gate Trace

- `assumption_source_context`: pass — supplied premise.
- `accountable_review_owner`: pass — supplied premise.
- `affected_system_and_standing`: pass — supplied premise.
- `changed_condition`: pass — supplied premise.
- `validation_burden`: fail — post-decision `V-late` cannot satisfy `VB-new`
  at `T0`.
- `observation_environment`: pass — supplied premise.
- `delegation_visibility_gap`: pass — supplied premise.
- `absorber_or_counterevidence`: pass — supplied premise.
- `correction_route_stop_condition`: pass — supplied premise.

No other failed gate is inferred.

## Verdict

Refuse qualification. `SF-VBT-0001` fails; the other four decision-time
controls pass only as supplied synthetic premises.

## Candidate Effect

Crosswalk application artifact only. The nine fields, five positive records,
provisional status, acceptance boundary, and no-remedy rule remain unchanged.
