---
comparison_id: SF-PES-RAD-WATER-SPRAY-SAFEGUARD-CONTRAST
status: provisional_public_source_comparison
records: [SF-0021]
lane: "1"
created: 2026-09-01
source_material: public_official_report
external_action: none
---

# PES RAD / Water-Spray Safeguard Contrast

## Boundary

This comparison tests only the same-incident distinction between rapid acid
deinventory and water-spray vapor suppression in the Philadelphia Energy
Solutions refinery event. It preserves their different purposes, activation
paths, dependency states, timing, observed operation, and unresolved
protection effects.

It does not infer recurrence, one root cause, a shared authority, maintenance,
management, or remedy mechanism; accept a schema; assign blame or duty; create
receiver work; infer HF exposure, health causation, environmental effect, or
comparative remedy efficacy; or authorize external action.

## Source Set

- U.S. Chemical Safety and Hazard Investigation Board, *Philadelphia Energy
  Solutions (PES) Refinery Fire and Explosions*, final report, October 11,
  2022, especially pages 6-8 and 51-68:
  https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf
- Owner PES record
  `evidence/records/SF-0021-philadelphia-energy-solutions-hf-alkylation-boundaries.md`
  and timing trace
  `topology/SF-PES-HF-MITIGATION-TIMING-PARTIAL-TRACE-0001.md`.

The CSB final report controls. This artifact does not import later
implementation, individual medical conclusions, litigation, or third-party
accounts.

## Source-Local Contrast

| Safeguard object | Rapid acid deinventory | Water spray | Contrast boundary | Missing link |
| --- | --- | --- | --- | --- |
| purpose | Route HF inventory from the compromised unit to a separate drum after a loss-of-containment incident or other emergency. | Reduce airborne HF through vapor suppression using elevated water cannons. | Inventory transfer and airborne-vapor suppression are distinct protective functions. | Comparable design basis, performance denominator, and counterfactual effect remain incomplete. |
| activation path | A control-room operator activated RAD after ignition. | The control-room operator attempted remote pump start; a supervisor later reached the field pump and started it manually. | Operator command, remote control, field access, pump start, and spray delivery are separate objects. | Complete alarm custody, activation authority, escalation, and field-access exposure remain unknown. |
| dependency path | The report says RAD successfully drained about 339,000 pounds of HF to its separate drum. | Control-system communication failed at ignition and unit backup power failed nine seconds later, preventing remote operation. | Observed RAD transfer does not establish the condition of water-control communication, power, pumps, or piping. | Complete component condition, dependency topology, and alternate-control availability remain unknown. |
| ignition-time state | RAD was activated after the vapor cloud ignited; the report does not support treating it as already active at ignition. | Communication to the water pumps failed at ignition; this does not prove the pumps themselves were physically unavailable. | Activation time, control availability, physical equipment condition, and mitigation output must not be collapsed. | Exact equipment damage, command receipt, pump condition, and spray state remain incomplete. |
| observed operation | Activation successfully routed about 339,000 pounds of HF from the unit to the RAD drum. | The remote start did not work at about 4:12 a.m.; manual pump start at about 4:39 a.m. supplied the elevated cannons. | Successful inventory transfer and delayed water delivery are observed operations under different functions and clocks. | Remaining inventory, delivered water profile, and complete release chronology remain incomplete. |
| timing | The report places RAD activation after ignition but does not supply a common response-time denominator for comparison with water spray. | Remote start failed about ten minutes after ignition; manual start followed about 27 minutes later and roughly 37 minutes after ignition. | Event clocks support a sequence, not an efficacy ranking. | Decision-time information, feasible alternatives, and comparable response windows remain unknown. |
| protection effect | Actual RAD operation reduced unit HF inventory but does not prove complete counterfactual protection. | PES estimated bounded HF capture by water spray, but the report does not quantify the effect of earlier remote availability. | Observed operation, estimated capture, exposure, and counterfactual protection are different evidentiary objects. | Comparable denominators, exposure, health, environmental, and counterfactual protection effects remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `bounded_same_incident_active_safeguard_contrast`.

The report supports a bounded contrast between successful post-ignition RAD
deinventory and ignition-time loss of remote water-pump control followed by
later manual activation. Different purposes, activation paths, dependency
states, clocks, and effect evidence are counterevidence to one shared
safeguard, authority, maintenance, management, or remedy mechanism.

Withdraw the contrast if closer official-source review shows that the report
does not distinguish the two safeguards' functions or does not report both
successful RAD transfer and the failed-remote/later-manual water-pump
sequence. Narrow a row if source review changes a named quantity, time,
control state, or operation. Strengthen no comparative protection claim
without source-local condition, activation, exposure, denominator, and
counterfactual-effect evidence for both safeguards.

## Result

The comparison closes the prepared gate while keeping the two safeguards and
their evidence boundaries distinct. It creates no recurrence, shared
authority, maintenance, management, or remedy mechanism, schema pressure,
blame, duty, acceptance, receiver work, HF or health conclusion,
environmental conclusion, liability, or external action.

## Candidate Effect And Frontier Verification

BUILD ONE BOUNDED PES SAME-INCIDENT ACTIVE-SAFEGUARD CONTRAST - NO
RECURRENCE, SHARED AUTHORITY, MAINTENANCE, MANAGEMENT, OR REMEDY MECHANISM,
SCHEMA, BLAME, DUTY, ACCEPTANCE, RECEIVER-WORK, HF-OR-HEALTH CONCLUSION,
ENVIRONMENTAL CONCLUSION, LIABILITY, OR EXTERNAL-ACTION CHANGE

Frontier retained the candidate's bounded decision, seven-object structure,
and exact RAD and water-pump facts. It replaced collapsed activation and
ignition-time states, generic abbreviations, and the non-operative falsifier,
directly reviewed the controlling CSB report, and authored the source custody,
durable contrast, counterevidence, correction route, and no-promotion
boundary.

Family lineage: `SF-LIN-PES-RAD-WATER-SAFEGUARD-CONTRAST-01`.
