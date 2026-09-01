---
trace_id: SF-PES-HF-MITIGATION-TIMING-PARTIAL-TRACE-0001
status: provisional_partial_trace
subject: pes_hf_mitigation_control_timing
disposition: partial_trace_only
claim_posture: provisional
source_material: SF-0021
external_action: none
---

# PES HF-Mitigation Control-Timing Partial Trace

## Boundary

This artifact preserves only the rapid-acid-deinventory, ignition, control-
communication, backup-power, remote-command, field-access, manual-activation,
and mitigation-effect sequence supported by the bounded PES record and direct
review of the CSB final report. It does not reconstruct complete alarm custody,
component damage, command authority, field-access exposure, implementation,
comparative mitigation effect, recurrence, blame, duty, remedy efficacy,
receiver work, health causation, environmental effect, or external action.

## Source Custody

- U.S. Chemical Safety and Hazard Investigation Board, *Philadelphia Energy
  Solutions (PES) Refinery Fire and Explosions*, final report, released
  October 11, 2022:
  https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf
- Owner source record:
  `evidence/records/SF-0021-philadelphia-energy-solutions-hf-alkylation-boundaries.md`.

The final report controls. The event timing is reviewed at report pages 6-8
and 15-24; safeguard reliability and historical control context at pages
51-68.

## Partial Trace Ledger

| Time or object | Supported official-source fact | Control distinction | Missing link |
| --- | --- | --- | --- |
| RAD action | After ignition, workers activated the rapid acid deinventory system and routed about 339,000 pounds of HF from the compromised unit to a separate drum. | Inventory transfer, release-rate reduction, residual inventory, activation, and protection effect are distinct. | Complete activation authority, response time, remaining inventory, and counterfactual effect remain incomplete. |
| 4:02:06 ignition | The vapor cloud ignited at 4:02:06 a.m. | Ignition is distinct from the earlier release, later equipment damage, command attempts, and mitigation response. | Complete ignition source, flame and overpressure propagation, and moment-by-moment equipment state remain incomplete. |
| 4:02:06 communication failure | Plant data show that control-system communication to the water pumps failed at ignition; the report says flame and overpressure likely damaged control equipment and wiring. | Loss of control communication, physical damage, pump availability, and water delivery are separate states. | Exact component-level damage, alarm receipt, and alternate control availability remain incomplete. |
| 4:02:15 backup-power failure | The unit's uninterruptible power supply failed nine seconds after ignition. | Backup-power loss is distinct from primary communication loss, pump condition, command authority, and field access. | Complete dependency topology, causal sequence, alarm custody, and feasible bypass remain unknown. |
| 4:12 remote attempt | At about 4:12 a.m., the control-room operator tried to start the water pumps remotely, but they did not start. | Command issue, signal transmission, power availability, pump response, and water discharge are not interchangeable. | Complete operator information, alarm state, command receipt, failure diagnosis, and escalation path remain unknown. |
| 4:39 manual activation | At about 4:39 a.m., a shift supervisor wearing firefighting protective gear manually started the pump supplying the elevated water cannons. | Field access, protective equipment, manual actuation, pump start, spray availability, and exposure are distinct. | Complete command authority, access risk, route, water delivery, exposure, and effect remain unknown. |
| mitigation-effect boundary | The system was designed to reduce airborne HF through vapor suppression; the report estimates bounded HF release and water-spray capture but does not quantify the counterfactual protection effect of earlier activation. | Design intent, actual availability, later operation, estimated capture, offsite-impact evidence, and remedy efficacy are distinct. | Comparative release, exposure, health, environmental, and protection effects remain unknown. |

## Disposition

`partial_trace_only`. The report supports the bounded control-timing sequence,
but not a complete alarm-to-authority-to-mitigation-effect chain. Event timing
does not establish the counterfactual result of earlier water-spray activation.

## Counterevidence And Domain Absorbers

HF release physics, process control, electrical and instrument reliability,
fire and explosion analysis, emergency operations, industrial hygiene, public
health, regulation, and legal accounts remain sovereign. Successful RAD
activation, failed remote water control, later manual pump activation, bounded
capture estimates, and incomplete exposure evidence are counterevidence to one
generalized safeguard, authority, or remedy mechanism.

## Falsifier And Correction Route

Narrow or withdraw this trace if closer official-source review changes a
named time, control state, RAD quantity, remote attempt, manual activation, or
mitigation boundary. Do not strengthen it unless source-local evidence
independently supplies the missing alarm custody, accountable authority,
component condition, field exposure, implementation, and comparative control-
effect links. Corrections route through this artifact, `SF-0021`, and
dependent summaries; no receiver or external action is created.

## Candidate Effect

BUILD ONE BOUNDED PES HF-MITIGATION CONTROL-TIMING PARTIAL TRACE - NO
RECURRENCE, SHARED AUTHORITY MECHANISM, SCHEMA, BLAME, DUTY, REMEDY,
ACCEPTANCE, RECEIVER-WORK, HF-OR-HEALTH CONCLUSION, ENVIRONMENTAL CONCLUSION,
LIABILITY, OR EXTERNAL-ACTION CHANGE

## Frontier Verification

Frontier retained the candidate's opening decision and seven-row timing
skeleton. It replaced the unknown-as-falsifier error, independently verified
the CSB timing and control facts, and authored the source-local relations,
missing-link boundaries, counterevidence, domain absorbers, correction route,
and durable artifact structure.

Family lineage: `SF-LIN-PES-HF-MITIGATION-CONTROL-TIMING-01`.
