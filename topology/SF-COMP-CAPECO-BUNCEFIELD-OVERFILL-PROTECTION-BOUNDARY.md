---
comparison_id: SF-COMP-CAPECO-BUNCEFIELD-OVERFILL-PROTECTION-BOUNDARY
status: provisional_public_source_comparison
records: [SF-0016, Buncefield-2005]
lane: "1"
created: 2026-09-01
source_material: public_official_reports
external_action: none
---

# CAPECO / Buncefield Overfill-Protection Boundary

## Boundary

This comparison tests only the source-local relation between the CAPECO and
Buncefield gasoline-tank overfills described in CSB Investigation Report
`2010-02-I-PR`. It preserves the difference between absent safeguards at
CAPECO and installed but inoperable safeguards at Buncefield, together with
their different regulatory treatment.

It does not equate the incidents; infer one root cause, recurrence, complete
custody, authority, disposition, implementation, or relative causal weight;
accept a schema; assign blame or duty; prescribe a remedy; create receiver
work; or authorize external action.

## Source Set

- U.S. Chemical Safety and Hazard Investigation Board, *Caribbean Petroleum
  Tank Terminal Explosion and Multiple Tank Fires*, Investigation Report
  `2010-02-I-PR`, Final Report, October 2015, especially sections 7.2-7.3 and
  Table 2 on report pages 51-55:
  https://www.csb.gov/assets/1/20/capeco_final_report__10.21.2015.pdf
- U.K. Health and Safety Executive, Environment Agency, and Buncefield Major
  Incident Investigation Board, Buncefield investigation and report index:
  https://www.hse.gov.uk/comah/buncefield/index.htm
- Owner CAPECO record:
  `evidence/records/SF-0016-capeco-overfill-protection-and-community-boundaries.md`.

The CSB report controls this bounded comparison. The HSE investigation index
corroborates the Buncefield incident and source family; this artifact does not
import later implementation, enforcement, litigation, or remedy-effect claims.

## Source-Local Comparison

| Dimension | CAPECO | Buncefield | Comparison boundary |
| --- | --- | --- | --- |
| event residue | Gasoline tank 409 overflowed, a vapor cloud exploded, and multiple tanks burned. | Gasoline tank 912 overflowed, a vapor cloud exploded, and multiple tanks burned. | The shared event class supports comparison but does not by itself establish recurrence or one causal mechanism. |
| primary gauging | Manual tank gauging failed to provide reliable level control during the transfer. | A remotely supervised automated level-control system failed. | Manual and automated primary controls are different operating objects even though neither controlled the overfill. |
| independent alarm | No independent high-level alarm or redundant alarm was present. | An independent high-level switch and redundant alarm protection were present but not functioning. | Safeguard absence and safeguard unavailability are materially different failure states. |
| automatic termination | CAPECO had no independent automatic overfill-prevention system able to shut down or divert flow. | The installed independent automatic overfill-protection function did not operate. | Missing automatic termination and failed installed termination cannot be treated as the same design, maintenance, testing, or response chain. |
| regulatory posture | The compared U.S. regime did not treat CAPECO as a high-hazard facility subject to the stronger process-safety treatment discussed by the CSB. | Buncefield was treated as a high-hazard facility under the U.K. COMAH framework. | Different regulatory classification did not prevent severe outcomes and does not prove equivalent oversight, implementation, or efficacy. |
| recurrence gate | CAPECO supplies failed primary gauging plus absent independent alarm and termination layers. | Buncefield supplies failed primary gauging plus present-but-inoperable independent alarm and termination layers. | The bounded relation is failed functional overfill protection across different layer configurations; a recurring management, authority, maintenance, regulatory, or remedy mechanism remains unproved. |

## Decision, Counterevidence, And Falsifier

Decision: `bounded_overfill_protection_relation`.

The two incidents support a bounded relation at the event-and-protection-layer
level: a gasoline tank overfilled after primary level control failed and no
functional independent layer stopped transfer. CAPECO's missing layers,
Buncefield's inoperable installed layers, and their different regulatory
postures are counterevidence to collapsing that relation into one mechanism,
recurrence claim, authority failure, or remedy conclusion.

Withdraw the relation if closer official-source review shows that either event
did not combine gasoline-tank overfill, failed primary level control, and the
absence of a functioning independent termination layer. Narrow either side if
source review changes a named safeguard state, event fact, or regulatory
boundary. Strengthen no mechanism claim without complete source-local design,
maintenance, test, custody, authority, disposition, and control-effect chains
for both incidents.

## Result

The comparison closes the prepared gate with one source-preserving bounded
relation and explicit configuration differences. It creates no recurrence,
shared management or authority mechanism, schema pressure, blame, duty,
remedy, acceptance, receiver work, or external action.

## Candidate Effect And Frontier Verification

BUILD ONE BOUNDED CAPECO / BUNCEFIELD OVERFILL-PROTECTION COMPARISON - NO
RECURRENCE, SHARED MANAGEMENT OR AUTHORITY MECHANISM, SCHEMA, REMEDY,
ACCEPTANCE, RECEIVER-WORK, LIABILITY, OR EXTERNAL-ACTION CHANGE

Frontier retained the candidate's six-row control-layer separation, replaced
its non-operative decision and falsifier, directly reviewed the controlling
CSB comparison, and authored the source custody, evidence relations,
configuration boundaries, counterevidence, falsifier, correction route, and
no-promotion boundary.

Family lineage: `SF-LIN-COMP-CAPECO-BUNCEFIELD-OVERFILL-PROTECTION-01`.
