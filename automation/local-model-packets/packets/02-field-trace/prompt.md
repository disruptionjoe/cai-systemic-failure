# Test multi-component validation-bridge coverage

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-MULTI-COMPONENT-BRIDGE-01">
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
- Every non-target core gate is supplied as `PASS`. The fixture does not prove
  real-world adequacy, authority exercise, duty, cause, remedy, or outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-MULTI-COMPONENT-BRIDGE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-MULTI-COMPONENT-BRIDGE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_multi_component_bridge_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Multi-Component Bridge 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-causal inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-partial | events: V-assumption plus V-interaction | completed: T-1 | owner_visible: T-1 | bridge: BR-partial at T-1 | covers: VC-assumption only | coverage_result: FAIL | qualification_result: FAIL`

   `draft: D-complete | events: V-assumption plus V-interaction | completed: T-1 | owner_visible: T-1 | bridge: BR-complete at T-1 | covers: VC-assumption plus VC-interaction | coverage_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-generic | events: V-assumption plus V-interaction | completed: T-1 | owner_visible: T-1 | bridge: BR-generic at T-1 | covers: NO NAMED COMPONENT | coverage_result: FAIL | qualification_result: FAIL`
6. `## Distinction` stating that event existence, bridge existence, named
   burden components, component coverage, completion time, owner-visibility
   time, decision time, synthetic gate result, real-world adequacy, authority
   exercise, duty, outcome, and remedy remain separate. Do not call any draft
   a timing failure; all supplied events and bridges are timely.
7. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: D-partial FAIL; D-complete PASS; D-generic FAIL`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `TEST FOR NEW PRESSURE — A TIMELY BRIDGE MUST
   COVER EVERY NAMED COMPONENT OF THE DECISION-TIME VALIDATION BURDEN`.
9. `## Candidate Effect` with exactly `PROPOSE MULTI-COMPONENT BRIDGE TEST ONLY
   — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 900 words.
