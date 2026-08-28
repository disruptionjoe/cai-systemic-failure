# Test split-component validation coverage

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-SPLIT-COMPONENT-COVERAGE-01">
- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- At `T-2`, validation burden `VB-v1` has one named component `VC-control`.
  Validation event `V-control` completes and becomes owner-visible at `T-2`;
  timely bridge `BR-v1` explicitly covers `VC-control`.
- At `T-1`, admitted burden revision `VB-v2` replaces `VC-control` with two
  current named components: `VC-assumption` and `VC-interaction`.
- `D-parent` cites only `V-control` and `BR-v1`; neither names either current
  `VB-v2` component.
- `D-split` cites timely events `V-assumption` and `V-interaction` plus timely
  bridge `BR-v2`, which explicitly covers both current components.
- `D-partial` cites timely event `V-assumption` and bridge `BR-partial`, which
  explicitly covers `VC-assumption` but not `VC-interaction`.
- Every non-target core gate is supplied as `PASS`. All supplied events,
  bridges, and the burden revision are timely and owner-visible. The fixture
  does not prove real-world adequacy, authority exercise, duty, cause, remedy,
  or outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-SPLIT-COMPONENT-COVERAGE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-SPLIT-COMPONENT-COVERAGE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_split_component_coverage_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Split Component Coverage 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-causal inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-parent | burden: VB-v2 | events: V-control | bridge: BR-v1 at T-2 | covers_current: NONE | covers_historical: VC-control | current_coverage_result: FAIL | qualification_result: FAIL`

   `draft: D-split | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-v2 at T-1 | covers_current: VC-assumption plus VC-interaction | covers_historical: NONE | current_coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-partial | burden: VB-v2 | events: V-assumption | bridge: BR-partial at T-1 | covers_current: VC-assumption | covers_historical: NONE | current_coverage_result: FAIL | qualification_result: FAIL`
6. `## Distinction` stating that historical parent-component membership,
   current child-component membership, event existence, bridge existence,
   current-component coverage, historical-component coverage, completion
   time, owner-visibility time, decision time, synthetic gate result,
   real-world adequacy, authority exercise, duty, outcome, and remedy remain
   separate. Do not infer that historical parent-component coverage proves
   coverage of either current child component.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-parent FAIL; D-split PASS; D-partial FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — COVERAGE OF A
   PRE-REVISION PARENT COMPONENT DOES NOT PROVE COVERAGE OF THE CURRENT NAMED
   CHILD COMPONENTS`.
9. `## Candidate Effect` with exactly `PROPOSE SPLIT-COMPONENT COVERAGE TEST
   ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 950 words.
