---
trace_id: SF-STRETCHDUCK7-WARNING-FLOODING-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0031]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# Stretch Duck 7 Warning-To-Flooding Partial Trace

## Boundary

This trace preserves only the source-local relation from the severe-weather
watch and warning through manager direction, tour sequencing, water entry,
storm encounter, return attempt, bow-hatch flooding, rapid sinking, affected
standing, and response in `NTSB/MAR-20/01` and `SF-0031`.

It does not reconstruct complete forecast custody, accountable manager or crew
receipt, tour-decision authority, monitoring chronology, reassessment,
hatch-design or inspection custody, evacuation sequence, correction,
implementation, relative causal weight, or verified control effect; infer
recurrence or one weather, warning, manager, tour, monitoring, go/no-go,
captain, vessel, hatch, flooding, buoyancy, egress, rescue, regulatory, or
safety-management mechanism; or create blame beyond NTSB findings, duty,
remedy, acceptance, receiver work, health causation, liability, or external
action.

## Source Set

- National Transportation Safety Board, *Sinking of Amphibious Passenger
  Vessel Stretch Duck 7, Table Rock Lake, near Branson, Missouri, July 19,
  2018*, Marine Accident Report `NTSB/MAR-20/01`, abstract, executive summary,
  and report pages 1-38 and 44-63:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/MAR2001.pdf
- NTSB investigation page `DCA18MM028`:
  https://www.ntsb.gov/investigations/Pages/DCA18MM028.aspx
- Bounded owner record `SF-0031`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| watch and warning | The National Weather Service issued a severe thunderstorm watch more than 7 hours before the accident and a warning one minute before Stretch Duck 7 departed the shoreside boarding facility. | Forecast production, company access, manager and crew receipt, interpretation, tour scheduling, and water entry remain separate. | Complete forecast custody, accountable receipt, acknowledgement, challenge, and decision chronology remain incomplete. |
| manager direction | The manager-on-duty directed the crew to complete the lake portion before the usual land tour. | Company policy, manager direction, captain and driver roles, crew receipt, passenger boarding, and operating decision remain distinct. | Complete instruction custody, receipt, authority, challenge, and stop opportunity are not reconstructed. |
| tour sequencing and water entry | Stretch Duck 7 entered the water at 1855 after the warning, following the manager's direction to reverse the normal tour sequence. | Manager direction, tour sequence, shoreside departure, captain operation, and lake entry remain separate objects. | Complete tour-decision authority, crew acknowledgement, reassessment, and accountable disposition remain unknown. |
| weather monitoring and policy | Ride The Ducks restricted water entry when severe weather was approaching but lacked a specific go/no-go policy; NTSB found available weather information was not effectively used and the last waterborne tours should have been suspended. | Policy, available information, monitoring, manager action, captain judgment, and operating decision remain distinct. | Complete monitoring chronology, display and alert custody, accountable review, correction, and implementation remain incomplete. |
| storm encounter and return | About 5 minutes after water entry, the leading edge of the storm reached the vessel with strong winds and waves; the vessel later attempted to return to the exit ramp. | Storm timing, observed conditions, captain operation, turn or return decision, propulsion, flooding, and shore response remain separate. | Complete onboard observations, communication, reassessment chronology, return decision, and evacuation opportunity are not reconstructed. |
| hatch flooding and sinking | Waves entered through a non-weathertight bow air-intake hatch; the vessel lacked subdivision and sufficient reserve buoyancy, and uncontrolled flooding produced rapid sinking. | Wave state, hatch configuration, water ingress, hull arrangement, reserve buoyancy, internal flooding, and sinking remain distinct. | Complete hatch-design and inspection custody, flooding chronology, correction, and relative contribution remain incomplete. |
| standing and response | One crewmember and 16 passengers died; 14 people were rescued, and NTSB found the emergency response timely and effective. | Crew, passengers, responders, nearby-vessel personnel, company staff, Coast Guard, and NTSB occupy different affected, operating, response, and oversight positions. | Complete evacuation, rescue custody, participation, correction, health effects, and verified control effect remain outside this trace. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_stretch_duck_7_warning_water_entry_trace`.

The report supports a bounded event-local relation among the warning, manager
direction, tour sequencing, water entry, storm encounter, return attempt,
hatch flooding, rapid sinking, affected standing, and response. It does not
support one complete forecast-to-operation custody chain. Separate forecast,
company, manager, crew, captain, policy, vessel, inspection, passenger,
response, and Coast Guard objects are counterevidence to one universal weather
or operating mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the severe thunderstorm warning did not precede departure, that manager
direction did not change the normal tour sequence before water entry, or that
waves did not enter through the non-weathertight bow hatch and lead to
uncontrolled flooding. Reject any stronger chain that fills preserved receipt,
authority, reassessment, evacuation, correction, implementation, causal-weight,
or control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report or NTSB
investigation page changes a cited fact or boundary. Frontier retained the
candidate's bounded decision, seven ordered objects, selected supplied facts,
unknowns, and non-effect; repaired the standing-and-response row, incomplete
missing-link fragments, and non-operative falsifier; independently reconciled
`NTSB/MAR-20/01` through `SF-0031`; and authored source custody, authority
distinctions, counterevidence, correction, uncertainty, and non-promotion
boundaries.

Family lineage: `SF-LIN-STRETCHDUCK7-WARNING-WATERENTRY-PARTIAL-TRACE-01`.
