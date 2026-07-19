---
schema_id: SF-SCHEMA-CANDIDATE-0001
status: provisional_schema_candidate
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-07-18
source_material: public_official_records_and_prior_topology_tests
external_action: none
---

# SF Schema Candidate 0001 - Review-Chain Fields

## Boundary

This is a provisional review-chain field schema candidate for source-backed
failure records. It implements the acceptance gate from
`SF-SCHEMA-READINESS-0001-review-chain-fields.md`.

It is not an accepted topology schema, universal systemic-failure ontology,
domain remedy, public-health recommendation, engineering recommendation,
legal or civil-rights finding, CAI doctrine, intervention plan, or proving
authority. It is a candidate structure to be falsified, narrowed, or revised
by a fourth source-backed record or negative absorber.

## Record Qualification Gate

A record may use this candidate only when all gate conditions are met:

1. source material is public, licensed, safely shareable, or synthetic;
2. the record names the source context and keeps correction routes open;
3. an old assumption is reused under a changed condition or changed evidence
   context;
4. the changed condition creates a validation burden that sources show as
   unmet, disputed, fragmented, or not owner-visible enough;
5. affected system or affected-party standing remains explicit;
6. delegation, review, or request paths are material to the contradiction; and
7. at least one narrower absorber or countermodel is recorded.

If these conditions are not met, the case may still be useful evidence, but it
does not qualify as positive evidence for this candidate.

## Candidate Fields

| Field | Required content | Refusal condition |
|---|---|---|
| `assumption_source_context` | Name the reused assumption and the source, report, decision context, revision, or evidence basis supporting the synthesis. | Refuse if the record only says a system failed without tying the assumption to source context. |
| `accountable_review_owner` | Distinguish the assumption owner from the owner who could review, stop, escalate, or revise its reuse. | Refuse if accountability is only a generic organization label. |
| `affected_system_and_standing` | Name the affected system and the affected-party standing visible in the sources, including people when sources make them central. | Refuse if affected parties disappear behind process language. |
| `changed_condition` | Identify the changed function, observed anomaly, source switch, evidence context, operating condition, or other change that alters the validation burden. | Refuse if the old assumption is reused under materially unchanged conditions. |
| `validation_burden` | State what adequate revalidation would need to address and what source-backed evidence shows as unmet, disputed, fragmented, or unresolved. | Refuse if the record supplies no source-backed burden beyond hindsight. |
| `observation_environment` | Preserve how the relevant evidence was made visible, missed, normalized, routed, or disputed without importing domain conclusions. | Refuse if the field becomes a domain-specific remedy or expertise claim. |
| `delegation_visibility_gap` | Show how distributed review, authority, request paths, or delegated decisions fragmented the contradiction. | Refuse if no review-chain fragmentation is source-supported. |
| `absorber_or_counterevidence` | Record the strongest narrower explanation and whether it absorbs, narrows, or fails to kill the review-chain residue. | Refuse if the candidate treats every case as confirming evidence. |
| `correction_route_stop_condition` | Name the owner-visible route that could correct, escalate, stop, revise, or expose the assumption without this repo prescribing the remedy. | Refuse if correction requires this repository to act as the domain owner. |

## Source-Gated Annotations

These annotations may be recorded when source material supports them, but they
are not mandatory fields in this candidate:

- `hazard_history`: prior tolerated anomalies, incidents, or infrastructure
  conditions that made later evidence appear normal;
- `observation_request_path`: complaints, measurements, imagery requests,
  inspections, external evidence, or other requests that failed to become an
  accountable contradiction;
- `jurisdictional_authority_gap`: formal authority boundaries that delayed,
  weakened, or blocked a stop condition despite visible risk.
- `resident_warning_route`: resident, tenant, local-community, or affected-
  party warnings that public sources show as possible review, escalation, stop,
  or correction routes.

Annotations must not let a record qualify without the core source, assumption,
changed-condition, validation-burden, absorber, and correction-route gates.

## Refusal Notes

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public source material centers deliberate
control bypass, test circumvention, false reporting, or similar adversarial
compliance behavior rather than source-backed assumption reuse under changed
conditions.

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public source material centers domain-code
application, fire/life-safety protection, material flammability, suppression,
pyrotechnic, evacuation, inspection, emergency-response, or similar domain-
specific remedy paths rather than source-backed assumption reuse under changed
conditions.

Record a case as a lead, inquiry, absorber, or separate topology question, not
positive evidence for this candidate, when the pattern match is source-thin,
media-only, retrospective, or dependent on hindsight reconstruction rather than
durable source material that can carry the assumption context, changed
condition, validation burden, review owner, and correction route.

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public official sources center false
alerting, public warning, communication, correction-message delay, drill
procedure, alert origination, or alert-system safeguards rather than
source-backed assumption reuse under changed conditions.

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public official sources center single-operator
or crew execution, situational awareness, task management, speed compliance,
protective-control absence or enforcement, or similar point-of-operation
performance rather than source-backed assumption reuse under changed
conditions.

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public official sources center structural
capacity, original design calculation, load rating, inspection guidance,
maintenance drift, construction-load placement, or similar infrastructure-
capacity controls rather than source-backed assumption reuse under changed
conditions.

These refusal notes are source-gated and do not authorize legal, regulatory,
environmental, health, enforcement, automotive, compliance, building-code,
fire-safety, emergency-response, public-safety, warning, communication,
alerting-system, rail-safety, train-control, transportation-safety, bridge-
safety, structural-engineering, transportation-infrastructure, inspection,
maintenance, construction-load, or domain-remedy conclusions.

## Non-Promotion Rules

This candidate cannot be used to:

- infer a universal topology from three records;
- convert domain remedies into topology fields;
- issue engineering, public-health, civil-rights, legal, regulatory, or policy
  recommendations;
- treat affected owners as participants or research subjects;
- use nonpublic, restricted, confidential, or field-collected evidence;
- create an external action, relationship obligation, membership obligation,
  intervention pathway, or CAI phase movement; or
- move another repository's claims, canon, or work state.

## Current Fit

| Record | Fit | Absorber result |
|---|---|---|
| `SF-0001` | Fits as a certification and safety-assessment assumption reuse record under changed flight-control, input, and alert/workload conditions. | Ordinary training or checklist deficit narrows but does not absorb the review-chain residue. |
| `SF-0002` | Fits as a hazard-acceptability and damage-assessment sufficiency record under live-mission anomaly conditions. | Domain-specific spaceflight remedy narrows but does not absorb owner-visible uncertainty and escalation failure. |
| `SF-0003` | Fits as a changed-source corrosion-control and exposure-risk review-chain record under public official evidence. | Drinking-water, public-health, legal, and civil-rights remedy domains narrow but do not absorb validation burden, affected-person standing, and correction route. |
| `SF-0004` | Fits as a negative-pressure-test and barrier-assumption review-chain record under public official evidence. | Offshore energy, process-safety, emergency, environmental, and legal domains narrow but do not absorb source-backed validation burden and correction route. |
| `SF-ABS-0002` | Refused as positive fit. The Volkswagen defeat-device source set is a control-bypass and false-reporting absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can reject a systemic-failure case instead of overgeneralizing. |
| `SF-CRT-0001` | Refused as positive fit. The synthetic stress fixture has apparent assumption reuse under changed conditions but lacks an owner-visible correction route. | The stress test preserves correction-route discipline; assumption reuse alone cannot qualify the candidate. |
| `SF-0005` | Fits as a refurbishment, external-wall, fire-safety, and resident-warning review-chain record under public official evidence. | Building-safety, product, fire-service, resident-engagement, regulatory, and legal domains narrow but do not absorb source-backed validation burden and correction route. |
| `SF-ABS-0003` | Refused as positive fit. The NIST Station nightclub source set is a fire/life-safety code, material, sprinkler, pyrotechnic, egress, inspection, and emergency-response protection absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can accept one building/fire-safety review-chain record without claiming every public fire-safety failure. |
| `SF-SQA-0001` | Refused as positive fit. Source-thin or hindsight-built pattern matches cannot qualify without source-backed assumption context, changed condition, validation burden, review owner, and correction route. | Source-quality failure absorbs attractive narratives before they stretch the candidate into a retrospective pattern label. |
| `SF-ABS-0004` | Refused as positive fit. The Hawaii false-alert source set is a warning/communication, drill-procedure, alert-origination, safeguard, and correction-message absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve warning-route pressure without claiming every public alerting or communication failure. |
| `SF-ABS-0005` | Refused as positive fit. The Amtrak Train 188 source set is a single-owner execution, situational-awareness, speed-compliance, train-control, occupant-protection, and emergency-response absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve affected standing and correction-route visibility without claiming every point-of-operation execution failure. |
| `SF-ABS-0006` | Refused as positive fit. The I-35W bridge-collapse source set is a slow-degradation, infrastructure-capacity, original-design-calculation, added-load, load-rating, construction-load, and inspection-guidance absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve long-lived defect and changed-load pressure without claiming every infrastructure-capacity failure. |

## Next Falsifier

Do not accept this schema yet.
`SF-SCHEMA-DISPOSITION-0002-two-absorber-post-disposition.md` compares
`SF-ABS-0002` and `SF-ABS-0003`, keeps the candidate provisional, and refuses
schema acceptance.

`SF-SCHEMA-ACCEPTANCE-BAR-0001-review-chain-fields.md` completed a
non-accepting acceptance-bar review. It names future promotion prerequisites,
remaining false-positive and false-negative classes, counterevidence that would
kill or demote the candidate, and the proper acceptance authority.

The next useful test is one remaining falsifier class, preferably a
non-synthetic false-positive class or a false-negative pressure test. The
candidate remains provisional until those unresolved classes are tested,
explicitly deferred with reasons, or routed to the proper owner.

`SF-SQA-0001-source-quality-falsifier.md` tests one remaining class by refusing
source-quality and hindsight-artifact fits.
`SF-ABS-0004-warning-communication-false-alert.md` tests another by refusing a
non-synthetic warning/communication false-positive case. The next useful test
`SF-ABS-0005-single-owner-execution-train-188.md` tests another by refusing a
non-synthetic single-owner execution and protective-control false-positive
case.
`SF-ABS-0006-slow-degradation-bridge-collapse.md` tests another by refusing a
non-synthetic slow-degradation and infrastructure-capacity false-positive case.
The next useful test should come from a different remaining class, preferably
resource scarcity or capacity tradeoff, newly formed assumption, a borderline
mixed case, or a false-negative pressure test.
