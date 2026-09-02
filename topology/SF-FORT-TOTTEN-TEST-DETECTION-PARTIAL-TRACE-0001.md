---
trace_id: SF-FORT-TOTTEN-TEST-DETECTION-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0028]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# Fort Totten Test-To-Detection Partial Trace

## Boundary

This trace preserves only the source-local relation among the 2005 Rosslyn
warning, WMATA's enhanced verification test, technician knowledge, June 2009
verification, the B2-304 module signal state, loss of train detection, and
automatic speed commands in `NTSB/RAR-10/02` and `SF-0028`.

It does not reconstruct complete bulletin or test custody, maintenance
response, train-control authority, oversight correction, implementation,
relative causal weight, or control effect; infer recurrence or one warning,
test, training, track-circuit, signal, detection, speed-command, maintenance,
oversight, or crashworthiness mechanism; or create blame, duty, remedy,
acceptance, receiver work, liability, health causation, or external action.

## Source Set

- National Transportation Safety Board, *Collision of Two Washington
  Metropolitan Area Transit Authority Metrorail Trains Near Fort Totten
  Station, Washington, D.C., June 22, 2009*, `NTSB/RAR-10/02`, abstract and
  report pages ix-xii, 35-50, 85-113, and 119-125:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/RAR1002.pdf
- NTSB investigation page `DCA09MR007`:
  https://www.ntsb.gov/investigations/Pages/DCA09MR007.aspx
- Bounded owner record `SF-0028`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| Rosslyn warning | After 2005 near-collisions at Rosslyn, WMATA developed an enhanced verification test for track-circuit failures. | Prior event evidence, engineering analysis, bulletin creation, procedure ownership, and later field use remain separate. | Complete warning intake, accountable receipt, review, approval, and closure are not reconstructed. |
| enhanced test | NTSB found the enhanced test would have identified the faulty Fort Totten circuit, but WMATA did not institutionalize and use it systemwide. | Test capability, formal procedure, training, work planning, compliance, and corrective action are distinct objects. | Complete adoption decision, exception handling, implementation custody, and verification remain unknown. |
| technician knowledge | Technicians interviewed after the accident were not familiar with the enhanced test. | Bulletin distribution, supervisor knowledge, technician training, qualification, task assignment, and field performance remain distinct. | Complete communication path, roster, training record, accountable review, and challenge route are incomplete. |
| June 2009 verification | Proper shunt placement during June 2009 testing could have exposed the loss of train detection before the accident. | Test design, shunt placement, observed signal, result interpretation, work closure, and repair authority are separate. | Complete task instruction, actual placement custody, result review, escalation, and disposition are not reconstructed. |
| module signal state | Parasitic oscillation in the B2-304 modules produced a spurious signal that mimicked a valid signal and indicated the circuit vacant while train 214 occupied it. | Physical module condition, waveform, track relay, represented occupancy, maintenance evidence, and later testing remain distinct. | Complete defect evolution, signal history, monitoring threshold, and corrective disposition remain incomplete. |
| train detection and speed command | Loss of train 214 detection permitted the automatic train-control system to transmit speed commands to train 112 up to impact. | Physical occupancy, detected occupancy, route logic, transmitted command, onboard control, operator action, braking, and collision are separate. | Complete command chronology, onboard receipt, fallback authority, intervention opportunity, and comparative contribution are not established. |
| standing and control effect | Nine people aboard train 112 died and 52 people were transported to hospitals; the report separately addressed maintenance, safety management, oversight, and crashworthiness. | Operator, passengers, families, responders, WMATA, Board, state and federal oversight, injury severity, and later action remain distinct. | Complete warning-to-governance custody, correction, implementation, relative causal weight, and verified control effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_fort_totten_test_detection_trace`.

The report supports a bounded relation from prior warning and a capable test
through incomplete institutionalization and field use to an undetected false-
vacant signal and automatic speed commands. Distinct component, test,
knowledge, work, command, oversight, and crashworthiness objects are
counterevidence to one complete test-to-control or authority mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the enhanced verification test would not have identified the faulty
circuit, that proper shunt placement could not have exposed the detection loss,
or that the B2-304 false-vacant indication did not permit speed commands to
train 112. Reject any stronger chain that fills preserved custody, authority,
correction, implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
ordered objects, supplied test-to-detection relation, operative falsifier,
unknowns, and non-effect; repaired circular missing-link cells and the broken
affected-party literal; independently reconciled `NTSB/RAR-10/02` through
`SF-0028`; and authored source custody, role distinctions, counterevidence,
correction, and non-promotion boundaries.

Family lineage: `SF-LIN-FORT-TOTTEN-TEST-DETECTION-PARTIAL-TRACE-01`.
