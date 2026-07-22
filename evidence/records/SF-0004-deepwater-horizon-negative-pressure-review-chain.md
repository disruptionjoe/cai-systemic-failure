---
record_id: SF-0004
status: source_backed_synthesis
claim_status: investigation_synthesis
lane: "1"
created: 2026-07-18
source_material: public_official_reports
external_action: none
---

# SF-0004 - Deepwater Horizon Negative-Pressure-Test Review Chain

## Boundary

This record is a bounded public-source synthesis of the Deepwater Horizon /
Macondo well blowout. It tests `SF-SCHEMA-CANDIDATE-0001` in an offshore
energy and process-safety context. It is not an offshore-drilling engineering
finding, regulatory finding, environmental-damage assessment, legal claim,
operator judgment, public recommendation, or intervention plan.

No confidential material, human subjects, field work, account access, external
contact, or deployment was used.

## Source Set

- National Commission on the BP Deepwater Horizon Oil Spill and Offshore
  Drilling, "Deep Water: The Gulf Oil Disaster and the Future of Offshore
  Drilling", January 2011, hosted by GovInfo:
  https://www.govinfo.gov/content/pkg/GPO-OILCOMMISSION/pdf/GPO-OILCOMMISSION.pdf
- Bureau of Safety and Environmental Enforcement / U.S. Coast Guard Joint
  Investigation Team final report release page:
  https://www.bsee.gov/site-page/deepwater-horizon-joint-investigation-team-releases-final-report
- U.S. Chemical Safety and Hazard Investigation Board, "Macondo Investigation
  Report Volume 1", June 5, 2014:
  https://www.csb.gov/assets/1/7/vol_1_final.pdf
- U.S. Chemical Safety and Hazard Investigation Board, "Macondo Investigation
  Report Volume 2", June 5, 2014:
  https://www.csb.gov/assets/1/7/vol_2_final_version.pdf

Source posture: public government or official investigation material. The
repository stores pointers and synthesis only; it does not copy the source
artifacts.

## Pattern Summary

The bounded pattern is not "offshore drilling fails" or "one technical remedy
would have prevented the disaster." The useful topology question is how a
temporary-abandonment and well-integrity validation step could produce
contradictory pressure, flow, barrier, and interpretation evidence without
forcing one accountable stop condition before the old assumption of adequate
well integrity was accepted.

For this repository, the record is narrow:

- the negative-pressure-test context changed the validation burden because the
  well was being placed into a condition meant to verify barriers under
  underbalanced pressure;
- source-reported test anomalies, pressure readings, bleed volumes, procedure
  design, and interpretation disagreements needed to remain one contradiction
  object rather than separate operational facts;
- the relevant review path crossed operator, rig, contractor, procedure,
  real-time decision, and regulator-facing evidence boundaries;
- affected-party standing is central because rig workers, response personnel,
  Gulf communities, and the marine environment carried risk while technical
  and operational owners interpreted the test and barriers.

## Candidate Field Fit

| Candidate field from `SF-SCHEMA-CANDIDATE-0001` | SF-0004 result |
|---|---|
| `assumption_source_context` | Fits. The reused assumption is that the well barriers and temporary-abandonment posture were adequately verified by the negative pressure test and related operational checks. |
| `accountable_review_owner` | Fits but must remain multi-owner. The record needs to distinguish assumption ownership, rig-site interpretation, contractor inputs, and regulator-facing accountability without collapsing them into one generic organization label. |
| `affected_system_and_standing` | Fits and broadens. The affected system includes the rig, well, response environment, workers, nearby communities, and environmental receivers named in public source materials. |
| `changed_condition` | Fits. Temporary abandonment and underbalanced negative-pressure-test conditions changed the validation burden for old barrier assumptions. |
| `validation_burden` | Fits. Conflicting pressure and flow evidence, test setup, acceptance criteria, and unresolved interpretation needed source-backed resolution before the old assumption could stand. |
| `observation_environment` | Fits. Evidence appeared through real-time instrumentation, procedure execution, crew/operator interpretation, and post-incident investigation; the field must not become a drilling-remedy claim. |
| `delegation_visibility_gap` | Fits. Distributed operational, contractor, procedural, and oversight roles could fragment who held the contradiction and who could force a stop condition. |
| `absorber_or_counterevidence` | Fits as a control. Well design, cementing, blowout-preventer, and emergency-response explanations narrow the case but do not absorb the pre-blowout review-chain residue. |
| `correction_route_stop_condition` | Fits. The route is an owner-visible requirement to stop, retest, escalate, or revise the barrier assumption when the validation evidence remains contradictory, without this repository prescribing the domain remedy. |

## New Field Pressure

`SF-0004` adds one pressure to keep source-gated rather than mandatory:

- `procedural_acceptance_criteria_gap`: whether a source record shows missing,
  disputed, or inadequate criteria for accepting a validation test before a
  consequential operation continues.

This pressure belongs under `validation_burden`, `observation_environment`, or
`delegation_visibility_gap` unless another record forces it to separate. It
does not let this repository write offshore-drilling procedure or regulation.

## Counterevidence And Absorbers

The strongest absorbers are domain-specific:

- the blowout is a well-design, cementing, drilling-operation, or process-
  safety case whose remedies belong to offshore energy authorities and domain
  experts;
- the blowout preventer and emergency systems are enough to explain the event;
- the event should be modeled as individual or local operational error rather
  than a reusable review-chain problem.

Those absorbers are partly right and narrow this repository's claims. They do
not absorb the candidate because this record uses them only as controls around
the source-backed contradiction: a changed validation condition, unresolved
evidence, distributed review, affected standing, and a possible owner-visible
stop route before old assumptions were reused.

## Uncertainty And Falsifiers

This synthesis may compress distinct well-design, test-procedure, rig-site,
contractor, operator, and oversight decisions into one review-chain pattern. It
does not reconstruct individual intent or decide among technical causal models.

Falsify or narrow the record if closer source review shows that the conflicting
test evidence and barrier assumption were already preserved as one accountable
stop condition, or that the proposed pattern depends on an offshore-engineering
conclusion rather than the bounded review-chain evidence.

## Owner Routing

Any offshore-drilling engineering, well-control, environmental, regulatory,
legal, operational, labor-safety, or damages conclusion belongs to the relevant
domain authorities, affected communities, and public official records, not this
repository. This repository may preserve the source-backed review-chain test
and use it to narrow or falsify provisional topology fields.

## Correction Route

If later source review shows this synthesis overstates the official record,
correct this file and any dependent topology test. Do not silently promote the
field set into an accepted schema, universal ontology, policy prescription, or
domain remedy.
