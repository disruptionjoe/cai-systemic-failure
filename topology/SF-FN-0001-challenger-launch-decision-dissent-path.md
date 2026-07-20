---
test_id: SF-FN-0001
status: false_negative_pressure_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-07-19
source_material: public_official_sources
external_action: none
---

# SF-FN-0001 - Challenger Launch Decision Dissent-Path Pressure

## Boundary

This false-negative pressure test uses public official Challenger accident
source material to test whether `SF-SCHEMA-CANDIDATE-0001` can represent a
review-chain failure where the source-backed correction path is not only a
generic owner review route, but an explicit technical dissent, no-launch
recommendation, constraint, reversal, and escalation path.

It does not create an accepted topology schema, launch-safety finding,
spaceflight recommendation, solid-rocket-booster model, management-standard
claim, legal conclusion, CAI doctrine, intervention plan, or owner routing
instruction.

No confidential material, human subjects, field work, account access, external
contact, posting, spending, publication outside normal GitHub versioning, or
deployment was used.

## Source Set

- NASA Technical Reports Server, "Report of the Presidential Commission on the
  Space Shuttle Challenger Accident, Volume 1":
  https://ntrs.nasa.gov/citations/19860015255
- NASA History Office HTML edition, "Chapter V: The Contributing Cause of The
  Accident":
  https://www.nasa.gov/history/rogersrep/v1ch5.htm

Source posture: public official U.S. government/NASA source material. The
repository stores pointers and synthesis only; it does not copy the source
artifacts.

## False-Negative Question

The candidate would be too narrow if it could not represent a public official
review-chain failure where the most correction-relevant evidence is an
engineering dissent path that was reversed or contained before reaching all
accountable launch decision owners.

The Rogers Commission source set supports that pressure. The NASA NTRS record
summarizes the Commission's conclusion that the accident involved failure of
the right solid rocket motor aft field-joint pressure seal and that the launch
decision chain had incomplete and misleading information, conflict between
engineering data and management judgment, and a management structure that let
flight-safety problems bypass key Shuttle managers. Chapter V records prior
O-ring and joint concerns, a contractor engineering recommendation against
launch below prior temperature experience, management reversal of that
recommendation, and incomplete communication to higher launch decision levels.

That source set looks like a review-chain case the candidate should not miss.
The pressure is not that the candidate lacks old-assumption, changed-condition,
validation-burden, affected-standing, or correction-route concepts. It is that
the current fields under-name a specific correction route shape: technical
dissent or constraint escalation that is converted, waived, contained, or
non-escalated before the accountable decision owner sees the unresolved
contradiction.

## Candidate Gate Results

| Candidate gate or field | Result | Constraint preserved |
|---|---|---|
| Public or safely shareable sources | Passes. The source set is public official NASA/U.S. government material. | No source artifacts copied; no confidential, personal, or field data used. |
| Assumption reused under changed condition | Passes as pressure. Prior O-ring and field-joint experience was carried into an unusually cold launch condition and a launch-readiness context the source says key decision-makers did not fully understand. | The test does not turn every launch decision or design issue into old-assumption reuse. |
| Validation burden source-backed | Passes. The source set supports a validation burden around O-ring/field-joint performance at temperatures below prior flight experience and around launch-readiness information flow. | The burden remains source-backed; this file does not supply an independent engineering model. |
| Affected standing explicit | Passes. Crew, launch decision owners, contractor engineers and management, Shuttle program owners, and public safety standing are visible in the source context. | Affected standing does not authorize legal, management, engineering, or safety recommendations. |
| Delegation or review visibility gap | Passes and pressures the field shape. Contractor engineering dissent, contractor management reversal, Marshall/project paths, Flight Readiness Review levels, Mission Management Team awareness, and higher launch decision visibility all matter. | The candidate should distinguish generic distributed review from source-backed dissent conversion and escalation failure. |
| Absorber or counterevidence present | Passes. Solid-rocket-booster design, cold-temperature material behavior, launch operations, NASA management structure, contractor-customer pressure, and communication process all narrow the case. | Domain and management explanations are preserved instead of flattened into generic review-chain language. |
| Correction route stop condition | Passes but is under-specified by the current candidate fields. No-launch recommendation, launch-constraint treatment, waiver or reversal review, and escalation to accountable launch decision owners are visible correction routes. | This repository records owner-visible routes without prescribing launch-safety, management, engineering, regulatory, legal, or program remedies. |

## Verdict

`SF-SCHEMA-CANDIDATE-0001` should not treat Challenger as a false negative if
the existing `delegation_visibility_gap` and `correction_route_stop_condition`
fields are read broadly enough to include technical dissent, no-launch
recommendations, constraint reversal, and escalation visibility.

The pressure still matters. Without an explicit annotation, the candidate can
represent the Challenger source set only by stretching generic "delegation" and
"correction route" language. That would hide the most useful field-shape lesson:
some review-chain failures hinge on whether a source-backed technical objection
or stop condition remained visible after management conversion, waiver, or
containment.

This test is not counted as a sixth positive record. It is a false-negative
field-shape pressure test. The candidate remains provisional and unaccepted.

## Candidate Revision Pressure

Keep the core field set unchanged, but add one source-gated annotation pressure
to the candidate:

`technical_dissent_escalation_path`: source-backed technical objections,
no-go recommendations, launch or operating constraints, waiver or constraint
review, management reversal or containment, and whether unresolved dissent
reached accountable decision owners.

This annotation must remain non-mandatory. It cannot let a record qualify
without the core source, old-assumption, changed-condition, validation-burden,
affected-standing, absorber, and correction-route gates. It also cannot
authorize launch-safety, engineering, program-management, legal, regulatory,
spaceflight, public-safety, or domain-remedy conclusions.

## Non-Promotion Result

This false-negative pressure test does not:

- accept `SF-SCHEMA-CANDIDATE-0001` as schema;
- create a universal systemic-failure ontology;
- issue a launch-safety, spaceflight, engineering, management, regulatory,
  legal, public-safety, procurement, contractor-governance, or domain-remedy
  recommendation;
- authorize human research, field research, participation, contact, posting,
  publication outside GitHub, deployment, spending, account access, or external
  action;
- change CAI phase, relationship, membership, automation, or proving authority;
  or
- move another repository's claims, canon, or work state.

## Next Test

The candidate remains provisional. The next useful work is a non-accepting
acceptance packet or an explicit deferral of remaining unresolved classes before
any schema-acceptance question is routed.
