# Trace Fort Totten verification testing to train-detection control

Lineage ID: `SF-LIN-FORT-TOTTEN-TEST-DETECTION-PARTIAL-TRACE-01`, opportunity
1. Prepare one proposal-only partial trace from supplied official NTSB evidence
and bounded record `SF-0028`. Frontier review decides owner truth. Do not
retrieve sources. Do not invent unsupported facts. Do not prescribe signaling, train control,
maintenance, testing, operations, oversight, regulatory, or railcar changes;
infer recurrence, one universal mechanism, blame, duty, liability, remedy
efficacy, health causation, or external effect.

Supplied evidence from `NTSB/RAR-10/02`:

- Failed B2-304 track-circuit modules produced a spurious signal that mimicked
  a valid signal, indicated the circuit vacant while train 214 occupied it, and
  permitted speed commands to train 112 up to impact.
- After 2005 Rosslyn near-collisions, WMATA developed an enhanced verification
  test but did not institutionalize and use it systemwide; technicians
  interviewed after Fort Totten were not familiar with it.
- NTSB found the enhanced test would have identified the faulty circuit. It
  also found that proper shunt placement during June 2009 testing could have
  exposed the loss of train detection before the accident.
- Manufacturer procedures would not have detected the spurious signals over
  module service life; maintenance planning, periodic monitoring, test
  disposition, correction, and implementation remained separate questions.
- Complete bulletin and test custody, technician knowledge, maintenance
  response, train-control authority, oversight correction, implementation,
  relative causal weight, and control effect remain incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `Rosslyn warning`, `enhanced test`, `technician knowledge`, `June
2009 verification`, `module signal state`, `train detection and speed command`,
`standing and control effect`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_fort_totten_test_detection_trace` or
  `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace.
- **Unknowns:** `complete bulletin and test custody, technician knowledge,
  maintenance response, train-control authority, oversight correction,
  implementation, relative causal weight, and control effect remain
  incomplete`
- **Non-effect:** `No recurrence, one warning, test, training, track-circuit,
  signal, detection, speed-command, maintenance, monitoring, train-control,
  oversight, or crashworthiness mechanism, shared engineer, technician,
  operator, controller, manager, director, regulator, passenger, or affected-
  party authority, schema, blame, duty, remedy, acceptance, receiver work,
  liability, health causation, or external action is accepted.`

Plain Markdown, no frontmatter, under 750 words.
