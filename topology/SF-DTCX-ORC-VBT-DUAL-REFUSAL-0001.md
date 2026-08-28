---
test_id: SF-DTCX-ORC-VBT-DUAL-REFUSAL-0001
status: synthetic_crosswalk_dual_refusal_proposal
source_material: synthetic
schema_effect: none
external_action: none
---

# SF Decision-Time ORC VBT Dual Refusal 0001

## Boundary

This artifact is proposal-only, provisional, synthetic, and uncertain. It
contains no remedy, promotion, field change, new record, authority-exercise
inference, duty inference, outcome inference, or action.

## Synthetic Fixture

- Draft `D-late` labels decision `T0` under changed condition `C-new` as reuse
  of `A-old`; admitted evidence shows `A-old` remained operative through `T0`.
- Contradiction `K-late` is displayed at `T-1` but is routed and disputed only
  at `T1`, after the `T0` decision is final.
- Owner `O-window` holds relevant review, stop, escalation, approval or
  rejection, and revision authority from `T-2` through `T+1`.
- Validation burden `VB-new` exists at `T0`. Synthetic validation `V-late`
  completes, becomes owner-visible, and covers `VB-new` only at `T1`, after
  the `T0` decision is final.
- Route `R-capable` can carry `K-late` to `O-window`; synthetic condition
  `C-stop` keeps qualification stopped and unresolved at `T0` while `K-late`
  remains unresolved.
- Every non-target core gate is supplied as `PASS`. The fixture does not say
  authority was exercised, validation was adequate outside supplied scope, a
  duty or remedy exists, or any outcome followed.

## Control Results

- `control: SF-TC-0001 | result: PASS | reason: admitted evidence says A-old remained operative through T0 | no_other_effect: owner authority, evidence handling, validation timing, and stop condition remain separate`
- `control: SF-DRA-0001 | result: PASS | reason: O-window holds relevant authority from T-2 through T+1 | no_other_effect: reuse, evidence handling, validation timing, and stop condition remain separate`
- `control: SF-ORC-0001 | result: FAIL | reason: K-late is routed and disputed only at T1 after the T0 decision is final | no_other_effect: reuse, owner authority, validation timing, and stop condition remain separate`
- `control: SF-VBT-0001 | result: FAIL | reason: V-late covers VB-new and becomes owner-visible only at T1 after the T0 decision is final | no_other_effect: reuse, owner authority, evidence handling, and stop condition remain separate`
- `control: SF-CSC-0001 | result: PASS | reason: C-stop keeps qualification unresolved at T0 while K-late remains unresolved | no_other_effect: reuse, owner authority, evidence handling, and validation timing remain separate`

## Candidate Gate Trace

- `assumption_source_context: PASS — A-old remains operative through T0`
- `accountable_review_owner: PASS — supplied premise`
- `affected_system_and_standing: PASS — supplied premise`
- `changed_condition: PASS — supplied premise`
- `validation_burden: FAIL — V-late completes and becomes owner-visible only at T1`
- `observation_environment: FAIL — K-late is routed and disputed only at T1`
- `delegation_visibility_gap: PASS — supplied premise`
- `absorber_or_counterevidence: PASS — supplied premise`
- `correction_route_stop_condition: PASS — supplied premise`

Infer no other failed gate.

## Verdict

REFUSE QUALIFICATION — SF-ORC-0001 AND SF-VBT-0001 FAIL INDEPENDENTLY; TC,
DRA, AND CSC PASS ONLY AS SUPPLIED SYNTHETIC PREMISES

## Candidate Effect

PROPOSE ORC-VBT DUAL-REFUSAL APPLICATION ONLY — NO FIELD, RECORD, STATUS,
ACCEPTANCE, OR REMEDY CHANGE

## Frontier Verification

- fixture facts
- five control records
- nine gate results
- verdict/effect coherence
- raw frontmatter and hard boundaries
