---
trace_id: SF-CAPECO-OVERFILL-SIGNAL-STOP-PARTIAL-TRACE-0001
status: provisional_partial_trace
subject: capeco_overfill_signal_to_stop
disposition: partial_trace_only
claim_posture: provisional
source_material: SF-0016
external_action: none
---

# CAPECO Overfill Signal-To-Stop Partial Trace

## Boundary

This artifact preserves only the transfer, level-evidence, alarm, automatic-
control, detection, and stop sequence supported by the bounded CAPECO record
and direct review of CSB Investigation Report `2010-02-I-PR`. It does not
reconstruct complete knowledge, custody, accountable receipt, authority,
disposition, stop status, implementation, ignition, one root cause,
recurrence, schema fit, blame, duty, remedy efficacy, receiver work, or
external action.

## Source Custody

- U.S. Chemical Safety and Hazard Investigation Board, *Caribbean Petroleum
  Tank Terminal Explosion and Multiple Tank Fires*, Investigation Report
  `2010-02-I-PR`, Final Report, October 2015:
  https://www.csb.gov/assets/1/20/capeco_final_report__10.21.2015.pdf
- Owner source record: `evidence/records/SF-0016-capeco-overfill-protection-and-community-boundaries.md`.

The final report controls. The transfer and operator sequence is reviewed at
report pages 15-24; the overflow estimate at page 25; the unreliable gauging
and transmitter evidence at pages 19-21 and 38-42; the independent alarm and
automatic-overfill findings at pages 42-43 and 75-81; and the report's
termination definition at page 17.

## Partial Trace Ledger

| Layer | Supported official-source fact | Boundary | Missing link |
| --- | --- | --- | --- |
| transfer allocation | A shipload was distributed among four tanks over more than 24 hours; remaining flow was later directed to tanks 409 and 411. | Transfer planning, valve position, tank capacity, and level knowledge are separate objects. | Complete calculations, shift handoffs, valve chronology, individual knowledge, and authority remain incomplete. |
| level evidence | Float-and-tape gauges supplied tank readings; operators normally recorded hourly values, and tank 409's transmitter was not sending data to the computer that night. | Manual reading, side-gauge condition, transmitter availability, computer display, and fill-time calculation are not interchangeable. | Every reading, calculation, interpretation, and receipt remains unknown. |
| instrument condition | CAPECO instruments were poorly maintained and frequently failed; operators often did not rely on the computer display. | Reliability evidence does not prove what each operator knew or what one functioning instrument would have changed. | Complete maintenance history, failure chronology, reliance, and counterfactual effect remain unknown. |
| independent alarm | Tank 409 had no independent high-level alarm. | Absence of an independent alarm is distinct from primary gauging, operator checks, and automatic flow control. | Complete design history, feasible alarm response, accountable receipt, and implementation remain unknown. |
| automatic flow control | CAPECO had no independent automatic system able to terminate or divert incoming product before overfill. | Missing automatic termination does not establish one sufficient remedy or one accountable authority. | Complete risk assessment, design decision, feasible intervention, implementation, and protection effect remain unknown. |
| overflow and detection | Tank 409 overflowed for an estimated 26 minutes, releasing about 193,974 gallons; operators observed a vapor cloud near midnight and contacted the dock operator to halt flow. | Physical overflow, operator observation, notification, actual flow termination, ignition, and later emergency response remain separate. | Exact awareness time, message receipt, termination timing, remaining inflow, and causal effect remain incomplete. |
| stop-chain decision | The report defines transfer termination as shutdown or diversion and documents both the missing automatic layer and a later manual halt request. | A requested halt plus a design-level missing safeguard is not a complete custody-to-authority-to-effect chain. | Accountable receipt, authority, disposition, verified stop status, implementation, and counterfactual control effect remain unknown. |

## Disposition

`partial_trace_only`. The report supports a bounded signal-to-stop sequence,
but not a complete knowledge-to-authority-to-effect chain. Adjacency, job
titles, recommendations, and hindsight cannot fill the missing links.

## Counterevidence And Domain Absorbers

Marine transfer, terminal operations, tank instrumentation, process control,
maintenance, human factors, fire protection, emergency response, environmental
science, standards, regulation, and legal accounts remain sovereign. Several
interacting conditions are counterevidence to one generalized information or
authority mechanism. Recommendations are investigative judgment, not proof of
implementation or efficacy.

## Falsifier And Correction Route

Narrow or withdraw this trace if closer official-source review changes a named
event, instrument state, timing, termination fact, or control boundary. Do not
strengthen it unless source-local evidence independently supplies the missing
knowledge, custody, accountable receipt, authority, disposition, verified
stop, implementation, and control-effect links. Corrections route through this
artifact, `SF-0016`, and dependent summaries; no receiver or external action
is created.

## Candidate Effect

BUILD ONE BOUNDED CAPECO SIGNAL-TO-STOP PARTIAL TRACE - NO RECURRENCE, SHARED
MECHANISM, SCHEMA, REMEDY, ACCEPTANCE, RECEIVER-WORK, HEALTH-OR-ENVIRONMENTAL
CONCLUSION, LIABILITY, OR EXTERNAL-ACTION CHANGE

## Frontier Verification

Frontier retained the candidate's partial-trace decision and seven-layer
separation, corrected its generic boundary and unknown cells, independently
reviewed CSB `2010-02-I-PR`, and authored the page-local source custody,
evidence relations, stop-request boundary, missing-link limits,
counterevidence, falsifier, correction route, and no-promotion boundary.

Family lineage: `SF-LIN-CAPECO-OVERFILL-SIGNAL-STOP-TRACE-01`.
