---
test_id: SF-VBT-MERGED-COMPONENT-COVERAGE-0001
candidate: SF-SCHEMA-CANDIDATE-0001
status: synthetic_merged_component_coverage_proposal
source_material: synthetic
external_action: none
---

# SF VBT Merged Component Coverage 0001

## Boundary

This artifact is proposal-only, provisional, synthetic, and uncertain. It
contains no remedy, promotion, field change, new record, authority-exercise
inference, duty inference, causal inference, outcome inference, or action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- At `T-2`, validation burden `VB-v1` has two named components:
  `VC-assumption` and `VC-interaction`. Timely events `V-assumption` and
  `V-interaction` complete and become owner-visible at `T-2`; bridge `BR-v1`
  explicitly covers both historical components separately.
- At `T-1`, admitted burden revision `VB-v2` replaces both historical
  components with one current named component, `VC-composite`, requiring the
  assumption-and-interaction relation to be validated as one current object.
- `D-separated` cites only the two historical events and `BR-v1`; none names
  or covers current component `VC-composite`.
- `D-merged` cites timely event `V-composite` and bridge `BR-v2`, which
  explicitly covers current component `VC-composite`.
- `D-label` cites the historical events plus `BR-label`, which calls them
  equivalent to `VC-composite` but does not explicitly cover the current
  composite component.
- Every non-target core gate is supplied as `PASS`. All supplied events,
  bridges, and the burden revision are timely and owner-visible. The fixture
  does not prove real-world adequacy, authority exercise, duty, cause, remedy,
  or outcome.

## Validation Ledger

- `draft: D-separated | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-v1 at T-2 | covers_current: NONE | covers_historical: VC-assumption plus VC-interaction | current_coverage_result: FAIL | qualification_result: FAIL`
- `draft: D-merged | burden: VB-v2 | events: V-composite | bridge: BR-v2 at T-1 | covers_current: VC-composite | covers_historical: NONE | current_coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS`
- `draft: D-label | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-label at T-1 | covers_current: NONE | covers_historical: VC-assumption plus VC-interaction | current_coverage_result: FAIL | qualification_result: FAIL`

## Distinction

Historical separate-component membership, current composite-component
membership, event existence, bridge existence, current-component coverage,
historical-component coverage, completion time, owner-visibility time,
decision time, synthetic gate result, real-world adequacy, authority exercise,
duty, outcome, and remedy remain separate. Coverage of historical separate
components does not prove coverage of the current composite component.

## Candidate Gate Trace

- `assumption_source_context: PASS — supplied premise`
- `accountable_review_owner: PASS — supplied premise`
- `affected_system_and_standing: PASS — supplied premise`
- `changed_condition: PASS — supplied premise`
- `validation_burden: D-separated FAIL; D-merged PASS; D-label FAIL`
- `observation_environment: PASS — supplied premise`
- `delegation_visibility_gap: PASS — supplied premise`
- `absorber_or_counterevidence: PASS — supplied premise`
- `correction_route_stop_condition: PASS — supplied premise`

Infer no other failed gate.

## Verdict

TEST FOR NEW PRESSURE — COVERAGE OF SEPARATE HISTORICAL COMPONENTS DOES NOT
PROVE COVERAGE OF THE CURRENT NAMED COMPOSITE COMPONENT

## Candidate Effect

PROPOSE MERGED-COMPONENT COVERAGE TEST ONLY — NO FIELD, RECORD, STATUS,
ACCEPTANCE, OR REMEDY CHANGE

## Frontier Verification

- fixture facts
- three ledger records
- nine gate results
- verdict/effect coherence
- raw frontmatter and boundaries
