---
trace_id: SF-CONCEPTION-PATROL-DETECTION-ESCAPE-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0009]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# Conception Patrol-To-Detection-To-Escape Partial Trace

## Boundary

This trace preserves only the source-local relation among the required roving
patrol, operator implementation, regulatory verification, fire detection,
warning opportunity, firefighting and evacuation feasibility, escape geometry,
and affected standing in `NTSB/MAR-20/03` and `SF-0009`.

It does not determine the ignition source or timing; reconstruct complete
warning receipt, passenger or crew evacuation custody, operator review,
regulatory disposition, implementation, relative causal weight, or control
effect; or infer recurrence, one patrol, fire, detection, warning,
firefighting, evacuation, escape, operator, regulatory, emergency, or
maritime-safety mechanism. It creates no blame, duty, liability, remedy,
schema, acceptance, receiver work, or external action.

## Source Set

- National Transportation Safety Board, *Fire Aboard Small Passenger Vessel
  Conception*, Marine Accident Report `NTSB/MAR-20/03`, adopted October 20,
  2020, executive-summary pages x-xii and report sections 2.5-2.9:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/MAR2003.pdf
- Bounded owner record `SF-0009`.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| patrol requirement | A roving patrol was required while passengers slept. | The requirement is distinct from operator implementation and inspection verification. | Complete communication, acknowledgment, and shift-level custody are not reconstructed. |
| patrol implementation | The required patrol was not maintained; NTSB found that its absence delayed detection and allowed the fire to grow. | Crew performance and operator oversight remain distinct from the regulatory requirement. | Complete assignment, supervision, review, escalation, and correction remain unknown. |
| regulatory verification | Coast Guard inspections had no effective means to verify patrol compliance. | Inspection capability is distinct from vessel implementation and company oversight. | Complete inspector knowledge, accountable receipt, disposition, and correction custody are not established. |
| fire detection | The salon lacked smoke detection; bunkroom detectors would alarm only after a salon fire was well developed. | Detection equipment is distinct from human patrol and warning receipt. | Exact ignition source, ignition timing, first detection, and complete alarm custody remain unknown. |
| warning | Delayed detection reduced the opportunity for timely warning, but complete warning receipt is not reconstructed. | Detection, alarm emission, crew warning, and passenger receipt are separate objects. | Exact warning path, timing, recipient set, acknowledgment, and escalation remain unknown. |
| firefighting | NTSB found that delayed detection allowed fire growth that precluded firefighting efforts. | Detection time, access, firefighting capability, command, and observed result remain separate. | Complete command custody, equipment use, alternative feasibility, and relative effect remain unknown. |
| evacuation and escape | Both bunkroom exits led into the salon, allowing one fire to block both escape paths and precluding evacuation. | Warning and evacuation custody are distinct from physical escape geometry. | Complete passenger and crew movement, assistance, decision custody, and counterfactual escape effect remain unknown. |
| affected standing and control effect | Thirty-three passengers and one crewmember died; the report identifies multiple safety issues. | Fatal consequence establishes direct standing, not one mechanism or relative causal weight. | Complete implementation, interaction, relative causal weight, and control effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `preserve_partial_patrol_detection_escape_trace`.

The official source supports a bounded relation from missing patrol through
delayed detection and reduced firefighting and evacuation opportunity, while
keeping regulatory verification, smoke detection, warning, escape geometry,
operator oversight, and consequence distinct. The unknown ignition source,
separate detection and escape protections, and incomplete custody or
disposition paths are counterevidence to one complete control mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the required patrol was maintained, that its absence did not delay
detection, or that the two bunkroom exits did not lead through the salon.
Reject any stronger chain that fills the preserved warning, custody, authority,
disposition, implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
ordered trace objects, and supplied patrol, inspection, detection, and escape
facts; removed invented generic authorities and gap labels; independently
checked the controlling owner source boundary; and authored the row-local
custody distinctions, counterevidence, falsifier, correction route, and
non-promotion boundary.

Family lineage: `SF-LIN-CONCEPTION-PATROL-DETECTION-ESCAPE-TRACE-01`.
