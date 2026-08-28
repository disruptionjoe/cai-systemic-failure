# Test bridged validation coverage

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, prescribe
a remedy, accept the provisional schema, create follow-on work, or request Joe
action. This is candidate material for Frontier verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-BRIDGED-COVERAGE-01">
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
- Every non-target core gate is supplied as `PASS`. The fixture does not prove
  real-world adequacy, authority exercise, duty, cause, remedy, or outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-BRIDGED-COVERAGE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-BRIDGED-COVERAGE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_bridged_validation_coverage_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Bridged Coverage 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-new-record, no-authority-exercise
   inference, no-duty inference, no-causal inference, no-outcome inference,
   and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-unbridged | events: V-assumption plus V-condition | completed: T-1 | owner_visible: T-1 | bridge: NONE | covers_VB-new: NO | timing_result: PASS | scope_result: FAIL | qualification_result: FAIL`

   `draft: D-bridged | events: V-assumption plus V-condition | completed: T-1 | owner_visible: T-1 | bridge: BR-validation at T-1 | covers_VB-new: YES | timing_result: PASS | scope_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-late-bridge | events: V-assumption plus V-condition | completed: T-1 | owner_visible: T-1 | bridge: BR-validation-late at T1 | covers_VB-new: YES | timing_result: FAIL | scope_result: PASS | qualification_result: FAIL`
6. `## Distinction` stating that event existence, scope coverage, bridge
   evidence, completion time, owner-visibility time, decision time, synthetic
   gate result, real-world adequacy, authority exercise, duty, outcome, and
   remedy remain separate. Do not call `D-unbridged` a timing failure or
   `D-late-bridge` a source-event timing failure; its bridge timing fails.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-unbridged FAIL; D-bridged PASS; D-late-bridge FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — MULTIPLE TIMELY EVENTS
   DO NOT COVER THE DECISION-TIME BURDEN WITHOUT AN ADMITTED TIMELY BRIDGE`.
9. `## Candidate Effect` with exactly `PROPOSE BRIDGED-COVERAGE TEST ONLY — NO
   FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both be
`---`. Stay under 900 words.
