---
test_id: SF-VBT-REVISED-MULTI-COMPONENT-BRIDGE-0001
status: synthetic_revised_multi_component_bridge_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
schema_effect: none
external_action: none
---

# SF VBT Revised Multi-Component Bridge 0001

## Boundary

This provisional synthetic test separates a prior complete validation bridge
from coverage of the current named decision-time burden after a pre-decision
revision. It adds no field or record, accepts no schema, infers no real-world
adequacy, authority exercise, duty, cause, outcome, or remedy, requests no
action, and performs no external action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- At `T-2`, validation burden `VB-v1` has two named components:
  `VC-assumption` and `VC-interaction`. Validation events `V-assumption` and
  `V-interaction` complete and become owner-visible at `T-2`; timely bridge
  `BR-v1` explicitly covers both components.
- At `T-1`, admitted burden revision `VB-v2` adds named component
  `VC-environment` because the decision environment changed before `T0`.
- `D-stale` cites `BR-v1` without a validation event or bridge for
  `VC-environment`.
- `D-revised` cites `V-assumption`, `V-interaction`, and timely event
  `V-environment`, plus timely bridge `BR-v2`, which explicitly covers all
  three `VB-v2` components before `T0`.
- `D-generic` cites all three events and timely bridge `BR-generic`, which says
  only `validation updated` and names no burden component.
- Every non-target core gate passes only as a supplied synthetic premise. All
  supplied events and bridges are timely. The fixture does not establish
  real-world adequacy, authority exercise, duty, cause, remedy, or outcome.

## Validation Ledger

| Draft | Burden | Events | Bridge | Coverage | Missing | Coverage result | Qualification result |
|---|---|---|---|---|---|---|---|
| `D-stale` | `VB-v2` | `V-assumption` plus `V-interaction` | `BR-v1` at `T-2` | `VC-assumption` plus `VC-interaction` | `VC-environment` | Fail | Fail |
| `D-revised` | `VB-v2` | `V-assumption` plus `V-interaction` plus `V-environment` | `BR-v2` at `T-1` | `VC-assumption` plus `VC-interaction` plus `VC-environment` | None | Pass | Continue gate checks |
| `D-generic` | `VB-v2` | `V-assumption` plus `V-interaction` plus `V-environment` | `BR-generic` at `T-1` | No named component | All named coverage | Fail | Fail |

## Distinction

Burden revision, event existence, bridge existence, named components,
component coverage, completion time, owner-visibility time, decision time,
synthetic gate result, real-world adequacy, authority exercise, duty, outcome,
and remedy remain separate. None of the three drafts fails timing; all supplied
events and bridges are timely.

## Candidate Gate Trace

- `assumption_source_context`: pass — supplied premise.
- `accountable_review_owner`: pass — supplied premise.
- `affected_system_and_standing`: pass — supplied premise.
- `changed_condition`: pass — supplied premise.
- `validation_burden`: `D-stale` fail; `D-revised` pass; `D-generic` fail.
- `observation_environment`: pass — supplied premise.
- `delegation_visibility_gap`: pass — supplied premise.
- `absorber_or_counterevidence`: pass — supplied premise.
- `correction_route_stop_condition`: pass — supplied premise.

No other failed gate is inferred.

## Verdict

A timely bridge must cover every named component of the current decision-time
validation burden.

## Candidate Effect

Revised multi-component bridge test only. The nine fields, five positive
records, provisional status, acceptance boundary, and no-remedy rule remain
unchanged.
