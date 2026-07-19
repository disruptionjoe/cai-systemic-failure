---
test_id: SF-ABS-0005
status: negative_absorber_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-07-19
source_material: public_official_sources
external_action: none
---

# SF-ABS-0005 - Single-Owner Execution Error Absorber

## Boundary

This negative absorber uses the Amtrak Train 188 / Philadelphia derailment
official source set to test whether `SF-SCHEMA-CANDIDATE-0001` refuses a real
public-source transportation disaster when the stronger public-source
explanation is point-of-operation situational awareness, task management, speed
compliance, and train-control protection rather than source-backed assumption
reuse under changed conditions.

It does not create an accepted topology schema, rail-safety model,
transportation-safety recommendation, train-control standard, legal conclusion,
regulatory conclusion, CAI doctrine, intervention plan, or owner routing
instruction.

No confidential material, human subjects, field work, account access, external
contact, posting, spending, publication outside normal GitHub versioning, or
deployment was used.

## Source Set

- National Transportation Safety Board, "Derailment of Amtrak Passenger Train
  188, Philadelphia, Pennsylvania, May 12, 2015", NTSB/RAR-16/02:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/RAR1602.pdf
- Federal Railroad Administration, "Amtrak 188 Derailment May 2015":
  https://railroads.dot.gov/human-factors/elearning-attention/amtrak-188-derailment-may-2015
- Federal Railroad Administration emergency-order publication, "Operational and
  Signal Modifications for Compliance With Maximum Authorized Passenger Train
  Speeds":
  https://www.federalregister.gov/documents/2015/06/12/2015-14394/operational-and-signal-modifications-for-compliance-with-maximum-authorized-passenger-train-speeds

Source posture: public official source material. The repository stores pointers
and synthesis only; it does not copy the source artifacts.

## Absorber Question

The provisional candidate should refuse this case as positive evidence if its
gates are doing real work.

The source set describes Amtrak Train 188 entering the Frankford Junction curve
far above the restricted speed, after the engineer's attention was diverted by
radio traffic about another train emergency. The NTSB source also centers the
absence of positive train control or another enforcing control system at that
location, plus passenger-window, occupant-protection, and emergency-response
issues. For this repository, that is a single-owner execution and protective
train-control absorber, not a review-chain assumption-reuse record.

The case is useful because it creates tempting surface fit: affected people are
central, train-control implementation and regulatory routes are visible, and
several institutional correction routes appear in official sources. Positive
fit still requires a source-backed old assumption reused under a changed
condition, a visible validation burden, delegation or review fragmentation
material to that contradiction, absorber control, and an owner-visible
correction route.

## Candidate Gate Results

| Candidate gate or field | Result | Constraint preserved |
|---|---|---|
| Public or safely shareable sources | Passes. The source set is public official NTSB and FRA material. | No source artifacts copied; no confidential, personal, or field data used. |
| Assumption reused under changed condition | Refused as central fit. The official sources do not require an inherited assumption reused under a changed validation context to explain the derailment. | A point-of-operation error does not automatically become an assumption-reuse review-chain case. |
| Validation burden source-backed | Refused as positive fit. The source set centers situational awareness, task management, speed enforcement, positive train control, occupant protection, and emergency response rather than unresolved revalidation of an old source context. | Rail-safety and train-control remedies are not flattened into generic validation-burden language. |
| Affected standing explicit | Passes. Passengers, crew, injured people, fatalities, responders, rail operators, and public-safety agencies remain visible in the official source context. | Affected standing and severe consequence alone cannot qualify a case. |
| Delegation or review visibility gap | Partly passes but is not central. Amtrak, FRA, NTSB, train-control owners, emergency responders, and standards bodies matter, but the source-backed explanation does not depend on review-chain fragmentation around a reused assumption. | Multi-owner safety infrastructure is not enough to create positive evidence. |
| Absorber or counterevidence present | Passes. The single-owner execution, situational-awareness, speed-compliance, train-control, occupant-protection, and response-coordination account absorbs the review-chain candidate for this case. | The absorber is recorded without becoming a universal rail-safety topology. |
| Correction route stop condition | Partly passes but does not rescue candidate fit. Official routes include crew training, attention-management practices, positive train control or automatic speed enforcement, speed-limit signage, occupant protection, and mass-casualty response coordination. | This repository records owner-visible routes without prescribing Amtrak, FRA, NTSB, railroad, emergency-response, legal, regulatory, or domain action. |

## Verdict

`SF-SCHEMA-CANDIDATE-0001` refuses this case as positive evidence. That refusal
is useful after the warning/communication absorber because it shows that an
officially documented disaster with affected-party standing, visible correction
routes, and multi-owner safety infrastructure does not qualify when the central
source-backed explanation is single-owner execution and protective-control
absence rather than assumption reuse under changed conditions.

The candidate remains provisional and local to review-chain failures involving
source-backed assumption reuse under changed conditions, visible validation
burden, affected standing, absorber control, and correction-route discipline.
This negative absorber does not justify schema acceptance.

## Candidate Revision Pressure

Keep the candidate field set as-is, but add one refusal note to the candidate:
when public official sources center single-operator or crew execution,
situational awareness, task management, speed compliance, protective-control
absence or enforcement, or similar point-of-operation performance rather than
source-backed assumption reuse under changed conditions, the case should be
recorded as an absorber or separate topology question, not positive evidence
for this candidate.

This note must remain source-gated. It does not authorize this repository to
make rail-safety, train-control, transportation-safety, emergency-response,
legal, regulatory, enforcement, public-safety, labor, training, or domain-remedy
conclusions.

## Non-Promotion Result

This absorber test does not:

- accept `SF-SCHEMA-CANDIDATE-0001` as schema;
- create a universal systemic-failure ontology;
- issue a rail-safety, train-control, transportation-safety,
  emergency-response, public-safety, legal, regulatory, compliance,
  enforcement, training, occupant-protection, or domain-remedy recommendation;
- authorize human research, field research, participation, contact, posting,
  publication outside GitHub, deployment, spending, account access, or external
  action;
- change CAI phase, relationship, membership, automation, or proving authority;
  or
- move another repository's claims, canon, or work state.

## Next Test

The candidate remains provisional. The next useful falsifier should come from a
different remaining class: resource scarcity or capacity tradeoff, slow
degradation or maintenance drift, newly formed assumption rather than reused
assumption, a borderline mixed case, or a false-negative pressure case where a
plausible review-chain failure is not well represented by the current fields.
