---
test_id: SF-TC-0001
status: temporal_coherence_falsifier
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-24
source_material: synthetic_fixture_and_repository_controls
external_action: none
---

# SF-TC-0001 - Temporal Coherence

## Boundary

This falsifier tests whether `SF-SCHEMA-CANDIDATE-0001` can qualify a record
when the admitted synthetic packet identifies an old assumption and a later
changed condition in the same system but does not show that the old assumption
was active or reused during that condition.

It adds no real-world record, accepts no schema, makes no domain finding,
prescribes no remedy, authorizes no research or participation, and performs no
external action.

## Falsifier Class

Shared system identity and chronological order do not establish temporal
coexistence. A record can join an old assumption at one time to a changed
condition at another and appear to satisfy both fields even when the admitted
packet shows the assumption was retired or replaced before the changed
condition occurred.

This pressure is distinct from weak counterevidence (`SF-CEQ-0001`), hidden
source revisions (`SF-SRL-0001`), an incapable correction route
(`SF-CRA-0001`), unbridged systems or review chains (`SF-CEC-0001`), and an
undispositioned direct conflict (`SF-IPC-0001`). Here the source history, system
identity, retirement event, and route are all visible; the missing relationship
is evidence that the old assumption still governed the later condition.

## Synthetic Fixture

The abstract fixture supplies:

- at T1, `A-old` is active in bounded System S and review owner R1 is named;
- at T2, the admitted packet says `A-old` is retired and replaced by `A-new`;
- at T3, System S encounters a changed operating condition, unmet validation
  burden, affected standing, and fragmented review;
- the packet fully discloses T2 and supplies a graded countermodel plus a route
  capable of carrying the relevant correction; but
- the proposed record combines T1 and T3, labels reuse of `A-old` passed, and
  supplies no evidence that `A-old` remained active or was reused at T3.

No real system, source, person, organization, or failure is represented.

## Candidate Gate Results

| Candidate gate or field | Result | Constraint preserved |
|---|---|---|
| Safely shareable material | Passes as a synthetic fixture. | No real-world claim is added. |
| Bounded system and evidence bridge | Passes. T1, T2, and T3 belong to System S and the complete sequence is admitted. | This is not an unbridged-fragment CEC failure. |
| Source revision and contradiction visibility | Passes. The retirement event is disclosed and dispositioned. | This is neither hidden lineage nor an undispositioned IPC conflict. |
| `assumption_source_context` | Refused. The packet does not show `A-old` was active or reused during T3 and instead says it was retired before T3. | Qualification requires evidence for the temporal relationship it asserts. |
| `changed_condition`, standing, and validation burden | Pass only as T3 fixture premises. | A later condition cannot supply reuse of an earlier assumption. |
| `absorber_or_counterevidence` | Passes as a graded synthetic premise. | Counterevidence quality does not repair missing coexistence evidence. |
| `correction_route_stop_condition` | Passes as a capable synthetic premise. | Route capability does not establish that `A-old` governed T3. |

## Verdict

`SF-SCHEMA-CANDIDATE-0001` refuses this fixture as positive evidence. Same-
system identity, chronology, and full disclosure of T2 do not prove reuse at
T3. The record may preserve the sequence as historical evidence, an absorber,
uncertainty, or a separate topology question, but it cannot label old-
assumption reuse passed without an admitted temporal bridge.

## Candidate Revision Pressure

Keep the nine core fields and provisional status unchanged. Narrow existing
`assumption_source_context` and record-bridge language so the admitted evidence
must connect the reused assumption to the interval or event in which the
changed condition creates the validation burden. When the packet shows that
the assumption was retired or replaced first, refuse positive qualification
unless separate evidence shows continued reliance or reuse. Grade incomplete
or contested timing explicitly; do not add a new core field.

## Non-Promotion Result

This falsifier does not accept the candidate, create a universal ontology, add
a real-world failure record, issue a recommendation or remedy, authorize human
or field research, change CAI phase or public posture, or move another owner's
truth or work.

## Next Test

Keep the candidate provisional. Add another test only when new public or
synthetic material creates distinct pressure on a core field, refusal note,
annotation, source gate, or correction-route gate. Record count alone is not
progress.
