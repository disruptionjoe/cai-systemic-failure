---
trace_id: SF-MERRIMACK-DESIGN-CONTROL-LINE-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0026]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# Merrimack Design-To-Control-Line Partial Trace

## Boundary

This trace preserves only the source-local relation among an operating low-
pressure distribution system, incomplete project documentation and review,
regulator sensing-line configuration, main-abandonment sequence, regulator
response, SCADA monitoring, field isolation, and system shutdown in
`NTSB/PAR-19/02` and `SF-0026`.

It does not reconstruct complete design-change custody, field communication,
inspector awareness, accountable review, correction, implementation, regulator
disposition, relative causal weight, or control effect; infer recurrence or one
design, documentation, sensing-line, pressure-control, construction,
inspection, protection, emergency-response, regulatory, or safety-management
mechanism; or create blame, duty, liability, remedy, schema, acceptance,
receiver work, or external action.

## Source Set

- National Transportation Safety Board, *Overpressurization of Natural Gas
  Distribution System, Explosions, and Fires in Merrimack Valley,
  Massachusetts, September 13, 2018*, Pipeline Accident Report
  `NTSB/PAR-19/02`, abstract and report pages 1-12, 38-44, and 53-59:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1902.pdf
- NTSB investigation page `PLD18MR003`:
  https://www.ntsb.gov/investigations/Pages/PLD18MR003.aspx
- Bounded owner record `SF-0026`.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| project operating state | Columbia Gas contracted a main-replacement project while the low-pressure distribution system remained operating to limit service interruption. | System operating state, project design, construction work, regulator state, customer service, and public exposure remain separate objects. | Complete operating-state approval, risk review, field communication, and decision custody are not reconstructed. |
| design documentation | The work package did not document the regulator sensing lines connected to the cast-iron main. | System records, engineering plans, work package, field configuration, constructability review, and crew knowledge remain distinct. | Complete record creation, transfer, reconciliation, accountable review, and correction remain incomplete. |
| engineering review and approval | NTSB found the project did not receive a sufficiently comprehensive engineering review; it also identified the public-utility professional-engineer exemption and recommended sealed plans for future work. | Designer, reviewer, approver, professional engineer, construction coordinator, contractor, inspector, and regulator are separate roles. | Complete assignment, review exchange, approval record, challenge, and prework disposition are not established. |
| sensing-line configuration | The regulator sensing lines remained connected to the old cast-iron main rather than being relocated to the new polyethylene main before abandonment. | Old and new mains, sensing lines, worker and monitor regulators, project drawing, physical field state, and system pressure remain distinct. | Complete configuration custody, field verification, inspector awareness, and correction opportunity are unknown. |
| work sequence | The crew abandoned the cast-iron main before the sensing lines were relocated. | Planned sequence, work instruction, crew action, construction inspection, system response, and later shutdown are separate objects. | Complete sequencing decision, communication, hold point, authorization, and contemporaneous challenge are not reconstructed. |
| regulator response | Pressure fell in the abandoned main and sensing lines, causing the regulators to open and admit high-pressure gas into the low-pressure system. | Sensed pressure, regulator mechanics, high-pressure supply, low-pressure distribution, customer piping, ignition, and consequence remain distinct. | Complete regulator-state custody, intervention opportunity, isolation authority, and comparative contribution remain incomplete. |
| monitoring and field control | SCADA recorded high-pressure alarms but could only monitor the system; field technicians isolated regulator stations and the distribution system was later shut down. | Alarm detection, control-center notification, field recognition, regulator adjustment, station isolation, valve closure, and system shutdown remain distinct. | Complete alarm custody, field dispatch, command transfer, shutdown chronology, implementation, and counterfactual control effect remain unknown. |
| standing and control effect | The overpressure led to fires and explosions across three municipalities, killing one person, injuring others, damaging 131 structures, and affecting more than 10,000 customers. | Residents, firefighters, customers, municipalities, operator, regulator, physical damage, service loss, and later recommendations remain distinct. | Complete affected-party observation, health history, causal weighting, correction, implementation, and remedy effect are not established. |

## Decision, Counterevidence, And Falsifier

Decision: `preserve_partial_merrimack_design_control_trace`.

The report supports a bounded relation from incomplete project documentation
and review through unchanged sensing-line configuration, main-abandonment
sequence, regulator response, monitoring, field isolation, and shutdown.
Distinct project, engineering, field, control-center, physical-system,
regulatory, and affected-standing objects are counterevidence to one complete
design-control or authority mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the cast-iron main was not abandoned before the regulator sensing lines
were relocated, or that the sensing-line pressure loss did not cause the
regulators to admit high-pressure gas. Reject any stronger chain that fills
preserved custody, review, field-awareness, authority, correction,
implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
ordered objects, supplied abandonment-before-relocation relation, operative
falsifier, unknowns, and non-effect; discarded invented or circular row
claims; independently checked `NTSB/PAR-19/02`; and authored source custody,
role distinctions, counterevidence, correction route, and non-promotion
boundary.

Family lineage: `SF-LIN-MERRIMACK-DESIGN-CONTROL-LINE-PARTIAL-TRACE-01`.
