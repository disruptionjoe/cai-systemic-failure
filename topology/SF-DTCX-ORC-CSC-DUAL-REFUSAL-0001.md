---
test_id: SF-DTCX-ORC-CSC-DUAL-REFUSAL-0001
status: synthetic_crosswalk_dual_refusal
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
schema_effect: none
external_action: none
---

# SF Decision-Time ORC CSC Dual Refusal 0001

## Boundary

This provisional synthetic application tests two independent refusals without
merging the five decision-time controls. It adds no field or record, accepts no
schema, infers no authority exercise, duty, cause, outcome, or remedy, requests
no action, and performs no external action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- `A-old` remains active and is reused at `T0`; the admitted sequence contains
  no retirement or replacement event.
- Owner `O-window` holds relevant review, stop, escalation, approval or
  rejection, and revision authority from `T-1` through `T+1`.
- Contradiction `K-one` is displayed at `T-1`, but routing and dispute occur
  only at `T1`, after `T-reuse` is final.
- Validation burden `VB-new` exists at `T0`. Synthetic validation `V-pre`
  completes, is owner-visible, and covers `VB-new` at `T-1`.
- Route `R-capable` can carry `K-one` to `O-window`, but the fixture supplies no
  source- or synthetic-backed condition keeping qualification stopped or
  unresolved while `K-one` remains unresolved.
- Every non-target core gate passes only as a supplied synthetic premise. The
  fixture does not establish real-world validation adequacy, authority
  exercise, duty, cause, remedy, or outcome.

## Control Results

| Control | Result | Reason | No other effect |
|---|---|---|---|
| `SF-TC-0001` | Pass | `A-old` remains active and is reused at `T0`. | Owner authority, evidence handling, validation timing, and stop condition remain separate. |
| `SF-DRA-0001` | Pass | `O-window` holds relevant authority from `T-1` through `T+1`. | Reuse, evidence handling, validation timing, and stop condition remain separate. |
| `SF-ORC-0001` | Fail | `K-one` routing and dispute occur only at `T1`, after `T-reuse` is final. | Reuse, owner authority, validation timing, and stop condition remain separate. |
| `SF-VBT-0001` | Pass | `V-pre` covers `VB-new` and is owner-visible at `T-1`. | Reuse, owner authority, evidence handling, and stop condition remain separate. |
| `SF-CSC-0001` | Fail | `R-capable` has no backed condition keeping qualification unresolved while `K-one` remains unresolved. | Reuse, owner authority, evidence handling, and validation timing remain separate. |

## Candidate Gate Trace

- `assumption_source_context`: pass — supplied premise.
- `accountable_review_owner`: pass — supplied premise.
- `affected_system_and_standing`: pass — supplied premise.
- `changed_condition`: pass — supplied premise.
- `validation_burden`: pass — `V-pre` covers `VB-new` at `T-1`.
- `observation_environment`: fail — routing and dispute occur only at `T1`.
- `delegation_visibility_gap`: pass — supplied premise.
- `absorber_or_counterevidence`: pass — supplied premise.
- `correction_route_stop_condition`: fail — no backed stop condition is
  supplied.

No other failed gate is inferred.

## Verdict

Refuse qualification. `SF-ORC-0001` and `SF-CSC-0001` fail independently;
TC, DRA, and VBT pass only as supplied synthetic premises.

## Candidate Effect

ORC/CSC dual-refusal application only. The nine fields, five positive records,
provisional status, acceptance boundary, and no-remedy rule remain unchanged.
