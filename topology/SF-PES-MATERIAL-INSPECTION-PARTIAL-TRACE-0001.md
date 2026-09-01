---
trace_id: SF-PES-MATERIAL-INSPECTION-PARTIAL-TRACE-0001
status: provisional_partial_trace
subject: pes_material_knowledge_to_inspection
disposition: partial_trace_only
claim_posture: provisional
source_material: SF-0021
external_action: none
---

# PES Material-Knowledge-To-Inspection Partial Trace

## Boundary

This artifact preserves only the material, damage, published-knowledge,
inspection-coverage, and later-standard sequence supported by the bounded PES
record and direct review of the CSB final report. It does not reconstruct
complete knowledge custody, decision-time review, inspection selection,
authority, disposition, implementation, control effect, recurrence, one root
cause, blame, duty, remedy efficacy, receiver work, or external action.

## Source Custody

- U.S. Chemical Safety and Hazard Investigation Board, *Philadelphia Energy
  Solutions (PES) Refinery Fire and Explosions*, final report, released
  October 11, 2022:
  https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf
- Owner source record:
  `evidence/records/SF-0021-philadelphia-energy-solutions-hf-alkylation-boundaries.md`.

The final report controls. The component and metallurgical evidence is
reviewed at report pages 24-44, the industry-knowledge and existing-equipment
discussion at pages 44-46, and the later inspection requirement at pages
76-78.

## Partial Trace Ledger

| Trace object | Supported official-source fact | Distinction | Missing link |
| --- | --- | --- | --- |
| material object | The failed carbon-steel elbow was installed around 1973 and contained much higher nickel and copper concentrations than adjacent components. | Component identity, material specification, measured composition, and later interpretation are separate objects. | Complete manufacturing, installation, inventory, and later identification custody remain unknown. |
| damage evidence | HF corrosion reduced the elbow from an original 0.322-inch thickness to a minimum measured 0.011 inch, while adjacent lower-residual-element components had not corroded as quickly. | Differential damage supports a material-specific relation without proving every decision, inspection, or counterfactual control. | Complete degradation chronology, every measurement, and the relative causal weight of other conditions remain incomplete. |
| published knowledge | A 2003 NACE paper quantified nickel and copper levels considered safe for HF alkylation service; ASTM and API guidance later incorporated related limits. | Research, standard revision, owner receipt, equipment inventory, and operating disposition are not interchangeable. | Who received, reviewed, translated, or rejected each change for the installed elbow is not reconstructed. |
| pre-incident inspection coverage | API RP 751, Sunoco, and PES did not ensure inspection of every existing carbon-steel component after the knowledge changed; Sunoco and PES had never inspected all such components in the HF unit. | Partial inspection coverage is distinct from knowledge custody, component selection, technique adequacy, and safe-operation judgment. | The complete selection rule, accountable authority, exclusions, alternatives, and closure evidence remain unknown. |
| decision-time translation | The report connects changed industry knowledge to the need to evaluate equipment built before that knowledge, but it does not supply a complete elbow-specific custody-to-decision chain. | A source-backed knowledge-to-coverage gap is not a complete review, authority, disposition, implementation, or effect chain. | Decision-time receipt, accountable review, component-level disposition, implementation, and verified control effect remain unknown. |
| later standard change | The post-incident API RP 751 revision added special-emphasis inspection of individual carbon-steel components and welds in identified corrosion zones. | Later investigative and standard response does not prove earlier duty, later implementation, or remedy efficacy. | Complete recipient custody, implementation, audit, sustained effect, and correction closure remain unknown. |

## Disposition

`partial_trace_only`. The report supports a bounded relation among material
composition, differential corrosion, published industry knowledge, incomplete
existing-component inspection, and later standard change. It does not support
a complete knowledge-to-authority-to-control-effect chain.

## Counterevidence And Domain Absorbers

HF corrosion science, metallurgy, materials standards, mechanical integrity,
inspection engineering, alkylation operations, regulation, management, and
legal accounts remain sovereign. The elbow's installation era, later research,
multiple standards bodies, partial inspection, accelerated damage, and later
recommendation objects are counterevidence to one generalized information or
authority mechanism. Later standards are not proof of implementation or
efficacy.

## Falsifier And Correction Route

Narrow or withdraw this trace if closer official-source review changes a
named material, thickness, differential-corrosion, guidance, inspection-
coverage, or later-standard fact. Do not strengthen it unless source-local
evidence independently supplies the missing custody, accountable receipt,
decision-time authority, disposition, implementation, and control-effect
links. Corrections route through this artifact, `SF-0021`, and dependent
summaries; no receiver or external action is created.

## Candidate Effect

BUILD ONE BOUNDED PES MATERIAL-TO-INSPECTION PARTIAL TRACE - NO RECURRENCE,
SHARED AUTHORITY MECHANISM, SCHEMA, BLAME, DUTY, REMEDY, ACCEPTANCE,
RECEIVER-WORK, HF-OR-HEALTH CONCLUSION, ENVIRONMENTAL CONCLUSION, LIABILITY,
OR EXTERNAL-ACTION CHANGE

## Frontier Verification

Frontier retained the candidate's six-object separation but not its
`current_facts_insufficient` decision or non-operative falsifier. Direct review
of the CSB report supports a bounded partial trace. Frontier authored the
source-local relations, decision-time boundary, counterevidence, domain
absorbers, operative correction condition, and durable artifact structure.

Family lineage: `SF-LIN-PES-MATERIAL-INSPECTION-TRACE-01`.
