---
comparison_id: SF-COMP-PES-MARATHON-CITGO-HF-SAFEGUARD-AVAILABILITY-BOUNDARY
status: provisional_public_source_comparison
records: [SF-0021, Marathon-Texas-City-1987, CITGO-Corpus-Christi-2009]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# PES / Marathon / CITGO HF Safeguard-Availability Boundary

## Boundary

This comparison tests only the cross-incident active-water-mitigation evidence
assembled in the PES CSB final report. Marathon's sprinkler was damaged by the
initiating crane event, CITGO nearly exhausted stored water and experienced
failures while establishing supplemental supply, and PES lost remote water-
pump control before later manual activation.

It does not equate the incidents; infer recurrence, one root cause, a shared
maintenance, supply, activation, authority, management, or remedy mechanism;
accept a schema; assign blame or duty; create receiver work; infer exposure or
health causation; or authorize external action.

## Source Set

- U.S. Chemical Safety and Hazard Investigation Board, *Philadelphia Energy
  Solutions (PES) Refinery Fire and Explosions*, final report, October 11,
  2022, especially report pages 51-62:
  https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf
- Owner PES record
  `evidence/records/SF-0021-philadelphia-energy-solutions-hf-alkylation-boundaries.md`
  and control-timing trace
  `topology/SF-PES-HF-MITIGATION-TIMING-PARTIAL-TRACE-0001.md`.

The PES final report controls this comparison and is itself the source of the
Marathon and CITGO historical summaries. This artifact does not independently
reconstruct those incidents or import later implementation, litigation,
individual medical conclusions, or third-party material.

## Source-Local Comparison

| Comparison object | Marathon Texas City | CITGO Corpus Christi | PES | Shared residue or boundary |
| --- | --- | --- | --- | --- |
| initiating event | During turnaround, an overloaded crane tipped and dropped equipment onto an HF vessel, severing lines. | A hydrocarbon-gas release caused a multi-day fire and multiple failures in the HF alkylation unit. | An HF-corroded elbow ruptured; the released vapor cloud ignited and the event escalated through fire and explosions. | The initiating mechanisms, equipment, inventories, and escalation paths differ. |
| water-system state | A sprinkler designed to control an HF release was damaged by the crane. | Stored fire-suppression and HF-mitigation water was nearly exhausted on the first day while HF continued to release. | Ignition-time flame and overpressure likely damaged water-pump control equipment and wiring. | Each report fragment contains compromised water-mitigation availability, but physical damage, stored-supply depletion, and control loss are distinct states. |
| activation or supply path | The source summary establishes damaged sprinkler equipment but not a complete activation, alternate-supply, or control path. | A firefighting barge began transferring saltwater about 11.5 hours after release; hoses ruptured and two pump engines failed. | Remote pump start failed at about 4:12 a.m.; a supervisor manually started the supplying pump at about 4:39 a.m. | Activation, primary supply, supplemental supply, field access, and manual control are not interchangeable. |
| duration or timing | The source summary supplies the release and consequence boundary but not a comparable mitigation-response timeline. | Fire and HF release continued across a multi-day response; stored water pressure emerged on day one. | Remote-control loss occurred at ignition and manual activation followed about 37 minutes later. | The report does not supply comparable denominators, event clocks, or response windows across all three cases. |
| capture evidence | About 30,000 to 53,000 pounds of HF were released; the summary does not provide a comparable water-capture estimate. | CITGO reported about 42,000 pounds captured and 30 pounds uncaptured; CSB disputed that estimate and calculated about 4,000 pounds likely uncaptured. | PES estimated 1,968 pounds captured by water spray and 3,271 pounds not captured, within a different release and system context. | Reported release and capture quantities use different evidence, contexts, and uncertainty and cannot establish comparative protection effect. |
| standing and consequences | About 4,000 people were evacuated, more than 1,000 residents went to hospitals with reported irritation or burns, and wildlife and vegetation were harmed. | The bounded report section centers fire, HF release, water supply, transfer failures, audit, and recommendation objects; complete standing is not reconstructed here. | Five workers and one firefighter had minor injuries; the CSB was unaware of offsite impacts from the HF release. | Standing, exposure, consequence, and health-causation evidence differ and remain case-local. |
| authority and disposition | Complete design, inspection, activation, response, authority, and later implementation remain outside the source summary. | The CSB found no recommended API RP 751 safety audit and issued urgent water-supply and audit recommendations; implementation and effect are not imported. | Complete alarm custody, command authority, field-access risk, disposition, implementation, and effect remain incomplete. | No shared custody, authority, maintenance, management, or correction chain is established. |
| comparative protection effect | The damaged sprinkler did not establish a comparable counterfactual mitigation effect. | Disputed capture estimates and supply failures prevent a stable comparative effect estimate. | Later manual activation and bounded capture estimates do not quantify the effect of earlier availability. | The report supports an availability relation, not recurrence, efficacy ranking, or a shared remedy mechanism. |

## Decision, Counterevidence, And Falsifier

Decision: `bounded_active_water_mitigation_availability_relation`.

The PES report supports a bounded cross-incident relation: water-spray
mitigation was damaged or experienced availability problems in all three
events. The different initiating events, damage states, supply and activation
paths, durations, estimates, standing, and unresolved authority chains are
counterevidence to one shared causal, maintenance, management, or remedy
mechanism.

Withdraw the relation if closer review of the controlling report shows that
it does not identify water-spray damage or availability problems in any one of
the three incidents. Narrow a case if source review changes a named event,
water-system, timing, capture, standing, or recommendation fact. Strengthen no
mechanism or protection-effect claim without comparable source-local system
condition, activation, supply, maintenance, authority, denominator, exposure,
and effect evidence across all three cases.

## Result

The comparison closes the prepared gate with one bounded availability
relation and explicit event separation. It creates no recurrence, shared
maintenance, management, supply, activation, or authority mechanism, schema
pressure, blame, duty, remedy, acceptance, receiver work, HF or health
conclusion, environmental conclusion, liability, or external action.

## Candidate Effect And Frontier Verification

BUILD ONE BOUNDED PES / MARATHON / CITGO HF SAFEGUARD-AVAILABILITY
COMPARISON - NO RECURRENCE, SHARED MAINTENANCE, MANAGEMENT, SUPPLY,
ACTIVATION, OR AUTHORITY MECHANISM, SCHEMA, REMEDY, ACCEPTANCE,
RECEIVER-WORK, HF-OR-HEALTH CONCLUSION, ENVIRONMENTAL CONCLUSION, LIABILITY,
OR EXTERNAL-ACTION CHANGE

Frontier retained the candidate's cross-incident event and safeguard skeleton
plus exact supplied facts, replaced its unselected decision, blank cells, and
non-operative falsifier, directly reviewed the controlling PES report, and
authored the source custody, bounded relation, counterevidence, correction
route, and no-promotion boundary.

Family lineage: `SF-LIN-PES-HF-ACTIVE-SAFEGUARD-CROSS-INCIDENT-01`.
