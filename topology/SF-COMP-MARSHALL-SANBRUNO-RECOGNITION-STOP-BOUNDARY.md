---
comparison_id: SF-COMP-MARSHALL-SANBRUNO-RECOGNITION-STOP-BOUNDARY
status: provisional_public_source_comparison
records: [SF-0025, SF-0027]
lane: "1"
created: 2026-09-02
source_material: public_official_reports
external_action: none
---

# Marshall And San Bruno Recognition-And-Stop Boundary

## Boundary

This comparison preserves a bounded relation between two rupture-recognition
and stopping sequences in `NTSB/PAR-12/01`, `NTSB/PAR-11/01`, `SF-0025`,
`SF-0027`, and `SF-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-0001`.

Marshall concerns a hazardous-liquid rupture during planned shutdown followed
by alarm interpretation, two startups, delayed recognition, and final stop.
San Bruno concerns a gas-transmission rupture and ignition followed by delayed
break recognition and location, field valve operation, isolation, and flow
cessation. Similar recognition pressure does not establish recurrence, one
leak-detection, SCADA, procedure, reporting, dispatch, valve, isolation,
emergency-response, regulatory, or safety-management mechanism, or shared
authority.

## Source Set

- National Transportation Safety Board, *Enbridge Incorporated Hazardous
  Liquid Pipeline Rupture and Release, Marshall, Michigan, July 25, 2010*,
  `NTSB/PAR-12/01`, executive-summary pages xii-xiv and report pages 8-15,
  52-54, and 93-101:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1201.pdf
- National Transportation Safety Board, *Pacific Gas and Electric Company
  Natural Gas Transmission Pipeline Rupture and Fire, San Bruno, California,
  September 9, 2010*, `NTSB/PAR-11/01`, executive-summary pages x-xii and
  report pages 13-18, 54-57, 100-105, and 124-128:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1101.pdf
- Bounded owner records `SF-0025`, `SF-0027`, and
  `SF-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-0001`.

The official NTSB reports control. Later implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Bounded Comparison

| Comparison object | Marshall boundary | San Bruno boundary | Shared relation or preserved separation |
| --- | --- | --- | --- |
| transported material and physical state | Line 6B carried hazardous liquid and ruptured during the final minute of a planned shutdown. | Line 132 carried natural gas, ruptured during a pressure increase, and ignited in a residential area. | Physical rupture and loss of containment are shared at a high level; material, operating state, ignition, consequence, and response remain separate. |
| remote indication | Pressure, flow, and material-balance indications and alarms were available during the shutdown and startups. | SCADA limitations delayed recognition of the transmission-line break and pinpointing its location. | Remote indications did not by themselves produce timely recognition in either case; signal types, system limits, custody, interpretation, and physical state remain distinct. |
| interpretation and recognition | Staff used column separation to interpret abnormal indications, characterized alarms as false, and did not recognize the rupture for more than 17 hours. | PG&E recognition and location of the break were delayed, while public reporting and municipal response occurred on a separate path. | Both reports preserve recognition delay, but Marshall's repeated transient interpretation differs from San Bruno's break-location and response sequence. |
| procedure or protection | Control-center procedures required unresolved abnormal or column-separation conditions to stop within ten minutes, yet an unapproved draft procedure was used during the startups. | The affected length lacked automatic shutoff or remote-control valves, and the report separately examined emergency procedures and isolation capability. | Marshall centers a procedural stop and restart boundary; San Bruno centers recognition, location, valve capability, and field isolation. Procedure and protection are not one control object. |
| stopping action | The first startup was stopped after pumped-versus-received volumes were compared; a later startup followed, and most of the release occurred after rupture before final recognition and shutdown. | PG&E took 95 minutes to stop gas flow by isolating the rupture site through field valve operation. | Both sequences concern stopping flow after rupture, but restart authority, final shutdown, valve access, dispatch, isolation, and elapsed time remain different objects. |
| community information and response | Staff treated the absence of outside reports as evidence against rupture; later outside notification enabled recognition after residents and responders had already encountered the release. | City responders arrived promptly and managed the fire defensively while gas continued to flow until isolation. | Community information and municipal response were consequential in both cases, but their timing, custody, hazard, operating authority, and effect remain separate. |
| standing and control effect | Residents self-evacuated, waterways were affected, and environmental and community standing differed from operator and regulator roles. | Residents, evacuees, injured people, responders, operator staff, CPUC, PHMSA, and NTSB occupied different exposure, action, and oversight positions. | Affected standing does not establish shared decision authority, relative causal weight, recurrence, or a verified comparative control effect. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_bounded_recognition_stop_comparison` while preserving
separate restart and isolation sequences.

The official reports support a bounded comparison of remote indication,
recognition, and stopping after rupture. They do not support one complete
signal-to-stop chain or a shared controller, analyst, supervisor, dispatcher,
field operator, responder, regulator, community, or affected-party authority.
Different transported materials, transient states, hazard paths, reporting
roles, stopping actions, response conditions, and consequences are
counterevidence to recurrence or one mechanism.

Falsify or materially narrow the comparison if closer official-source review
shows that Marshall did not involve a shutdown/restart sequence after rupture,
or that San Bruno did not require field isolation after delayed recognition and
location. Reject any stronger comparison that fills signal or report custody,
accountable review, recognition, shutdown or isolation authority, correction,
implementation, relative causal weight, community-information effect, or
control effect absent from the reports.

## Correction Route And Frontier Verification

Correct this comparison and dependent summaries if either controlling report
changes a cited fact or boundary. Frontier retained the candidate's bounded
decision, seven comparison objects, supplied event facts, unknowns, and non-
effect; repaired its broad shared labels and standing row; independently
reviewed both NTSB reports; and authored source custody, exact preserved
separations, counterevidence, falsifier, correction route, and non-promotion
boundaries.

Family lineage: `SF-LIN-COMP-MARSHALL-SANBRUNO-RECOGNITION-STOP-01`.
