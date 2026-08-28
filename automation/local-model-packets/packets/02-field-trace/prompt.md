# Test revised multi-component validation coverage

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-REVISED-MULTI-COMPONENT-BRIDGE-01">
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
- Every non-target core gate is supplied as `PASS`. All supplied events and
  bridges are timely. The fixture does not prove real-world adequacy, authority
  exercise, duty, cause, remedy, or outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-REVISED-MULTI-COMPONENT-BRIDGE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-REVISED-MULTI-COMPONENT-BRIDGE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_revised_multi_component_bridge_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Revised Multi-Component Bridge 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-causal inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-stale | burden: VB-v2 | events: V-assumption plus V-interaction | bridge: BR-v1 at T-2 | covers: VC-assumption plus VC-interaction | missing: VC-environment | coverage_result: FAIL | qualification_result: FAIL`

   `draft: D-revised | burden: VB-v2 | events: V-assumption plus V-interaction plus V-environment | bridge: BR-v2 at T-1 | covers: VC-assumption plus VC-interaction plus VC-environment | missing: NONE | coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-generic | burden: VB-v2 | events: V-assumption plus V-interaction plus V-environment | bridge: BR-generic at T-1 | covers: NO NAMED COMPONENT | missing: ALL NAMED COVERAGE | coverage_result: FAIL | qualification_result: FAIL`
6. `## Distinction` stating that burden revision, event existence, bridge
   existence, named components, component coverage, completion time,
   owner-visibility time, decision time, synthetic gate result, real-world
   adequacy, authority exercise, duty, outcome, and remedy remain separate.
   Do not call any draft a timing failure.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-stale FAIL; D-revised PASS; D-generic FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — A TIMELY BRIDGE MUST
   COVER EVERY NAMED COMPONENT OF THE CURRENT DECISION-TIME VALIDATION BURDEN`.
9. `## Candidate Effect` with exactly `PROPOSE REVISED MULTI-COMPONENT BRIDGE
   TEST ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 950 words.
