---
trace_id: SF-SCHOHARIE-OOS-DISPATCH-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0030]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# Schoharie Out-Of-Service-To-Dispatch Partial Trace

## Boundary

This trace preserves only the source-local relation from the NYSDOT out-of-
service finding through unresolved carrier receipt and repair verification,
missing operating authority, carrier dispatch, brake condition and operation,
and affected standing in `NTSB/HAR-20/03` and `SF-0030`.

It does not reconstruct complete order custody, repair history, inspection
decision, information transfer, enforcement chronology, dispatch decision,
correction, implementation, relative causal weight, or verified control
effect; infer recurrence or one out-of-service, repair, verification,
operating-authority, dispatch, brake, maintenance, inspection, registration,
enforcement, occupant-protection, regulatory, or safety-management mechanism;
or create blame beyond the NTSB finding, duty, remedy, acceptance, receiver
work, health causation, liability, or external action.

No recurrence, shared mechanism or authority, schema, remedy, acceptance,
receiver work, health causation, liability, or external action is accepted.

## Source Set

- National Transportation Safety Board, *Stretch Limousine Run-Off-Road Crash
  Near Schoharie, New York, October 6, 2018*, `NTSB/HAR-20/03`, abstract and
  report pages vii-x, 1-19, 52-83, and 89-92:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/HAR2003.pdf
- NTSB investigation page `HWY19MH001`:
  https://www.ntsb.gov/investigations/Pages/HWY19MH001.aspx
- Bounded owner record `SF-0030`.

The NTSB report controls. Later recommendation implementation, criminal or
civil proceedings, compensation, individual medical history, and third-party
material are not imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| out-of-service finding | NYSDOT placed the limousine out of service before the crash for safety defects that included brake deficiencies. | Inspection finding, written order, vehicle status, carrier knowledge, repair claim, verification, enforcement, and later dispatch remain separate. | Complete order custody, accountable carrier receipt, and day-of-trip enforcement chronology are not reconstructed. |
| carrier receipt | The carrier later dispatched the same out-of-service limousine, but the current bounded source set does not reconstruct the exact receipt path for the order. | Agency issuance, carrier ownership, employee receipt, record custody, dispatch knowledge, and driver receipt remain distinct. | Recipient, timestamp, transmission path, acknowledgement, internal challenge, and accountable disposition remain unknown. |
| repair representation and verification | The vehicle had not been verified as repaired, and NTSB found NYSDOT's repair-verification process inadequate. | Carrier repair representation, supporting records, agency review, physical verification, vehicle release, and enforcement remain separate. | Complete repair history, representation custody, verification decision, rejection or acceptance, and correction are not reconstructed. |
| operating authority | Prestige Limousine lacked authority to transport passengers in New York. | Carrier identity, registration, vehicle status, operating authority, charter commitment, driver qualification, and enforcement remain distinct. | Complete authority notice custody, carrier receipt, enforcement chronology, and accountable stop opportunity remain incomplete. |
| dispatch | Prestige Limousine dispatched the limousine for a passenger charter despite the out-of-service order and without operating authority. | Ownership, charter booking, dispatch, vehicle assignment, driver assignment, status knowledge, and passenger knowledge remain separate. | Complete dispatch decision, internal challenge, driver receipt, passenger information, and correction route remain unknown. |
| brake condition and operation | NTSB found the brake system inadequately maintained and in poor condition; rear-brake components showed evidence they had not been appreciably working, and the brakes failed to slow the vehicle on the grade. | Maintenance, component condition, braking capacity, driver action, route demand, dispatch, and enforcement remain distinct. | Complete maintenance and inspection history, functional-test evidence, failure mode, and relative contribution remain unresolved. |
| standing and consequence | The driver, 17 passengers, and two pedestrians died; NTSB found the emergency response timely and adequate. | Vehicle occupants, pedestrians, bystanders, responders, carrier staff, inspectors, agencies, and regulators occupy different affected, operating, response, and oversight positions. | Complete participation, occupant-protection sequence, correction, implementation, legal duty, health causation beyond the crash findings, and verified control effect remain outside this trace. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_schoharie_oos_dispatch_trace`.

The report supports a bounded relation between the prior out-of-service
finding, unverified repair, absent operating authority, later carrier
dispatch, brake condition and operation, and affected standing. It does not
support one complete order-to-dispatch custody chain. Distinct inspection,
carrier receipt, repair representation, verification, operating authority,
dispatch, maintenance, driver, occupant, pedestrian, response, and oversight
objects are counterevidence to one universal enforcement mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that NYSDOT did not place the limousine out of service before the crash, that
the carrier did not dispatch that vehicle for the charter despite the order
and without operating authority, or that the rear brakes did not show evidence
of prolonged nonfunction. Reject any stronger chain that fills preserved
receipt, repair, verification, authority, enforcement, correction,
implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
seven ordered objects, selected supplied facts, unknowns, and non-effect;
repaired the substituted carrier-receipt, repair-verification, standing, and
falsifier content; independently reconciled `NTSB/HAR-20/03` through
`SF-0030`; and authored source custody, authority distinctions,
counterevidence, correction, uncertainty, and non-promotion boundaries.

Family lineage: `SF-LIN-SCHOHARIE-OOS-DISPATCH-PARTIAL-TRACE-01`.
