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
2. the record names the source context and relied-on revision, preserves any
   known materially superseding or contradicting revision in the admitted
   source packet, preserves and grades any direct material contradiction within
   that packet that bears on a required field, and keeps correction routes
   open;
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
| `assumption_source_context` | Name the reused assumption and the source, report, decision context, revision, version, date, or evidence basis relied on for the synthesis. Where multiple fragments or times support a record, name the admitted source-backed bridge connecting the qualifying assumption, changed condition, standing, and review path to one bounded system or review chain, including evidence that the assumption remained active or was reused during the changed condition. Preserve and disposition any known later revision, retirement or replacement event, or direct material contradiction in the admitted source packet that supersedes, narrows, withdraws, or conflicts with that support. | Refuse if the record only says a system failed without tying the assumption to source context, combines unrelated source fragments or disjoint times without an admitted evidentiary bridge, knowingly selects an earlier supporting revision while omitting a later material contradiction, treats same-system chronology as proof that a retired assumption remained active, or labels a directly contradicted required field passed without grading the conflict. |
| `accountable_review_owner` | Distinguish the assumption owner from the owner who could review, stop, escalate, or revise its reuse. | Refuse if accountability is only a generic organization label. |
| `affected_system_and_standing` | Name the bounded affected system and the affected-party standing visible in the sources, including people when sources make them central; when assembled from multiple fragments, preserve the admitted bridge that connects their standing to that system. | Refuse if affected parties disappear behind process language or the record borrows standing from an unrelated system without a source-backed bridge. |
| `changed_condition` | Identify the changed function, observed anomaly, source switch, evidence context, operating condition, or other change that alters the validation burden. | Refuse if the old assumption is reused under materially unchanged conditions. |
| `validation_burden` | State what adequate revalidation would need to address and what source-backed evidence shows as unmet, disputed, fragmented, or unresolved. | Refuse if the record supplies no source-backed burden beyond hindsight. |
| `observation_environment` | Preserve how the relevant evidence was made visible, missed, normalized, routed, or disputed without importing domain conclusions. | Refuse if the field becomes a domain-specific remedy or expertise claim. |
| `delegation_visibility_gap` | Show how distributed review, authority, request paths, or delegated decisions fragmented the contradiction. | Refuse if no review-chain fragmentation is source-supported. |
| `absorber_or_counterevidence` | Record the strongest narrower explanation, its source context or explicit synthetic basis, its claim posture, whether it absorbs, narrows, or fails to kill the review-chain residue, and any direct material contradiction in the admitted packet bearing on a required field. | Refuse if the candidate treats every case as confirming evidence, names only generic, untraceable, or ungraded alternatives, or leaves an admitted direct material contradiction undispositioned. |
| `correction_route_stop_condition` | Name the owner-visible route and the admitted source or explicit synthetic basis showing how it can receive or surface the relevant contradiction to a party able to correct, escalate, stop, revise, or expose the assumption, without this repo prescribing the remedy. | Refuse if correction requires this repository to act as the domain owner, or if a named route is only a label or is shown unable to carry the relevant correction. |

## Source-Gated Annotations

These annotations may be recorded when source material supports them, but they
are not mandatory fields in this candidate:

- `hazard_history`: prior tolerated anomalies, incidents, or infrastructure
  conditions that made later evidence appear normal;
- `observation_request_path`: complaints, measurements, imagery requests,
  inspections, external evidence, or other requests that failed to become an
  accountable contradiction;
- `jurisdictional_authority_gap`: formal authority boundaries that delayed,
  weakened, or blocked a stop condition despite visible risk;
- `procedural_acceptance_criteria_gap`: missing, disputed, or inadequate
  source-backed criteria for accepting a validation test before a
  consequential operation continues;
- `resident_warning_route`: resident, tenant, local-community, or affected-
  party warnings that public sources show as possible review, escalation, stop,
  or correction routes.
- `design_basis_reassessment_path`: formal backchecks, reassessments, stress
  tests, design-basis reviews, licensing-basis updates, or external-hazard
  review paths that public sources show as pending, incomplete, nonbinding,
  fragmented, or not owner-visible enough.
- `technical_dissent_escalation_path`: source-backed technical objections,
  no-go recommendations, launch or operating constraints, waiver or constraint
  review, management reversal or containment, and whether unresolved dissent
  reached accountable decision owners.

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

Refuse positive qualification when the named absorber or counterevidence is
only a generic alternative with no traceable source context or explicit
synthetic basis and no claim posture. Preserve source-thin, contradicted,
synthetic, or unresolved alternatives with those grades; do not treat
performative skepticism as an inspectable countermodel.

Refuse positive qualification when the record cites an earlier source revision
while omitting a known later revision in the admitted source packet that
materially supersedes, narrows, withdraws, or contradicts the support carrying
a required field. Preserve the earlier revision as historical evidence and
grade unresolved lineage conflict explicitly; do not treat every later revision
or unrelated edit as disqualifying.

Refuse positive qualification when the admitted packet directly and materially
contradicts the source support for a required field and the record labels that
field passed without preserving and grading the conflict. This does not require
source unanimity or make every tension disqualifying; contested, narrowed, or
unresolved support remains explicit rather than silently passed.

Refuse positive qualification when individually traceable source fragments are
combined as one record without an admitted source-backed bridge connecting the
qualifying assumption, changed condition, affected system or standing, and
review path. Multiple sources, incomplete bridges, and contested relationships
may remain graded evidence; field-level citations alone cannot silently create
a bounded review chain.

Refuse positive qualification when a record names a correction route but the
admitted source or explicit synthetic basis shows that route cannot receive,
review, escalate, stop, revise, or expose the relevant assumption through an
accountable path. A visible label alone is not a correction route; preserve an
incapable or unresolved route as uncertainty, an absorber, an inquiry, or a
separate topology question without inventing a remedy.

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

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public official sources center resource
adequacy, capacity planning, market practice, operating reserve scarcity,
import limits, load forecast, resource procurement, or similar capacity-
tradeoff controls rather than source-backed assumption reuse under changed
conditions.

Record a case as an absorber or separate topology question, not positive
evidence for this candidate, when public official sources center newly
introduced design, configuration, shop-drawing, construction-detail,
calculation-review, or change-control assumptions rather than source-backed
reuse of an old assumption under changed conditions.

These refusal notes are source-gated and do not authorize legal, regulatory,
environmental, health, enforcement, automotive, compliance, building-code,
fire-safety, emergency-response, public-safety, warning, communication,
alerting-system, rail-safety, train-control, transportation-safety, bridge-
safety, structural-engineering, transportation-infrastructure, inspection,
maintenance, construction-load, electric-reliability, power-market, resource-
procurement, operating-reserve, load-forecasting, planning, or domain-remedy
conclusions, construction-management conclusions, professional-liability
conclusions, design-review conclusions, shop-drawing-review conclusions,
change-control conclusions, nuclear-safety conclusions, tsunami-hazard
conclusions, severe-accident-management conclusions, emergency-planning
conclusions, radiation-health conclusions, or external-hazard design-basis
conclusions.

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
| `SF-CRA-0001` | Refused as positive fit. The synthetic fixture names a visible route, but its admitted packet shows that the route cannot receive, review, or carry the relevant correction to an accountable owner. | The falsifier prevents a route label from simulating an operable correction path. |
| `SF-0005` | Fits as a refurbishment, external-wall, fire-safety, and resident-warning review-chain record under public official evidence. | Building-safety, product, fire-service, resident-engagement, regulatory, and legal domains narrow but do not absorb source-backed validation burden and correction route. |
| `SF-ABS-0003` | Refused as positive fit. The NIST Station nightclub source set is a fire/life-safety code, material, sprinkler, pyrotechnic, egress, inspection, and emergency-response protection absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can accept one building/fire-safety review-chain record without claiming every public fire-safety failure. |
| `SF-SQA-0001` | Refused as positive fit. Source-thin or hindsight-built pattern matches cannot qualify without source-backed assumption context, changed condition, validation burden, review owner, and correction route. | Source-quality failure absorbs attractive narratives before they stretch the candidate into a retrospective pattern label. |
| `SF-CEQ-0001` | Refused as positive fit. Source-backed positive-fit fields plus a generic, untraceable, and ungraded alternative do not satisfy the counterevidence gate. | The falsifier prevents performative skepticism from appearing as inspectable contradiction while preserving weak alternatives as graded leads or uncertainty. |
| `SF-SRL-0001` | Refused as positive fit. A named earlier source revision cannot carry qualification when a known later revision in the admitted packet materially withdraws or contradicts its support and the record hides that lineage. | The falsifier prevents revision-specific citation from laundering materially superseded support while preserving earlier revisions as historical evidence. |
| `SF-IPC-0001` | Refused as positive fit. A named admitted packet cannot carry qualification when it directly and materially contradicts the support for a required field and the record leaves that conflict undispositioned. | The falsifier prevents selective source excerpts from silently passing a field while preserving graded contested or unresolved evidence. |
| `SF-TC-0001` | Refused as positive fit. Same-system identity and chronology cannot carry qualification when the admitted packet shows the old assumption was retired before the changed condition and supplies no evidence of continued reliance or reuse. | The falsifier prevents a record from manufacturing temporal coexistence while keeping the nine core fields unchanged. |
| `SF-ABS-0004` | Refused as positive fit. The Hawaii false-alert source set is a warning/communication, drill-procedure, alert-origination, safeguard, and correction-message absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve warning-route pressure without claiming every public alerting or communication failure. |
| `SF-ABS-0005` | Refused as positive fit. The Amtrak Train 188 source set is a single-owner execution, situational-awareness, speed-compliance, train-control, occupant-protection, and emergency-response absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve affected standing and correction-route visibility without claiming every point-of-operation execution failure. |
| `SF-ABS-0006` | Refused as positive fit. The I-35W bridge-collapse source set is a slow-degradation, infrastructure-capacity, original-design-calculation, added-load, load-rating, construction-load, and inspection-guidance absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve long-lived defect and changed-load pressure without claiming every infrastructure-capacity failure. |
| `SF-ABS-0007` | Refused as positive fit. The California August 2020 rotating-outage source set is a resource-adequacy, capacity-planning, market-practice, operating-reserve, import-limit, and net-load-timing absorber, not an assumption-reuse review-chain record. | The absorber shows the candidate can preserve multi-actor planning and correction-route visibility without claiming every capacity-tradeoff failure. |
| `SF-ABS-0008` | Refused as positive fit. The Kansas City Hyatt walkway-collapse source set is a new or changed design, connection-capacity, hanger-rod-arrangement, calculation-review, shop-drawing-review, and construction-communication absorber, not an old-assumption reuse review-chain record. | The absorber shows the candidate can preserve review and correction-route visibility without claiming every changed design or construction-detail failure. |
| `SF-MIX-0001` | Mixed pressure, not counted as a sixth positive record. The Fukushima Daiichi source set shows old tsunami design-basis and reassessment pressure, but also strong nuclear-safety, tsunami-hazard, severe-accident, regulatory, and emergency-response absorber pressure. | The mixed test adds a source-gated design-basis reassessment annotation while refusing schema acceptance or domain-remedy conclusions. |
| `SF-FN-0001` | False-negative pressure, not counted as a sixth positive record. The Challenger source set shows a plausible review-chain failure where old-assumption, changed-condition, validation-burden, dissent, reversal, and escalation visibility all matter. | The pressure adds a source-gated technical-dissent escalation annotation while refusing schema acceptance, launch-safety conclusions, or spaceflight/domain remedies. |

## Next Falsifier

Do not accept this schema yet.
`SF-SCHEMA-DISPOSITION-0002-two-absorber-post-disposition.md` compares
`SF-ABS-0002` and `SF-ABS-0003`, keeps the candidate provisional, and refuses
schema acceptance.

`SF-SCHEMA-ACCEPTANCE-BAR-0001-review-chain-fields.md` completed a
non-accepting acceptance-bar review. It names future promotion prerequisites,
remaining false-positive and false-negative classes, counterevidence that would
kill or demote the candidate, and the proper acceptance authority.

Recent tests have covered the named source-quality, warning/communication,
single-owner execution, slow-degradation infrastructure-capacity, resource
adequacy, newly formed assumption, mixed-case, and false-negative pressure
classes. The candidate remains provisional until any remaining unresolved
classes are explicitly deferred with reasons or routed to the proper owner.

`SF-SQA-0001-source-quality-falsifier.md` tests one remaining class by refusing
source-quality and hindsight-artifact fits.
`SF-CEQ-0001-counterevidence-quality-asymmetry.md` tests whether the
counterevidence field can be satisfied by generic, untraceable, and ungraded
alternatives. It refuses that asymmetric evidence posture while keeping the
core field list unchanged.
`SF-SRL-0001-source-revision-lineage.md` tests whether a named earlier source
revision can carry qualification after a known later revision in the admitted
source packet materially withdraws or contradicts its support. It refuses that
lineage omission while keeping the core field list unchanged.
`SF-IPC-0001-intra-packet-contradiction.md` tests whether a directly material
contradiction already visible within an admitted packet can be left
undispositioned while a required source field is labelled passed. It refuses
that selective-source posture while keeping the core field list unchanged.
`SF-TC-0001-temporal-coherence.md` tests whether same-system identity and
chronology can substitute for evidence that an old assumption remained active
or was reused during a later changed condition. It refuses that temporal gap
while keeping the core field list unchanged.
`SF-CRA-0001-correction-route-authority.md` tests whether a named but incapable
route can satisfy the correction gate. It refuses that name-only route posture
while keeping the core field list unchanged.
`SF-ABS-0004-warning-communication-false-alert.md` tests another by refusing a
non-synthetic warning/communication false-positive case.
`SF-ABS-0005-single-owner-execution-train-188.md` tests another by refusing a
non-synthetic single-owner execution and protective-control false-positive
case.
`SF-ABS-0006-slow-degradation-bridge-collapse.md` tests another by refusing a
non-synthetic slow-degradation and infrastructure-capacity false-positive case.
`SF-ABS-0007-resource-adequacy-rolling-outages.md` tests another by refusing a
non-synthetic resource-adequacy and capacity-tradeoff false-positive case.
`SF-ABS-0008-new-assumption-walkway-collapse.md` tests another by refusing a
non-synthetic newly formed or changed design-assumption false-positive case.
`SF-MIX-0001-fukushima-tsunami-design-basis.md` tests a borderline mixed case
where old design-basis assumption reuse and domain-specific nuclear,
external-hazard, regulatory, and emergency-management explanations all remain
material.
`SF-FN-0001-challenger-launch-decision-dissent-path.md` tests the
false-negative class by showing that the candidate can represent Challenger
only if technical dissent, no-launch recommendation, constraint reversal, and
escalation visibility are explicitly available as source-gated annotation
pressure.

`SF-SCHEMA-ACCEPTANCE-PACKET-0001-review-chain-fields.md` packages the current
evidence and explicitly refuses schema acceptance. It keeps the candidate as a
local provisional screen, freezes the current field list only for provisional
use, names unresolved-class deferrals, and recommends no Joe action unless Joe
separately asks to review acceptance. Future tests should be added only when a
new public or synthetic case creates material pressure on a core field, refusal
note, annotation, source gate, or correction-route gate.

`SF-ANNOTATION-LINEAGE-RECONCILIATION.md` restores the source-gated
`procedural_acceptance_criteria_gap` annotation to the maintained candidate and
non-accepting packet after repository history showed no intentional retirement.
It does not promote the annotation or accept the schema.
