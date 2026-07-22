---
record_id: SF-0002
status: source_backed_synthesis
claim_status: investigation_synthesis
lane: "1"
created: 2026-07-18
source_material: public_official_report
external_action: none
---

# SF-0002 - Columbia Foam-Strike Review Chain

## Boundary

This record is a bounded public-source synthesis of the Space Shuttle Columbia
accident investigation. It tests whether the provisional topology fields from
`SF-0001` survive a second record. It is not a spaceflight safety finding,
engineering recommendation, NASA governance judgment, or intervention plan.

No confidential material, human subjects, field work, account access, external
contact, or deployment was used.

## Source Set

- Columbia Accident Investigation Board, "Report Volume I", August 2003,
  available through NASA NTRS: https://ntrs.nasa.gov/citations/20030093634
- Columbia Accident Investigation Board, "Report Volume I", UNT/GPO public
  mirror: https://digital.library.unt.edu/ark:/67531/metadc1282018/
- NASA "Remembering the Columbia STS-107 Mission" public page, which points to
  the six-volume CAIB report: https://www.nasa.gov/remembering-columbia-sts-107/

## Pattern Summary

The bounded pattern is not "foam caused damage" by itself. The useful topology
question is how a known hazard and an in-mission damage concern could remain
insufficiently decisive inside the review and escalation system.

For this repository, the record is narrow:

- repeated foam-shedding experience made the hazard easier to treat as an
  accepted operational condition;
- the STS-107 strike changed the review burden because it involved a live
  mission and potential thermal-protection damage;
- the source-reported review path did not keep uncertainty, imagery need,
  technical dissent, management disposition, and crew-risk standing as one
  accountable contradiction object;
- recommendations after the accident emphasized independent technical
  authority, better imagery and inspection, and more disciplined hazard control.

## Topology Field Test

| Candidate field from `SF-0001-CM1` | SF-0002 result |
|---|---|
| Assumption identifier and source revision | Survives. The assumption is not a pilot-response assumption; it is hazard-acceptability and damage-assessment sufficiency under a specific mission context. |
| Assumption owner and accountable review owner | Survives and strengthens. The record needs both technical ownership and management disposition ownership. |
| Affected system and affected-party standing | Survives. The affected system is the orbiter and mission, with crew standing explicit. |
| Change event or changed input/function path | Survives with a broader label. The event is an observed mission anomaly and damage concern, not a design-function change. |
| Validation method and validation burden | Survives. Imagery, inspection, analysis, and uncertainty handling become validation methods rather than optional notes. |
| Alert, interface, workload, or environment interaction | Narrows. The useful field is broader than flight-deck workload: call it `operating_or_observation_environment`. |
| Delegation path and visibility gap | Survives. Distributed technical, management, and request paths must preserve dissent and unresolved uncertainty. |
| Counterevidence or absorber model | Survives. The ordinary absorber is "known foam event handled as normal maintenance or acceptable risk." |
| Correction route and stop condition | Survives. The record needs a route for unresolved hazard evidence and an explicit stop or escalation condition. |

## New Field Pressure

`SF-0002` adds two pressures that `SF-0001` did not force clearly enough:

- `hazard_history`: how previous non-catastrophic occurrences shape the
  apparent normality of a new event;
- `observation_request_path`: how requests for additional evidence, such as
  imagery or inspection, are escalated, denied, or allowed to expire.

These are candidate pressures, not accepted schema fields. They must still
survive an absorber or third record before becoming repository structure.

## Counterevidence And Absorbers

The strongest absorber is that this was a domain-specific technical accident
whose lessons belong only in aerospace safety practice. That absorber is partly
right: this repository must not generalize engineering conclusions. It does not
absorb the review-chain pattern, because the source-backed synthesis here only
tracks owner, evidence, uncertainty, validation burden, escalation, and
correction routing.

The second absorber is "more inspection would have fixed it." That is too
narrow for this record because the topology question is not a remedy; it is how
the need for stronger evidence becomes visible and accountable before the
system treats the old assumption as still adequate.

## Uncertainty And Falsifiers

This synthesis may compress distinct technical, mission-management, imagery-
request, and institutional decisions into one review-chain pattern. The public
report set supports a bounded comparison, not a complete reconstruction of
individual knowledge, intent, or every decision path.

Falsify or narrow this record if closer source review shows either that the
unresolved damage concern, imagery need, technical dissent, and management
disposition were already preserved as one accountable contradiction object, or
that the proposed cross-domain pattern cannot be stated without importing a
spaceflight-specific engineering conclusion.

## Owner Routing

Any spaceflight engineering, NASA governance, certification, or operational
recommendation belongs to the relevant domain authorities, not this repository.
This repository may preserve the source-backed failure pattern and use it to
test generic topology fields.

## Correction Route

If later source review shows this synthesis overstates the CAIB record, correct
this file and any dependent topology test. Do not silently promote the field
set into a universal schema.
