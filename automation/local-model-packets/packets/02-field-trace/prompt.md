# Test same-label validation-scope revision

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-SAME-LABEL-SCOPE-REVISION-01">
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
</synthetic_fixture>

## Work now

Draft `SF-VBT-SAME-LABEL-SCOPE-REVISION-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-SAME-LABEL-SCOPE-REVISION-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_same_label_scope_revision_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Same Label Scope Revision 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-causal inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-history | burden: VB-v2 | component: VC-context | event: V-history | bridge: BR-v1 at T-2 | covered_scope: continued operation of A-old | current_required_scope: relation between A-old and C-new | current_scope_coverage: FAIL | qualification_result: FAIL`

   `draft: D-current | burden: VB-v2 | component: VC-context | event: V-relation | bridge: BR-v2 at T-1 | covered_scope: relation between A-old and C-new | current_required_scope: relation between A-old and C-new | current_scope_coverage: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-label | burden: VB-v2 | component: VC-context | event: V-history | bridge: BR-label at T-1 | covered_scope: component label only | current_required_scope: relation between A-old and C-new | current_scope_coverage: FAIL | qualification_result: FAIL`
6. `## Distinction` stating that component-label identity, historical scope,
   current required scope, event existence, bridge existence, current-scope
   coverage, historical-scope coverage, completion time, owner-visibility time,
   decision time, synthetic gate result, real-world adequacy, authority
   exercise, duty, outcome, and remedy remain separate. Do not infer that an
   unchanged component label preserves its earlier validation scope.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-history FAIL; D-current PASS; D-label FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — AN UNCHANGED COMPONENT
   LABEL DOES NOT PROVE COVERAGE OF ITS CURRENT REVISED SCOPE`.
9. `## Candidate Effect` with exactly `PROPOSE SAME-LABEL SCOPE-REVISION TEST
   ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 950 words.
