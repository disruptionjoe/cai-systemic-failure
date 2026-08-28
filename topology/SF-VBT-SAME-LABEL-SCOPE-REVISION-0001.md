---
test_id: SF-VBT-SAME-LABEL-SCOPE-REVISION-0001
candidate: SF-SCHEMA-CANDIDATE-0001
status: synthetic_same_label_scope_revision_proposal
source_material: synthetic
external_action: none
---

# SF VBT Same Label Scope Revision 0001

## Boundary

This artifact is proposal-only, provisional, synthetic, and uncertain. It
contains no remedy, promotion, field change, new record, authority-exercise
inference, duty inference, causal inference, outcome inference, or action.

## Synthetic Fixture

- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- At `T-2`, validation burden `VB-v1` has current component `VC-context`, whose
  admitted scope is only the continued operation of `A-old`. Timely event
  `V-history` and bridge `BR-v1` explicitly cover that historical scope.
- At `T-1`, admitted burden revision `VB-v2` retains the label `VC-context`
  but changes its current required scope to the relation between `A-old` and
  changed condition `C-new`.
- `D-history` cites only `V-history` and `BR-v1`; neither covers the current
  relation scope even though the component label is unchanged.
- `D-current` cites timely event `V-relation` and bridge `BR-v2`, which
  explicitly cover the current `A-old` and `C-new` relation scope.
- `D-label` cites `V-history` plus `BR-label`, which repeats label `VC-context`
  but does not identify or cover the current relation scope.
- Every non-target core gate is supplied as `PASS`. All supplied events,
  bridges, and the burden revision are timely and owner-visible. The fixture
  does not prove real-world adequacy, authority exercise, duty, cause, remedy,
  or outcome.

## Validation Ledger

- `draft: D-history | burden: VB-v2 | component: VC-context | event: V-history | bridge: BR-v1 at T-2 | covered_scope: continued operation of A-old | current_required_scope: relation between A-old and C-new | current_scope_coverage: FAIL | qualification_result: FAIL`
- `draft: D-current | burden: VB-v2 | component: VC-context | event: V-relation | bridge: BR-v2 at T-1 | covered_scope: relation between A-old and C-new | current_required_scope: relation between A-old and C-new | current_scope_coverage: PASS | qualification_result: CONTINUE GATE CHECKS`
- `draft: D-label | burden: VB-v2 | component: VC-context | event: V-history | bridge: BR-label at T-1 | covered_scope: component label only | current_required_scope: relation between A-old and C-new | current_scope_coverage: FAIL | qualification_result: FAIL`

## Distinction

Component-label identity, historical scope, current required scope, event
existence, bridge existence, current-scope coverage, historical-scope coverage,
completion time, owner-visibility time, decision time, synthetic gate result,
real-world adequacy, authority exercise, duty, outcome, and remedy remain
separate. An unchanged component label does not preserve its earlier validation
scope.

## Candidate Gate Trace

- `assumption_source_context: PASS — supplied premise`
- `accountable_review_owner: PASS — supplied premise`
- `affected_system_and_standing: PASS — supplied premise`
- `changed_condition: PASS — supplied premise`
- `validation_burden: D-history FAIL; D-current PASS; D-label FAIL`
- `observation_environment: PASS — supplied premise`
- `delegation_visibility_gap: PASS — supplied premise`
- `absorber_or_counterevidence: PASS — supplied premise`
- `correction_route_stop_condition: PASS — supplied premise`

Infer no other failed gate.

## Verdict

TEST FOR NEW PRESSURE — AN UNCHANGED COMPONENT LABEL DOES NOT PROVE COVERAGE OF
ITS CURRENT REVISED SCOPE

## Candidate Effect

PROPOSE SAME-LABEL SCOPE-REVISION TEST ONLY — NO FIELD, RECORD, STATUS,
ACCEPTANCE, OR REMEDY CHANGE

## Frontier Verification

- fixture facts
- three ledger records
- nine gate results
- verdict/effect coherence
- raw frontmatter and boundaries
