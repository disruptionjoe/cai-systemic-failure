---
comparison_id: SF-0001-CM1
status: provisional_comparison
record_id: SF-0001
lane: "1"
created: 2026-07-18
source_material: public_official_reports
external_action: none
---

# SF-0001 Causal Model Comparison

## Boundary

This comparison is a provisional topology aid for `SF-0001`. It compares
explanatory models and source-reported interventions using public official
material. It is not an aviation finding, liability judgment, remedy,
certification recommendation, or intervention plan.

No topology schema is accepted from this single record. Candidate fields below
must survive at least one additional source-backed record or absorber before
they become repository structure.

## Source Set

- NTSB `ASR-19-01`, "Assumptions Used in the Safety Assessment Process and the
  Effects of Multiple Alerts and Indications on Pilot Performance", 2019.
- Joint Authorities Technical Review, "Boeing 737 MAX Flight Control System:
  Observations, Findings, and Recommendations", 2019.
- U.S. House Committee on Transportation and Infrastructure, final Boeing 737
  MAX investigation report, 2020.

## Competing Models

| Model | What it explains | What it misses | Current fit |
|---|---|---|---|
| Human-response assumption drift | The safety case relied on timely, appropriate pilot response while the alert/workload environment changed. | Does not by itself explain why changed function details and delegated review visibility were fragmented. | Strong fit. Keep as one load-bearing model. |
| Changed-function integration failure | The changed function, input path, authority, limits, and interfaces were not held as one aircraft-level review object. | Needs the human-factor assumption model to explain why alert interaction mattered. | Strong fit. Pair with human-response drift. |
| Delegated review visibility failure | Distributed approval and document fragmentation made key changes easier to miss by accountable reviewers. | Does not by itself identify which assumptions were safety-critical. | Strong fit as a coordination mechanism, not a complete cause. |
| Organizational pressure and production incentives | Can explain persistence, under-escalation, and reluctance to widen review. | Requires additional careful sourcing before this repository can use it as a primary topology field. | Reserve as contextual pressure, not a core field yet. |
| Ordinary training/checklist deficit | Explains why procedure changes and training are tempting interventions. | Too narrow: source reports also point to design, safety-assessment assumptions, alert clarity, changed-function visibility, and delegated review. | Absorber only. Do not let it collapse the record. |

## Prior Interventions And Recommendations

| Intervention class | Source-reported example | Mechanism tested | Topology implication |
|---|---|---|---|
| Procedure update | FAA emergency AFM revision after Lion Air expanded runaway-stabilizer guidance for erroneous AOA input. | Late symptom recognition and response. | Useful but downstream; does not force earlier contradiction visibility. |
| Safety-assessment revalidation | NTSB recommendations A-19-10 and A-19-11 ask that pilot-response assumptions consider all possible flight-deck alerts and indications. | Human-response assumption validation. | Supports `assumption`, `environment`, and `validation burden` fields. |
| Human-factors tool development | NTSB recommendations A-19-13 and A-19-14 ask for tools/methods and documentation for validating pilot recognition and response assumptions. | Repeatable validation method. | Supports a `validation method` field rather than free text. |
| Alert diagnostic standards | NTSB recommendations A-19-15 and A-19-16 concern prioritization and clarity of failure indications. | Signal clarity under multiple indications. | Supports an `alert/interface interaction` field. |
| Certification visibility standards | JATR R4.2 through R4.6 address clarity, consistency, early coordination, fragmented descriptions, functional-change highlighting, and records of agreements. | Changed-function visibility and review timing. | Supports `change event`, `visibility owner`, and `integrated review trigger` fields. |
| Delegation pressure review | JATR observations and recommendations on ODA environment and FAA communication address delegated authority pressure and visibility. | Delegated review integrity. | Supports `review owner`, `delegation path`, and `pressure/counterevidence` fields, but only when sourced. |

## Provisional Topology Fields

These are candidate fields only:

- assumption identifier and source revision;
- assumption owner and accountable review owner;
- affected system and affected-party standing;
- change event or changed input/function path;
- validation method and validation burden;
- alert, interface, workload, or environment interaction;
- delegation path and visibility gap;
- counterevidence or absorber model;
- correction route and stop condition.

## Inquiry Refinement

`SFQ-0001` should ask mechanism design to test not only whether a register can
store assumptions, but whether it can keep three contradictions visible:

1. a changed function or input path changes the validation burden;
2. human-response assumptions become unvalidated under a changed alert or
   workload environment; and
3. delegated review can see the contradiction without a central owner silently
   absorbing domain authority.

If a candidate mechanism cannot distinguish these from an ordinary completed
checklist, it should be revised or killed.

