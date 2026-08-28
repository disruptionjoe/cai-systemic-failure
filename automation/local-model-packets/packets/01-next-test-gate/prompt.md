# Test independent review-authority and route-stop refusals

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-DECISION-CONTROL-CROSSWALK-01`.

## Evidence

<synthetic_fixture id="DTCX-DRA-CSC-DUAL-REFUSAL-01">
- Draft `D-split` labels decision `T0` under changed condition `C-new` as
  reuse of `A-old`.
- The admitted sequence shows `A-old` remains operative and is reused at `T0`.
- Contradiction `K-one` is displayed, routed, and disputed at `T-1`.
- `O-late` receives relevant review, stop, escalation, approval or rejection,
  and revision authority only at `T1`, after the `T0` decision is final. No
  source- or synthetic-backed decision-time review authority is supplied.
- Validation burden `VB-new` exists at `T0`. Synthetic validation `V-pre`
  completes, is owner-visible, and covers `VB-new` at `T-1`.
- Route `R-capable` can carry `K-one` to capable recipient `O-route`, but the
  fixture supplies no source- or synthetic-backed condition keeping
  qualification stopped or unresolved while `K-one` remains unresolved.
- Every non-target core gate is supplied as `PASS`. The fixture does not say
  authority was exercised, validation was adequate outside supplied scope, a
  duty or remedy exists, or any outcome followed.
</synthetic_fixture>

## Work now

Draft `SF-DTCX-DRA-CSC-DUAL-REFUSAL-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-DTCX-DRA-CSC-DUAL-REFUSAL-0001`,
   `status: synthetic_crosswalk_dual_refusal_proposal`,
   `source_material: synthetic`, `schema_effect: none`, and
   `external_action: none`.
2. `# SF Decision-Time DRA CSC Dual Refusal 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-outcome inference,
   and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Control Results` copying exactly these five records, once each:

   `control: SF-TC-0001 | result: PASS | reason: A-old remains operative and is reused at T0 | no_other_effect: owner authority, evidence handling, validation timing, and stop condition remain separate`

   `control: SF-DRA-0001 | result: FAIL | reason: O-late receives relevant authority only at T1 after the T0 decision is final | no_other_effect: reuse, evidence handling, validation timing, and stop condition remain separate`

   `control: SF-ORC-0001 | result: PASS | reason: K-one is displayed, routed, and disputed at T-1 | no_other_effect: reuse, owner authority, validation timing, and stop condition remain separate`

   `control: SF-VBT-0001 | result: PASS | reason: V-pre covers VB-new and is owner-visible at T-1 | no_other_effect: reuse, owner authority, evidence handling, and stop condition remain separate`

   `control: SF-CSC-0001 | result: FAIL | reason: R-capable has no backed condition keeping qualification unresolved while K-one remains unresolved | no_other_effect: reuse, owner authority, evidence handling, and validation timing remain separate`
6. `## Candidate Gate Trace` copying these nine records exactly:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: FAIL — relevant authority begins only at T1`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — V-pre covers VB-new at T-1`

   `observation_environment: PASS — K-one is displayed, routed, and disputed at T-1`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: FAIL — no backed stop condition is supplied`

   End with literal `Infer no other failed gate.`
7. `## Verdict` with exactly `REFUSE QUALIFICATION — SF-DRA-0001 AND
   SF-CSC-0001 FAIL INDEPENDENTLY; TC, ORC, AND VBT PASS ONLY AS SUPPLIED
   SYNTHETIC PREMISES`.
8. `## Candidate Effect` with exactly `PROPOSE DRA-CSC DUAL-REFUSAL
   APPLICATION ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
9. `## Frontier Verification` with exactly five bullets: fixture facts; five
   control records; nine gate results; verdict/effect coherence; raw
   frontmatter and hard boundaries.

Begin the raw artifact now. Return only the finished artifact. Do not use a
code fence. The first line and the line after `external_action: none` must both
be `---`. Copy the five verification bullets once and end. Stay under 850 words.
