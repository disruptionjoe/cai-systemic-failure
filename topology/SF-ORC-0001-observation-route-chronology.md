---
test_id: SF-ORC-0001
status: observation_route_chronology_falsifier
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
external_action: none
---

# SF-ORC-0001 - Observation Route Chronology

## Boundary

This synthetic falsifier tests whether eventual routing or dispute can qualify
as observation handling for a reuse decision that was already final. It adds no
record, accepts no schema, infers no signal adequacy, authority, negligence, or
outcome, prescribes no remedy, requests no action, and performs no external
action.

## Falsifier Class

Event existence does not establish decision-time handling. A draft can name a
real display, normalization, route, and dispute while erasing that the route
and dispute occurred only after the decision under review became final. This is
distinct from assumption temporal coherence (`SF-TC-0001`) and decision-time
review authority (`SF-DRA-0001`): here the question is the sequence in which
relevant evidence was handled.

## Synthetic Fixture

- Signal `S-one` was displayed and logged before reuse decision `T-reuse`.
- Before `T-reuse`, note `N-pre` normalized the signal as expected variation;
  no admitted evidence shows pre-decision routing or dispute.
- After `T-reuse` became final, log `L-post` routed the signal to owner `O-one`,
  who disputed the earlier normalization.
- `D-eventual` records all event types without timing and marks
  `observation_environment` passed.
- `D-chronology` preserves the sequence and leaves the field unresolved for
  `T-reuse`. Every non-target core gate passes only as a supplied premise.

## Chronology Result

`D-eventual` is refused because it collapses pre-decision normalization and
post-decision routing or dispute into one timeless pass. `D-chronology`
preserves the later events as graded historical or correction-route evidence
and may continue through the remaining gates without claiming that the signal
was handled before the decision.

## Candidate Revision Pressure

Keep the nine core fields and provisional status unchanged. Narrow existing
`observation_environment` wording so how and when evidence was made visible,
missed, normalized, routed, or disputed remain tied to the decision under
review. Do not infer signal adequacy, authority exercise, negligence, outcome,
or remedy.

## Non-Promotion Result

This falsifier does not accept the candidate, create a universal ontology, add
a real-world record, authorize research or participation, change public
posture, or move another owner's truth or work.
