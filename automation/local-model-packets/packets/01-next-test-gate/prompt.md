# Trace Alaska Airlines Flight 261 maintenance to trim-system failure

Lineage ID: `SF-LIN-ALASKA261-MAINTENANCE-TRIM-FAILURE-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence and bounded record `SF-0032`. Frontier review decides owner
truth. Do not retrieve sources. Do not invent unsupported facts. Do not
prescribe airline, lubrication, interval, inspection, maintenance, trim-
control, flight-crew, certification, surveillance, regulatory, or management
changes; infer recurrence, one universal mechanism, blame beyond supplied
NTSB findings, duty, liability, remedy efficacy, health causation, or external
effect.

Supplied evidence from `NTSB/AAR-02/01`:

- NTSB determined that Flight 261 lost pitch control after the horizontal-
  stabilizer trim-system jackscrew assembly's acme-nut threads failed in
  flight; excessive wear resulted from insufficient lubrication.
- No effective lubrication remained at the acme-screw and nut interface, but
  the complete specific missed or inadequate lubrication history is not
  reconstructed here.
- Alaska Airlines extended the lubrication interval, and FAA approved the
  extension; NTSB found this increased the likelihood that missed or
  inadequate lubrication would produce excessive thread wear.
- Alaska Airlines extended the end-play-check interval, and FAA approved that
  extension; NTSB found this allowed excessive wear to progress to failure
  without an opportunity for detection.
- The acme-nut threads wore excessively and were completely sheared during the
  accident flight. The crew encountered jammed and then failed stabilizer-trim
  behavior, attempted troubleshooting and recovery, and ultimately lost pitch
  control.
- NTSB separately found widespread systemic deficiencies in Alaska Airlines'
  maintenance program and deficient FAA surveillance, while declining to
  connect every discovered maintenance deficiency directly to the accident.
- The MD-80 design lacked a fail-safe mechanism against the catastrophic
  effects of total acme-nut thread loss.
- The 2 pilots, 3 cabin crewmembers, and 83 passengers aboard died.
- Task performance, intervals, measurement, wear, component and trim-system
  state, crew response, airline program, FAA approval and surveillance,
  design, certification, standing, and consequence remain distinct.
- Complete task custody, specific missed or inadequate lubrication history,
  measurement custody, interval-decision history, approval and surveillance
  chronology, correction, implementation, relative causal weight, and
  verified control effect remain incomplete.

Return exactly one Markdown table with eight ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `lubrication task`, `lubrication interval`, `end-play check`,
`thread wear`, `jackscrew and trim-system state`, `pitch control and crew
response`, `maintenance program and FAA oversight`, `standing and consequence`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_alaska_261_maintenance_trim_failure_trace`
  or `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace.
- **Unknowns:** `complete task custody, specific missed or inadequate
  lubrication history, measurement custody, interval-decision history,
  approval and surveillance chronology, correction, implementation, relative
  causal weight, and verified control effect remain incomplete`
- **Non-effect:** `No recurrence, one jackscrew, lubrication, inspection,
  interval, wear, trim-control, pitch-control, maintenance-program,
  certification, surveillance, regulatory, airline, manufacturer, FAA,
  flight-crew, maintainer, inspector, passenger, responder, or affected-party
  mechanism or authority, schema, blame beyond supplied NTSB findings, duty,
  remedy, acceptance, receiver work, health causation, liability, or external
  action is accepted.`

Plain Markdown, no frontmatter, under 1,000 words.
