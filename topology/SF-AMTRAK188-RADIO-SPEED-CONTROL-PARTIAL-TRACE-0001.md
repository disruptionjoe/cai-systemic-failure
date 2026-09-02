---
trace_id: SF-AMTRAK188-RADIO-SPEED-CONTROL-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0029]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# Amtrak Train 188 Radio-To-Speed-Control Partial Trace

## Boundary

This trace preserves only the source-local relation from nearby-train radio
information through attention allocation, situational awareness, curve and
speed state, signal and rule boundaries, absent automatic enforcement,
emergency braking, derailment, and affected standing in `NTSB/RAR-16/02` and
`SF-0029`.

It does not reconstruct complete attention custody, cue receipt, train-control
decision sequence, positive-train-control implementation history, correction,
relative causal weight, or verified control effect; infer recurrence or one
radio, attention, situational-awareness, speed-control, signal, operating-rule,
train-control, braking, derailment, occupant-protection, emergency-response,
regulatory, or safety-management mechanism; or create blame, duty, remedy,
acceptance, receiver work, health causation, liability, or external action.

## Source Set

- National Transportation Safety Board, *Derailment of Amtrak Passenger Train
  188, Philadelphia, Pennsylvania, May 12, 2015*, `NTSB/RAR-16/02`, abstract
  and report pages vii-x, 1-16, 20-28, 31-45, and 51-57:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/RAR1602.pdf
- NTSB investigation page `DCA15MR010`:
  https://www.ntsb.gov/investigations/Pages/DCA15MR010.aspx
- Bounded owner record `SF-0029`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| radio information | The engineer monitored a six-minute radio exchange about an emergency involving a nearby SEPTA train and remained focused on that incident as train 188 approached the accident area. | Required monitoring, radio content, operational relevance, dispatcher and engineer roles, and train handling remain distinct. | Complete message custody, cue receipt, relevance assessment, challenge, and return-to-task sequence are not reconstructed. |
| attention allocation | NTSB found that the engineer's attention was likely diverted to the nearby-train emergency as train 188 approached Frankford Junction. | Radio receipt, attention allocation, memory, location awareness, throttle action, and later recollection are separate. | Complete attention chronology, competing cues, accountable task-management boundary, and recovery opportunity remain incomplete. |
| situational awareness | NTSB concluded that the engineer lost situational awareness and accelerated without slowing for the curve. | Attention state, route knowledge, location recognition, speed monitoring, throttle action, and brake action remain distinct. | The exact transition, cue interpretation, speed-target decision, and comparative contribution are not established. |
| speed and curve | Train 188 entered the permanent 50 mph Frankford Junction curve at 106 mph. | Curve geometry, timetable restriction, cab display, operating action, train speed, braking, and overturn threshold remain separate. | Complete rule-cue custody, location decision, speed-target decision, and remaining intervention opportunity are not reconstructed. |
| signal and rule boundary | Cab-signal protection did not enforce the eastbound 50 mph permanent restriction because the design assumed trains would approach below overturn speed. | Operating rule, timetable, wayside and cab signals, design assumption, engineer compliance, and automatic enforcement remain distinct. | Complete assumption review, rule-display sequence, implementation authority, and correction history remain unknown. |
| automatic enforcement | Positive train control was not implemented in the accident area; NTSB found PTC or equivalent permanent-restriction enforcement would have prevented the accident. | Statutory program, route deployment, trainborne equipment, speed target, enforcement, operator action, and regulator oversight remain separate. | Complete implementation custody, schedule, readiness decision, exception history, and counterfactual sequence are not reconstructed. |
| braking, derailment, and standing | The engineer applied emergency braking as the train entered the curve; seconds later the train derailed, eight passengers died, and 185 people were transported to hospitals. | Recognition, brake command, brake response, derailment dynamics, occupant protection, passenger standing, response, and oversight remain distinct. | Complete recognition-to-brake chronology, occupant-specific sequence, response custody, correction, and verified protection effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_amtrak188_radio_speed_control_trace`.

The report supports a bounded relation from nearby-train radio information
through likely attention diversion and loss of situational awareness to the
speed excursion, while separately preserving absent automatic enforcement,
late emergency braking, derailment, and affected standing. It does not support
one complete radio-to-control chain. Distinct radio, attention, route, rule,
signal, PTC, operator, braking, occupant, response, and oversight objects are
counterevidence to a universal attention or speed-control mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the engineer did not monitor the nearby SEPTA emergency, that NTSB did not
find his attention was likely diverted and situational awareness lost, or that
train 188 did not enter the 50 mph curve at 106 mph. Reject any stronger chain
that fills preserved custody, decision, implementation, correction, causal-
weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
seven ordered objects, supplied radio, attention, awareness, speed, rule,
signal, enforcement, braking, derailment, standing, unknown, and non-effect
facts; repaired the ellipsis in a load-bearing row; independently reconciled
`NTSB/RAR-16/02` through `SF-0029`; and authored source custody, authority
distinctions, counterevidence, correction, uncertainty, and non-promotion
boundaries.

Family lineage: `SF-LIN-AMTRAK188-RADIO-SPEED-CONTROL-PARTIAL-TRACE-01`.
