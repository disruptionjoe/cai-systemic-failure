---
trace_id: SF-SANBRUNO-RECOGNITION-ISOLATION-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0027]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# San Bruno Recognition-To-Isolation Partial Trace

## Boundary

This trace preserves only the source-local relation from the physical Line 132
rupture through SCADA indication, public reporting and municipal response,
operator recognition, location and dispatch, valve operation, isolation, and
flow cessation in `NTSB/PAR-11/01` and `SF-0027`.

It does not reconstruct complete signal custody, command transfer, location
decision, dispatch or valve authority, response chronology, correction,
implementation, relative causal weight, or control effect; infer recurrence or
one rupture, pressure-control, SCADA, reporting, dispatch, location, valve,
isolation, emergency-response, regulatory, or safety-management mechanism; or
create blame, duty, remedy, acceptance, receiver work, health causation,
liability, or external action.

## Source Set

- National Transportation Safety Board, *Pacific Gas and Electric Company
  Natural Gas Transmission Pipeline Rupture and Fire, San Bruno, California,
  September 9, 2010*, `NTSB/PAR-11/01`, executive-summary pages x-xii and
  report pages 1-2, 53-59, 89-116, and 124-130:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1101.pdf
- NTSB investigation page `DCA10MP008`:
  https://www.ntsb.gov/investigations/Pages/DCA10MP008.aspx
- Bounded owner record `SF-0027`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| rupture state | Line 132 ruptured during a pressure increase associated with terminal work, released natural gas, and ignited in a residential area. | Terminal work, pressure control, deficient seam, rupture, release, ignition, recognition, and consequence remain separate. | Complete work-plan custody, pressure-decision sequence, rupture-time knowledge, ignition path, and relative contribution are not reconstructed. |
| SCADA indication | PG&E's SCADA system lacked real-time leak or line-break detection and sufficiently spaced pressure and flow instrumentation; NTSB found those limitations delayed recognition and location of the break. | Physical rupture, instrument state, control-room display, operator interpretation, public report, and location decision are distinct. | Complete signal chronology, alarm presentation, operator receipt, challenge, escalation, and decision custody remain incomplete. |
| public reporting and municipal response | Local responders arrived promptly and managed the fire defensively while gas continued to flow; PG&E did not immediately notify emergency officials that one of its transmission pipelines had ruptured. | Resident reports, 911, police and fire response, incident command, utility notification, operator dispatch, and pipeline isolation remain separate. | Complete call custody, operator-to-911 communication, municipal-to-utility transfer, and effect on isolation timing are not established. |
| operator recognition | SCADA information and outside communications did not immediately produce a coordinated recognition of a transmission-line break; NTSB found SCADA limitations contributed to delayed recognition and location. | Individual indications, control-room interpretation, engineering knowledge, dispatch knowledge, supervisory authority, and field confirmation remain distinct. | Complete recognition threshold, accountable synthesis, command transfer, and location decision are not reconstructed. |
| location and dispatch | PG&E dispatch learned of the explosion, initially sent one service representative, and had not officially dispatched a qualified valve-isolation crew when the control room identified Line 132 as feeding the fire. | Event location, transmission-line identification, service assessment, qualified crew dispatch, travel, valve assignment, and field command remain separate. | Complete dispatch chronology, crew qualification decision, route, field receipt, and isolation authority remain incomplete. |
| valve operation and isolation | PG&E took 95 minutes to stop the gas flow and isolate the rupture site; NTSB found the delay excessive and found that automatic shutoff or remote-control valves would have reduced isolation time. | Control-room action, remote station valves, manual valves, field crews, automatic protection, isolation boundary, and flow cessation remain distinct. | Complete valve sequence, each operator authorization, field verification, flow response, and counterfactual protection effect are not established. |
| standing and control effect | Eight people died, many were injured or evacuated, homes were destroyed or damaged, and responders could not fully access the area until the gas flow stopped. | Residents, evacuees, responders, operator staff, CPUC, PHMSA, and NTSB occupy different affected, operating, response, oversight, and recommendation positions. | Complete participation, accountable correction, implementation, health effects, relative causal weight, and verified control effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_sanbruno_recognition_isolation_trace`.

The report supports a bounded relation from rupture indications and public
information through delayed operator recognition and location to field valve
operation, isolation, and flow cessation. It does not support one complete
signal-to-command chain. Distinct SCADA, public reporting, municipal response,
dispatch, field operation, valve protection, standing, and oversight objects
are counterevidence to a universal recognition-and-isolation mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that SCADA limitations did not delay recognition and location, that PG&E did
not take 95 minutes to stop flow and isolate the rupture, or that the delayed
isolation did not constrain responder access. Reject any stronger chain that
fills preserved custody, authority, chronology, correction, implementation,
causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
seven ordered objects, supplied rupture, recognition, response, isolation,
unknown, and non-effect facts; repaired substituted missing-link cells and the
non-operative single-relation falsifier; independently reconciled
`NTSB/PAR-11/01` through `SF-0027`; and authored source custody, chronology,
authority distinctions, counterevidence, correction, and non-promotion
boundaries.

Family lineage: `SF-LIN-SANBRUNO-RECOGNITION-ISOLATION-PARTIAL-TRACE-01`.
