---
test_id: SF-VBT-MULTI-COMPONENT-BRIDGE-0001
status: synthetic_multi_component_bridge_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
schema_effect: none
external_action: none
---

# SF VBT Multi-Component Bridge 0001

## Boundary

This provisional synthetic test separates timely bridge existence from
coverage of every named component in one decision-time validation burden. It
adds no field or record, accepts no schema, infers no real-world adequacy,
authority exercise, duty, cause, outcome, or remedy, requests no action, and
performs no external action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- Validation burden `VB-new` exists at `T0` and has two named components:
  `VC-assumption`, checking whether `A-old` remains adequate under `C-new`, and
  `VC-interaction`, checking the supplied interaction between `A-old` and
  `C-new`.
- Validation events `V-assumption` and `V-interaction` both complete and become
  owner-visible at `T-1`.
- `D-partial` cites both events and timely bridge `BR-partial`, but the bridge
  covers only `VC-assumption`; it does not cover `VC-interaction`.
- `D-complete` cites both events and timely bridge `BR-complete`, which
  explicitly covers both named components of `VB-new` before `T0`.
- `D-generic` cites both events and timely bridge `BR-generic`, which says only
  `validation complete` and names neither burden component.
- Every non-target core gate passes only as a supplied synthetic premise. The
  fixture does not establish real-world adequacy, authority exercise, duty,
  cause, remedy, or outcome.

## Validation Ledger

| Draft | Events | Completed | Owner-visible | Bridge | Coverage | Coverage result | Qualification result |
|---|---|---|---|---|---|---|---|
| `D-partial` | `V-assumption` plus `V-interaction` | `T-1` | `T-1` | `BR-partial` at `T-1` | `VC-assumption` only | Fail | Fail |
| `D-complete` | `V-assumption` plus `V-interaction` | `T-1` | `T-1` | `BR-complete` at `T-1` | `VC-assumption` plus `VC-interaction` | Pass | Continue gate checks |
| `D-generic` | `V-assumption` plus `V-interaction` | `T-1` | `T-1` | `BR-generic` at `T-1` | No named component | Fail | Fail |

## Distinction

Event existence, bridge existence, named burden components, component
coverage, completion time, owner-visibility time, decision time, synthetic
gate result, real-world adequacy, authority exercise, duty, outcome, and remedy
remain separate. None of the three drafts fails timing; all supplied events
and bridges are timely.

## Candidate Gate Trace

- `assumption_source_context`: pass — supplied premise.
- `accountable_review_owner`: pass — supplied premise.
- `affected_system_and_standing`: pass — supplied premise.
- `changed_condition`: pass — supplied premise.
- `validation_burden`: `D-partial` fail; `D-complete` pass; `D-generic` fail.
- `observation_environment`: pass — supplied premise.
- `delegation_visibility_gap`: pass — supplied premise.
- `absorber_or_counterevidence`: pass — supplied premise.
- `correction_route_stop_condition`: pass — supplied premise.

No other failed gate is inferred.

## Verdict

A timely bridge must cover every named component of the decision-time
validation burden.

## Candidate Effect

Multi-component bridge test only. The nine fields, five positive records,
provisional status, acceptance boundary, and no-remedy rule remain unchanged.
