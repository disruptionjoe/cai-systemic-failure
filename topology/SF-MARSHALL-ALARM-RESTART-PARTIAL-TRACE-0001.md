---
trace_id: SF-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0025]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# Marshall Alarm-To-Restart Partial Trace

## Boundary

This trace preserves only the source-local relation among rupture indications,
column-separation interpretation, the ten-minute stop rule, shutdown, field
verification, restart permission, outside-notification inference, and delayed
recognition in `NTSB/PAR-12/01` and `SF-0025`.

It does not reconstruct complete alarm custody, challenge, accountable review,
authority, verification, correction, implementation, relative causal weight,
or control effect; infer recurrence or one alarm, procedure, training,
operator, response, regulatory, environmental, or health mechanism; or create
blame, duty, liability, remedy, schema, acceptance, receiver work, or external
action.

## Source Set

- National Transportation Safety Board, *Enbridge Incorporated Hazardous
  Liquid Pipeline Rupture and Release, Marshall, Michigan, July 25, 2010*,
  Pipeline Accident Report `NTSB/PAR-12/01`, report pages 24-29, 52-54, and
  98-101:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1201.pdf
- Bounded owner record `SF-0025`.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| rupture and transient state | Line 6B ruptured during the final minute of a planned shutdown. | Physical rupture, planned operating state, pressure transient, later startup, and release remain distinct. | Complete shutdown planning, transient-risk review, and rupture-time operator knowledge are not reconstructed. |
| leak indications | A sudden Marshall pressure drop, local pump-station shutdown alarm, and material-balance alarm were leak triggers under control-center procedures. | SCADA values, software alarms, physical rupture, operator receipt, and analyst review are separate objects. | Complete signal custody, alarm presentation, acknowledgment, and cross-check sequence remain incomplete. |
| initial interpretation | Staff accepted column separation as the explanation and an analyst characterized alarms as false during the startup sequence. | Operator observation, analyst interpretation, shift-lead review, supervisor input, and physical pipeline state remain distinct. | Complete challenge, alternative review, dissent, and accountable disposition are not established. |
| ten-minute stop rule | Procedures required a leak to be ruled out within ten minutes or the pipeline to be shut down; suspected column separation also required valve closure and an abnormal-operation record. | Procedure text, approval state, operator action, shift-lead notification, and recorded disposition remain distinct. | Complete procedure selection, communication, exception authority, and contemporaneous record custody remain incomplete. |
| first shutdown | The first startup continued beyond the restriction and was then shut down after pumped and received volumes were compared. | Continued pumping, volume comparison, shift-lead instruction, shutdown, and valve state are separate. | Complete decision timing, alternative evidence review, isolation verification, and consequence attribution remain unknown. |
| restart authorization | The operative procedure allowed restart only after field personnel confirmed no leak and the designated on-call supervisor permitted restart; staff instead used an unapproved draft procedure in the accident sequence. | Field confirmation, shift-lead action, supervisor permission, procedure approval, and startup execution remain separate. | Complete field request, local verification, permission record, and compliance custody are not reconstructed. |
| outside-notification inference | Staff treated the absence of outside reports as evidence against rupture and did not actively obtain local confirmation before visual evidence arrived. | Community observation, outside reporting, control-center inference, field verification, and operator notification are distinct. | Complete public-information access, call custody, verification request, and counterfactual recognition effect remain unknown. |
| recognition and stop | The rupture was not recognized for more than 17 hours, during which two startups added most of the estimated release. | Alarm interpretation, restart, recognition, final shutdown, response mobilization, and release consequence remain distinct. | Complete recognition custody, final stop authority, local confirmation, correction, and relative causal weight remain incomplete. |

## Decision, Counterevidence, And Falsifier

Decision: `preserve_partial_marshall_alarm_restart_trace`.

The report supports a bounded relation from leak indications through
interpretation, procedural stop requirements, shutdown and restart decisions,
outside-notification inference, and delayed recognition. Distinct SCADA,
software, procedure, operator, analyst, supervisor, field, community, and
physical-state objects are counterevidence to one complete alarm or authority
mechanism.

Falsify or materially narrow the trace if closer official-source review shows
that the three identified leak triggers were not present, that the ten-minute
shutdown requirement did not govern the sequence, or that staff did not use
the column-separation interpretation when restarting. Reject any stronger
chain that fills preserved custody, authority, verification, correction,
implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
ordered trace objects, supplied facts, unknowns, and non-effect; repaired row-
local custody, first-shutdown and restart distinctions, and the operative
falsifier; independently checked `NTSB/PAR-12/01`; and authored the source
custody, counterevidence, correction route, and non-promotion boundary.

Family lineage: `SF-LIN-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-01`.
