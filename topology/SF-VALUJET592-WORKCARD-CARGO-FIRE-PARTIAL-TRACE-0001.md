---
trace_id: SF-VALUJET592-WORKCARD-CARGO-FIRE-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0033]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# ValuJet Flight 592 Work-Card-To-Cargo-Fire Partial Trace

## Boundary

This trace preserves only the source-local relation from chemical-oxygen-
generator removal and work-card signoff through safety-cap state, packaging
and identification, contractor-to-carrier custody, cargo loading, generator
activation and fire, cargo protection, flight-crew response, oversight,
affected standing, and consequence in `NTSB/AAR-97/06` and `SF-0033`.

It does not reconstruct generator-by-generator custody, individual knowledge,
accountable receipt, the exact packaging and loading sequence, fire and
warning chronology, oversight chronology, correction, implementation,
relative causal weight, or verified control effect; infer recurrence or one
oxygen-generator, maintenance, work-card, signoff, hazardous-material, cargo-
fire, protection, contractor, carrier, certification, surveillance,
regulatory, or affected-party mechanism; or create blame beyond NTSB findings,
duty, remedy, acceptance, receiver work, health causation, liability, or
external action.

## Source Set

- National Transportation Safety Board, *In-Flight Fire and Impact with
  Terrain, ValuJet Airlines Flight 592, DC-9-32, N904VJ, Everglades, Near
  Miami, Florida, May 11, 1996*, Aircraft Accident Report `NTSB/AAR-97/06`,
  executive summary, sections 1.1.2, 1.6.3, 1.17, 2.2, 2.6, 2.8, findings,
  probable cause, and recommendations:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/AAR9706.pdf
- NTSB investigation page `DCA96MA054`:
  https://www.ntsb.gov/investigations/Pages/DCA96MA054.aspx
- Bounded owner record `SF-0033`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| component removal | SabreTech removed unexpended chemical oxygen generators during heavy maintenance for ValuJet. | Generator condition, aircraft removal, mechanic action, maintenance program, and later cargo disposition remain distinct. | Complete generator-specific condition, removal, tag, and task custody remain unresolved. |
| work card and signoff | Work card 0069 required safety caps on removed unexpended generators; cards were signed as complete although caps had not been installed. | Task instruction, mechanic performance, inspection and supervisory signoff, cap availability, and component state remain separate. | Complete individual knowledge, task signoff custody, review, challenge, and correction remain incomplete. |
| safety-cap state | The removed unexpended generators lacked required safety caps before packaging and carriage. | Work-card completion, safety-cap state, firing-mechanism protection, packaging, and later activation remain distinct. | Generator-by-generator cap state and the complete handling chronology are not reconstructed. |
| packaging and identification | NTSB found SabreTech failed to properly prepare, package, and identify the generators; the shipping ticket described five boxes as oxygen canisters marked empty. | Component condition, packaging, labeling, company-material description, hazardous-material status, and tracking remain separate. | Complete box contents, tag review, label-decision custody, and correction path remain incomplete. |
| contractor-to-carrier custody | SabreTech personnel packaged and presented the shipment as company material, and ValuJet ramp personnel accepted it for carriage. | Contractor maintenance and stores, ValuJet technical representation, shipping, ramp acceptance, loading approval, and carrier oversight remain distinct. | Complete handoff chronology, accountable receipt, knowledge, challenge, and disposition remain unresolved. |
| cargo loading | Five boxes described as empty oxygen canisters were loaded with tires and wheels in Flight 592's forward class D cargo compartment. | Shipment description, ramp handling, box placement, adjacent cargo, compartment classification, and flight operation remain separate. | Exact loading sequence, generator orientation, initial actuation, and loading-decision custody remain incomplete. |
| activation, fire, and cargo protection | NTSB determined that activation of one or more improperly carried generators initiated the fire; the class D compartment had neither required smoke/fire detection nor suppression. | Generator activation, heat and oxygen release, adjacent cargo, fire growth, compartment design, detection, warning, suppression, and aircraft state remain distinct. | The initiating generator, propagation chronology, warning timing, and verified protection effect remain unresolved. |
| crew response | The crew received cabin reports, reported fire and smoke, and attempted an immediate return to Miami. | Cabin observation, communication, cockpit receipt, crew decision, aircraft state, airport return, and emergency response remain separate. | Complete warning chronology, cockpit and cabin conditions, counterfactual landing sequence, and verified control effect remain incomplete. |
| oversight, standing, and consequence | NTSB identified separate SabreTech handling, ValuJet contract-maintenance oversight, cargo-protection, and FAA-monitoring findings; both pilots, 3 flight attendants, and 105 passengers died. | Contractor, carrier, regulator, crew, passengers, maintainers, responders, families, and investigators occupy distinct operating, maintenance, oversight, affected, response, and investigative positions. | Complete oversight chronology, causal weight, correction, implementation, participation, and health effects beyond the fatal accident remain outside this trace. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_valujet_592_workcard_cargo_fire_trace`.

The report supports a bounded event-local relation among removal and work-card
signoff, missing safety caps, packaging and identification, custody and
loading, generator activation, cargo fire and protection, crew response,
oversight, standing, and consequence. It does not support one complete task-
to-oversight custody chain. Separate contractor handling, carrier acceptance,
compartment design, crew action, carrier governance, FAA regulation and
surveillance, standing, and consequence are counterevidence to one universal
mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that work card 0069 did not require safety caps on the removed generators,
that the cards were not signed complete while caps remained absent, or that
activation of one or more improperly carried generators did not initiate the
fire. Reject any stronger chain that fills the preserved custody, knowledge,
receipt, chronology, correction, implementation, causal-weight, or control-
effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report or NTSB
investigation page changes a cited fact or boundary. Frontier retained the
candidate's bounded decision, nine ordered objects, principal supplied
relations, exact unknowns, and non-effect; separated repeated work-card and
safety-cap content, restored carrier acceptance, separated activation from
cargo protection, strengthened falsifier locality, and independently checked
`NTSB/AAR-97/06`. Frontier also authored source custody, authority
distinctions, counterevidence, correction, uncertainty, and non-promotion
boundaries.

Family lineage:
`SF-LIN-VALUJET592-WORKCARD-CARGO-FIRE-PARTIAL-TRACE-01`.
