---
test_id: SF-VBT-BRIDGED-COVERAGE-0001
status: synthetic_bridged_validation_coverage_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
schema_effect: none
external_action: none
---

# SF VBT Bridged Coverage 0001

## Boundary

This provisional synthetic test separates timely validation events from an
admitted timely bridge showing that their scope covers the decision-time
burden. It adds no field or record, accepts no schema, infers no real-world
adequacy, authority exercise, duty, cause, outcome, or remedy, requests no
action, and performs no external action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- Validation burden `VB-new` exists at `T0` and specifically requires checking
  whether reused assumption `A-old` remains adequate under `C-new`.
- `D-unbridged` cites `V-assumption` and `V-condition`, both completed and
  owner-visible at `T-1`. Their admitted scopes separately cover `A-old` and
  `C-new`, but the packet supplies no bridge showing that either event or their
  combination addresses `VB-new`.
- `D-bridged` cites the same two events plus explicit synthetic bridge
  `BR-validation`, admitted before `T0`, which states that the combined checks
  cover `A-old` under `C-new` and address `VB-new`.
- `D-late-bridge` cites the same two events, but `BR-validation-late` is not
  admitted or owner-visible until `T1`, after `T-reuse` is final.
- Every non-target core gate passes only as a supplied synthetic premise. The
  fixture does not establish real-world adequacy, authority exercise, duty,
  cause, remedy, or outcome.

## Validation Ledger

| Draft | Events | Completed | Owner-visible | Bridge | Covers `VB-new` | Timing | Scope | Qualification |
|---|---|---|---|---|---|---|---|---|
| `D-unbridged` | `V-assumption` plus `V-condition` | `T-1` | `T-1` | None | No | Pass | Fail | Fail |
| `D-bridged` | `V-assumption` plus `V-condition` | `T-1` | `T-1` | `BR-validation` at `T-1` | Yes | Pass | Pass | Continue gate checks |
| `D-late-bridge` | `V-assumption` plus `V-condition` | `T-1` | `T-1` | `BR-validation-late` at `T1` | Yes | Fail | Pass | Fail |

## Distinction

Event existence, scope coverage, bridge evidence, completion time,
owner-visibility time, decision time, synthetic gate result, real-world
adequacy, authority exercise, duty, outcome, and remedy remain separate.
`D-unbridged` fails scope rather than timing. `D-late-bridge` fails bridge
timing rather than source-event timing.

## Candidate Gate Trace

- `assumption_source_context`: pass — supplied premise.
- `accountable_review_owner`: pass — supplied premise.
- `affected_system_and_standing`: pass — supplied premise.
- `changed_condition`: pass — supplied premise.
- `validation_burden`: `D-unbridged` fail; `D-bridged` pass;
  `D-late-bridge` fail.
- `observation_environment`: pass — supplied premise.
- `delegation_visibility_gap`: pass — supplied premise.
- `absorber_or_counterevidence`: pass — supplied premise.
- `correction_route_stop_condition`: pass — supplied premise.

No other failed gate is inferred.

## Verdict

Multiple timely events do not cover the decision-time burden without an
admitted timely bridge.

## Candidate Effect

Bridged-coverage test only. The nine fields, five positive records,
provisional status, acceptance boundary, and no-remedy rule remain unchanged.
