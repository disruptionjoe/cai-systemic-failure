---
record_id: SF-0001
status: source_backed_bounded_record
lane: "1"
claim_status: investigation_synthesis
created: 2026-07-18
sources_public: true
external_action: none
---

# SF-0001 - Boeing 737 MAX Certification Assumption Chain

## Boundary

This record is a bounded systemic-failure synthesis from public official
investigation material. It does not adjudicate liability, recreate the accident
sequence, assert aviation-specific expertise, or authorize an intervention. It
records a reusable failure pattern for CAI: safety-relevant assumptions can
drift across delegated, incremental, and human-factor-dependent review without
one owner holding the full contradiction.

## Sources

- National Transportation Safety Board, `ASR-19-01`, "Assumptions Used in the
  Safety Assessment Process and the Effects of Multiple Alerts and Indications
  on Pilot Performance", 2019:
  https://www.ntsb.gov/investigations/accidentreports/reports/asr1901.pdf
- Joint Authorities Technical Review, "Boeing 737 MAX Flight Control System:
  Observations, Findings, and Recommendations", submitted to FAA, 2019:
  https://www.faa.gov/sites/faa.gov/files/2021-08/Final_JATR_Submittal_to_FAA_Oct_2019.pdf
- U.S. House Committee on Transportation and Infrastructure, Boeing 737 MAX
  investigation page and final report:
  https://democrats-transportation.house.gov/committee-activity/boeing-737-max-investigation
  and
  https://democrats-transportation.house.gov/imo/media/doc/final_boeing_737_max_report1.pdf

Source posture: public government or regulator-hosted material. The repository
stores pointers and synthesis only; it does not copy the source artifacts.

## Failure Pattern

The public reports identify a certification and safety-assessment pattern in
which changed-product treatment, delegated review, design changes, human-factor
assumptions, and flight-deck alert complexity were not held together as one
integrated review object.

Mechanism fragments:

- Incremental change review can preserve discrete compliance while missing
  cumulative system integration and human-factor effects.
- A safety assessment can depend on assumed immediate or appropriate operator
  response without enough validation under realistic alert and workload
  conditions.
- Delegated or distributed approval can reduce visibility into changed function
  authority, inputs, limits, and interfaces unless the review artifact makes
  those changes unavoidable.
- Post-incident corrective data and interim risk actions can lag when the
  information-sharing route is not explicit enough.

## Affected Systems

- People aboard affected aircraft and their families.
- Flight crews and operators expected to absorb ambiguous or interacting
  system behavior.
- Regulators and delegated certification actors.
- Manufacturers and engineering organizations managing derivative products.
- International aviation authorities depending on shared safety information.

## Counterevidence And Limits

- This record relies on retrospective investigation and review reports, not on
  the complete source certification file.
- JATR explicitly reviewed a bounded certification and flight-control scope; it
  was not a complete review of every return-to-service or post-certification
  decision.
- This record does not decide motive, legal culpability, or the complete causal
  chain for either accident.
- Aviation-specific remedies belong to aviation safety authorities and domain
  experts, not this repository.

## Falsifiers

Revise or downgrade this record if official source material shows that the
load-bearing assumptions were fully validated under the relevant multi-alert
and workload conditions, that the changed function was reviewed as an
integrated aircraft-level object, or that a different mechanism better explains
the observed review failure.

## Correction Route

Corrections should preserve source provenance and identify the exact source,
revision, and claim being changed. Aviation-specific claims should route to
aviation safety authorities or public official records. Generic mechanism
questions route through `SFQ-0001`.

## Inquiry Route

This record opens `inquiries/SFQ-0001-assumption-validation-and-integrated-review.md`.
The inquiry asks whether a source-preserving assumption-drift register can force
integrated review without becoming a new authority or intervention.
