---
trace_id: SF-ALASKA261-MAINTENANCE-TRIM-FAILURE-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0032]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# Alaska Airlines Flight 261 Maintenance-To-Trim-Failure Partial Trace

## Boundary

This trace preserves only the source-local relation from jackscrew lubrication
and maintenance intervals through end-play detection opportunity, thread wear,
jackscrew and trim-system failure, pitch-control loss, flight-crew response,
affected standing, and consequence in `NTSB/AAR-02/01` and `SF-0032`.

It does not reconstruct complete task custody, the specific missed or
inadequate lubrication history, measurement custody, interval-decision and
approval chronology, surveillance chronology, correction, implementation,
relative causal weight, or verified control effect; connect every maintenance-
program deficiency to the accident; infer recurrence or one jackscrew,
lubrication, inspection, interval, wear, trim-control, maintenance-program,
design, certification, surveillance, regulatory, or affected-party mechanism;
or create blame beyond NTSB findings, duty, remedy, acceptance, receiver work,
health causation, liability, or external action.

## Source Set

- National Transportation Safety Board, *Loss of Control and Impact with
  Pacific Ocean, Alaska Airlines Flight 261, McDonnell Douglas MD-83, N963AS,
  About 2.7 Miles North of Anacapa Island, California, January 31, 2000*,
  Aircraft Accident Report `NTSB/AAR-02/01`, abstract, executive summary,
  analysis, findings, probable cause, and recommendations:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/AAR0201.pdf
- NTSB investigation page `DCA00MA023`:
  https://www.ntsb.gov/investigations/Pages/DCA00MA023.aspx
- Bounded owner record `SF-0032`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| lubrication task | NTSB found the acme-nut thread failure resulted from excessive wear caused by insufficient lubrication; no effective lubrication remained at the screw-and-nut interface. | Procedure, scheduled task, actual performance, grease condition, maintainer action, inspection, and physical wear remain distinct. | The specific missed or inadequate lubrication history, task custody, signoff, review, and challenge remain unresolved. |
| lubrication interval | Alaska Airlines extended the lubrication interval, and FAA approved the extension; NTSB found those actions increased the likelihood that missed or inadequate lubrication would produce excessive thread wear. | Manufacturer guidance, airline interval decision, FAA approval, task scheduling, actual task performance, and wear remain separate. | Complete decision basis, technical-data custody, approval chronology, correction, and implementation remain incomplete. |
| end-play check | Alaska Airlines extended the end-play-check interval, and FAA approved that extension; NTSB found excessive wear could then progress to failure without an opportunity for detection. | Measurement method, interval, tool and procedure, inspector action, result custody, airline decision, and FAA approval remain distinct. | Complete measurement custody, interval justification, actual check history, review, and stop condition remain unresolved. |
| thread wear | Insufficient lubrication produced excessive and accelerated wear of the jackscrew assembly's acme-nut threads. | Lubrication state, wear rate, measurement, thread condition, detection opportunity, and later failure remain separate. | Complete wear chronology, intermediate measurements, detection, correction, and relative contribution remain incomplete. |
| jackscrew and trim-system state | The acme-nut threads failed in flight and were completely sheared; the MD-80 lacked a fail-safe mechanism against the catastrophic effects of total thread loss. | Thread condition, jackscrew state, stabilizer position, trim-system design, fail-safe design, certification, and aircraft response remain distinct. | Complete state chronology, design and certification custody, correction, implementation, and verified control effect are not reconstructed. |
| pitch control and crew response | The crew encountered jammed and then failed stabilizer-trim behavior, attempted troubleshooting and recovery, and ultimately lost pitch control. | System indication, checklist and improvised action, crew judgment, stabilizer state, aircraft response, and outcome remain separate. | Complete decision chronology, counterfactual controllability, correction, and verified control effect remain incomplete. |
| maintenance program and FAA oversight | NTSB found widespread systemic deficiencies in Alaska Airlines' maintenance program and deficient FAA surveillance while identifying only specific maintenance deficiencies as accident-related. | Program governance, individual task performance, quality control, staffing, FAA interval approval, surveillance, and accident causation remain distinct. | Complete deficiency-to-event linkage, approval and surveillance chronology, accountable disposition, correction, and implementation remain incomplete. |
| standing and consequence | The 2 pilots, 3 cabin crewmembers, and 83 passengers aboard died. | Flight crew, cabin crew, passengers, maintainers, inspectors, airline staff, manufacturer, FAA, responders, families, and NTSB occupy different affected, operating, maintenance, design, regulatory, response, and investigative positions. | Complete participation, individual response, correction, health effects beyond the fatal accident, and verified control effect remain outside this trace. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_alaska_261_maintenance_trim_failure_trace`.

The report supports a bounded event-local relation among insufficient
lubrication, interval and detection opportunity, excessive thread wear,
in-flight thread failure, trim-system state, pitch-control loss, crew response,
standing, and consequence. It does not support one complete task-to-oversight
custody chain. Separate task performance, interval setting, measurement,
physical wear, system design, crew action, airline-program governance, FAA
approval and surveillance, standing, and consequence are counterevidence to
one universal mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that insufficient lubrication did not produce the excessive thread wear or
that the acme-nut thread failure did not produce the in-flight loss of pitch
control. Reject any stronger chain that fills the preserved task, measurement,
decision, approval, surveillance, correction, implementation, causal-weight,
or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report or NTSB
investigation page changes a cited fact or boundary. Frontier retained the
candidate's bounded trace decision, eight ordered objects, principal causal
relation, exact unknowns, and non-effect; removed an ellipsis, restored the
fail-safe relation, returned task custody to its source-local object, and
independently checked `NTSB/AAR-02/01`. Frontier also authored source custody,
authority distinctions, counterevidence, correction, uncertainty, and non-
promotion boundaries.

Family lineage:
`SF-LIN-ALASKA261-MAINTENANCE-TRIM-FAILURE-PARTIAL-TRACE-01`.
