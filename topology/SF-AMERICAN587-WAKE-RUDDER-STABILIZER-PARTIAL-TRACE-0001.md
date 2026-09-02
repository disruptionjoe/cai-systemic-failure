---
trace_id: SF-AMERICAN587-WAKE-RUDDER-STABILIZER-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0034]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# American Airlines Flight 587 Wake-To-Stabilizer Partial Trace

## Boundary

This trace preserves only the source-local relation from the second wake-
turbulence encounter through control inputs, rudder-system response, sideslip
and aerodynamic-load buildup, vertical-stabilizer separation, aircraft
response, training and design context, affected standing, and consequence in
`NTSB/AAR-04/04` and `SF-0034`.

It does not reconstruct complete cue perception, input-by-input intent and
effect, training-to-action custody, design and certification chronology, post-
separation control chronology, correction, implementation, relative causal
weight, or verified control effect; infer recurrence or one wake-turbulence,
rudder, pilot-input, training, upset-recovery, aircraft-pilot-coupling,
aerodynamic-load, structural-failure, aircraft-response, design,
certification, airline, manufacturer, regulatory, or affected-party
mechanism; or create blame beyond NTSB findings, duty, remedy, acceptance,
receiver work, health causation, liability, or external action.

## Source Set

- National Transportation Safety Board, *In-Flight Separation of Vertical
  Stabilizer, American Airlines Flight 587, Airbus Industrie A300-605R,
  N14053, Belle Harbor, New York, November 12, 2001*, Aircraft Accident Report
  `NTSB/AAR-04/04`, executive summary, sections 1.1, 1.6, 1.17, 2.2-2.4,
  findings, probable cause, and recommendations:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/AAR0404.pdf
- NTSB investigation page `DCA02MA001`:
  https://www.ntsb.gov/investigations/Pages/DCA02MA001.aspx
- Bounded owner record `SF-0034`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| wake encounter | Flight 587 encountered a second wake-turbulence event shortly after takeoff, and the first officer responded with control-wheel and rudder-pedal inputs. | Environmental encounter, cue perception, control-wheel input, pedal input, pilot intent, and aircraft response remain distinct. | Complete cue perception, expectation, and initial decision chronology remain unresolved. |
| alternating rudder inputs | The first officer then made five alternating full rudder-pedal inputs over about 6.5 seconds before the vertical stabilizer separated. | Pedal command, rudder motion, pilot intent, perceived response, sideslip, load, and later separation remain separate. | Input-by-input intent, feedback, effect, and decision custody remain incomplete. |
| rudder-system response | NTSB found that the A300-600 rudder system combined increasing sensitivity with airspeed and unusually light pedal forces among the transport aircraft it evaluated. | Pedal force and displacement, travel-limiter behavior, rudder deflection, airspeed, aircraft motion, human perception, and design remain distinct. | Complete design-choice, fleet-comparison, certification, and control-effect custody remain incomplete. |
| sideslip and aerodynamic load | Alternating full inputs rapidly built sideslip and aerodynamic loads beyond the vertical stabilizer's ultimate design load. | Pilot input, rudder position, sideslip, aerodynamic load, structural capacity, and failure remain separate. | Complete time-resolved input, response, load, and structural-margin sequence remains incomplete. |
| vertical-stabilizer separation | NTSB determined that loads created by the first officer's unnecessary and excessive rudder-pedal inputs caused the vertical stabilizer to separate in flight. | Input, system response, aerodynamic loading, attachment structure, stabilizer separation, and rudder separation remain distinct. | Complete local fracture chronology and counterfactual structural response are not reconstructed. |
| aircraft response | The stabilizer and rudder separated before the engines; the airplane then departed controlled flight and crashed. | Flight-control loss, aircraft motion, later engine separation, impact, and postcrash fire remain separate. | Complete post-separation control chronology, crew action, and impact sequence remain incomplete. |
| training, design, and certification | NTSB identified A300-600 rudder-system design characteristics and elements of American Airlines' Advanced Aircraft Maneuvering Program as contributors to the rudder inputs and separately examined certification and guidance. | Airline curriculum, instructor delivery, pilot learning, manufacturer design, structural analysis, certification basis, FAA guidance, and accident action remain distinct. | Complete training-to-action, design-decision, certification, review, correction, and implementation custody remain unresolved. |
| standing and consequence | The 2 flight crewmembers, 7 flight attendants, and 251 passengers aboard, plus 5 people on the ground, died. | Crew, passengers, ground residents, airline staff, manufacturer, regulator, responders, families, and investigators occupy different affected, operating, design, oversight, response, and investigative positions. | Complete participation, individual response, representation, ground effects, and health effects beyond the fatal accident remain outside this trace. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_american_587_wake_rudder_stabilizer_trace`.

The report supports a bounded event-local relation among the second wake
encounter, alternating rudder inputs, rudder-system response, sideslip and load
buildup, vertical-stabilizer separation, loss of control, training and design
context, standing, and consequence. It does not support one complete cue-to-
certification custody chain. Separate environmental cue, pilot action, system
response, structural capacity, training, design, certification, standing, and
consequence are counterevidence to one universal mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the unnecessary and excessive rudder-pedal inputs did not create loads
beyond ultimate design or that those loads did not cause the vertical
stabilizer to separate. Reject any stronger chain that fills the preserved
cue, intent, training, design, certification, chronology, correction,
implementation, causal-weight, or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report or NTSB
investigation page changes a cited fact or boundary. Frontier retained the
candidate's bounded decision, nine ordered objects, principal source-local
relations, operative falsifier, exact unknowns, and non-effect; independently
checked `NTSB/AAR-04/04`; and authored source custody, authority distinctions,
counterevidence, correction, uncertainty, and non-promotion boundaries.

Family lineage:
`SF-LIN-AMERICAN587-WAKE-RUDDER-STABILIZER-PARTIAL-TRACE-01`.
