---
test_id: SF-VBT-RETIRED-COMPONENT-COVERAGE-0001
candidate: SF-SCHEMA-CANDIDATE-0001
status: synthetic_retired_component_coverage_proposal
source_material: synthetic
external_action: none
---

# SF VBT Retired Component Coverage 0001

## Boundary

This proposal is proposal-only, provisional, synthetic, and uncertain. No
remedy, promotion, field change, new record, authority-exercise inference,
duty inference, causal inference, outcome inference, or action is permitted.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- At `T-2`, validation burden `VB-v1` has three named components:
  `VC-assumption`, `VC-interaction`, and `VC-legacy`. Validation events for all
  three components complete and become owner-visible at `T-2`; timely bridge
  `BR-v1` explicitly covers all three.
- At `T-1`, admitted burden revision `VB-v2` removes `VC-legacy` and preserves
  only `VC-assumption` and `VC-interaction` as the named decision-time burden.
- `D-current` cites timely events `V-assumption` and `V-interaction` plus
  timely bridge `BR-v2`, which explicitly covers both current components.
- `D-legacy-only` cites only `V-legacy` and bridge `BR-legacy`, which cover the
  removed component but neither current component.
- `D-superset` cites all three events and `BR-v1`, which explicitly covers the
  two current components plus the removed component.
- Every non-target core gate is supplied as `PASS`. All supplied events,
  bridges, and the burden revision are timely and owner-visible. The fixture
  does not prove real-world adequacy, authority exercise, duty, cause, remedy,
  or outcome.

## Validation Ledger

draft: D-current | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-v2 at T-1 | covers_current: VC-assumption plus VC-interaction | covers_removed: NONE | current_coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS

draft: D-legacy-only | burden: VB-v2 | events: V-legacy | bridge: BR-legacy at T-1 | covers_current: NONE | covers_removed: VC-legacy | current_coverage_result: FAIL | qualification_result: FAIL

draft: D-superset | burden: VB-v2 | events: V-assumption plus V-interaction plus V-legacy | bridge: BR-v1 at T-2 | covers_current: VC-assumption plus VC-interaction | covers_removed: VC-legacy | current_coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS

## Distinction

Current burden membership, historical burden membership, event existence,
bridge existence, current-component coverage, surplus removed-component
coverage, completion time, owner-visibility time, decision time, synthetic gate
result, real-world adequacy, authority exercise, duty, outcome, and remedy
remain separate. Removed-component coverage is neither required nor
disqualifying.

## Candidate Gate Trace

assumption_source_context: PASS — supplied premise

accountable_review_owner: PASS — supplied premise

affected_system_and_standing: PASS — supplied premise

changed_condition: PASS — supplied premise

validation_burden: D-current PASS; D-legacy-only FAIL; D-superset PASS

observation_environment: PASS — supplied premise

delegation_visibility_gap: PASS — supplied premise

absorber_or_counterevidence: PASS — supplied premise

correction_route_stop_condition: PASS — supplied premise

Infer no other failed gate.

## Verdict

TEST FOR NEW PRESSURE — COVERAGE IS JUDGED AGAINST THE CURRENT NAMED DECISION-TIME BURDEN; COVERAGE OF A REMOVED COMPONENT IS NEITHER A SUBSTITUTE NOR A FAILURE

## Candidate Effect

PROPOSE RETIRED-COMPONENT COVERAGE TEST ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE

## Frontier Verification

- Fixture facts.
- Three ledger records.
- Nine gate results.
- Verdict/effect coherence.
- Raw frontmatter and boundaries.
