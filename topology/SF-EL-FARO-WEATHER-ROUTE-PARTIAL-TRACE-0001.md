---
trace_id: SF-EL-FARO-WEATHER-ROUTE-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0024]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# El Faro Weather-Information-To-Route-Decision Partial Trace

## Boundary

This trace preserves only the source-local relation among weather-product
delivery, captain use, officer suggestions, route decision, bridge resource
management, and company oversight in `NTSB/MAR-17/01` and `SF-0024`.

It does not reconstruct complete weather custody, bridge-team access,
officer-to-captain review, shoreside receipt, company disposition, route
alternatives, implementation, relative causal weight, or control effect. It
does not infer one weather-information, captain, bridge, company, vessel, or
maritime-safety mechanism; recurrence; blame; duty; liability; remedy efficacy;
schema fit; receiver work; or external action.

## Source Set

- National Transportation Safety Board, *Sinking of US Cargo Vessel SS El
  Faro*, Marine Accident Report `NTSB/MAR-17/01`, reissued September 7, 2018,
  executive-summary page xiii, report sections 2.5-2.8, and page 247:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/MAR1701.pdf
- Bounded owner record `SF-0024`.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| weather information | BVS weather files were sent on a six-hour cycle to the captain's email address; one file downloaded at 0608 had been available at 0504. NTSB separately identified failure to use the most current weather information. | Product production, delivery availability, captain download, interpretation, and decision use are separate objects. | Complete product set, bridge-team access, selection rationale, and decision-time comparison remain incomplete. |
| bridge access | The record documents weather equipment and information available aboard, but does not establish one complete bridge-wide custody path for every product. | Captain email receipt, bridge equipment access, and officer access are not interchangeable. | Which officers accessed which product at each decision point remains incomplete. |
| officer observation | NTSB found ineffective bridge resource management, including inadequate consideration of officers' suggestions. | Officer observation and suggestion remain distinct from captain review and final command. | Complete wording, timing, custody, escalation, and response for every suggestion are not reconstructed. |
| captain review | The captain discussed the storm and BVS information with the chief mate and retained final route authority. | Review of weather and officer input is distinct from accepting, rejecting, or implementing a route alternative. | Complete review rationale and disposition of each suggestion remain incomplete. |
| route decision | NTSB identified insufficient action to avoid Hurricane Joaquin as part of the probable cause. | Route planning, route change, storm avoidance, command authority, and vessel-state response remain separate. | Complete alternative set, timing, implementation sequence, and relative effect remain incomplete. |
| shoreside receipt | NTSB separately identified company oversight and safety-management deficiencies. | Shoreside oversight is distinct from onboard weather receipt and captain command. | Complete shoreside receipt of voyage-specific weather or officer concerns is not established here. |
| company disposition | TOTE oversight and safety management are source-backed objects, not proof of one voyage-specific company decision chain. | Company policy, training, oversight, receipt, and disposition remain separate. | Complete accountable recipient, review, disposition, and implementation remain unknown. |
| implementation and control effect | The vessel continued on the selected route into worsening conditions; NTSB identified multiple causal and contributing factors. | Route execution and observed outcome do not establish the counterfactual effect of another route or one omitted control. | Complete implementation custody, alternative-route effect, relative causal weight, and control effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `preserve_partial_weather_to_route_trace`.

The source set supports a partial relation from weather delivery and officer
input to captain review and route decision, while refusing a complete bridge-
or-shoreside custody chain. Multiple distinct weather products, final captain
authority, incomplete officer-input custody, separate company oversight, and
the report's other vessel and emergency factors are counterevidence to one
complete information-to-control mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the cited BVS delivery, officer-suggestion, captain-use, or route-decision
fact is absent or materially different. Reject any stronger chain that depends
on filling the preserved custody, authority, disposition, implementation, or
control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes
a cited fact or boundary. Frontier retained the candidate's bounded
insufficiency decision and ordered objects; replaced repeated generic unknowns
and the non-operative falsifier; independently reviewed the official report;
and authored the source custody, row-local links, counterevidence, correction
route, and non-promotion boundary.

Family lineage: `SF-LIN-EL-FARO-WEATHER-ROUTE-PARTIAL-TRACE-01`.
