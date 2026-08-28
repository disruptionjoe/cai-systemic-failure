---
test_id: SF-DTCX-DRA-CSC-DUAL-REFUSAL-0001
status: synthetic_crosswalk_dual_refusal_proposal
source_material: synthetic
schema_effect: none
external_action: none
---

# SF Decision-Time DRA CSC Dual Refusal 0001

## Boundary

This is proposal-only, provisional, synthetic, and uncertain. It supports no
remedy, promotion, field change, new record, authority-exercise inference,
duty inference, outcome inference, or action.

## Synthetic Fixture

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

## Control Results

control: SF-TC-0001 | result: PASS | reason: A-old remains operative and is reused at T0 | no_other_effect: owner authority, evidence handling, validation timing, and stop condition remain separate

control: SF-DRA-0001 | result: FAIL | reason: O-late receives relevant authority only at T1 after the T0 decision is final | no_other_effect: reuse, evidence handling, validation timing, and stop condition remain separate

control: SF-ORC-0001 | result: PASS | reason: K-one is displayed, routed, and disputed at T-1 | no_other_effect: reuse, owner authority, validation timing, and stop condition remain separate

control: SF-VBT-0001 | result: PASS | reason: V-pre covers VB-new and is owner-visible at T-1 | no_other_effect: reuse, owner authority, evidence handling, and stop condition remain separate

control: SF-CSC-0001 | result: FAIL | reason: R-capable has no backed condition keeping qualification unresolved while K-one remains unresolved | no_other_effect: reuse, owner authority, evidence handling, and validation timing remain separate

## Candidate Gate Trace

assumption_source_context: PASS — supplied premise

accountable_review_owner: FAIL — relevant authority begins only at T1

affected_system_and_standing: PASS — supplied premise

changed_condition: PASS — supplied premise

validation_burden: PASS — V-pre covers VB-new at T-1

observation_environment: PASS — K-one is displayed, routed, and disputed at T-1

delegation_visibility_gap: PASS — supplied premise

absorber_or_counterevidence: PASS — supplied premise

correction_route_stop_condition: FAIL — no backed stop condition is supplied

Infer no other failed gate.

## Verdict

REFUSE QUALIFICATION — SF-DRA-0001 AND SF-CSC-0001 FAIL INDEPENDENTLY; TC, ORC, AND VBT PASS ONLY AS SUPPLIED SYNTHETIC PREMISES

## Candidate Effect

PROPOSE DRA-CSC DUAL-REFUSAL APPLICATION ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE

## Frontier Verification

- Fixture facts.
- Five control records.
- Nine gate results.
- Verdict/effect coherence.
- Raw frontmatter and hard boundaries.
