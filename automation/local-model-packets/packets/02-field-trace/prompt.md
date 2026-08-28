# Test merged-component validation coverage

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-MERGED-COMPONENT-COVERAGE-01">
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
</synthetic_fixture>

## Work now

Draft `SF-VBT-MERGED-COMPONENT-COVERAGE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-MERGED-COMPONENT-COVERAGE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_merged_component_coverage_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Merged Component Coverage 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-causal inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-separated | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-v1 at T-2 | covers_current: NONE | covers_historical: VC-assumption plus VC-interaction | current_coverage_result: FAIL | qualification_result: FAIL`

   `draft: D-merged | burden: VB-v2 | events: V-composite | bridge: BR-v2 at T-1 | covers_current: VC-composite | covers_historical: NONE | current_coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-label | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-label at T-1 | covers_current: NONE | covers_historical: VC-assumption plus VC-interaction | current_coverage_result: FAIL | qualification_result: FAIL`
6. `## Distinction` stating that historical separate-component membership,
   current composite-component membership, event existence, bridge existence,
   current-component coverage, historical-component coverage, completion
   time, owner-visibility time, decision time, synthetic gate result,
   real-world adequacy, authority exercise, duty, outcome, and remedy remain
   separate. Do not infer that coverage of historical separate components
   proves coverage of the current composite component.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-separated FAIL; D-merged PASS; D-label FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — COVERAGE OF SEPARATE
   HISTORICAL COMPONENTS DOES NOT PROVE COVERAGE OF THE CURRENT NAMED
   COMPOSITE COMPONENT`.
9. `## Candidate Effect` with exactly `PROPOSE MERGED-COMPONENT COVERAGE TEST
   ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 950 words.
