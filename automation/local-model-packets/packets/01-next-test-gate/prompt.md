# Trace San Bruno rupture recognition to isolation

Lineage ID: `SF-LIN-SANBRUNO-RECOGNITION-ISOLATION-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence and bounded record `SF-0027`. Frontier review decides owner truth.
Do not retrieve sources. Do not invent unsupported facts. Do not prescribe
pipeline, SCADA, isolation, valve, emergency-response, regulatory, or
management changes; infer recurrence, one universal mechanism, blame, duty,
liability, remedy efficacy, health causation, or external effect.

Supplied evidence from `NTSB/PAR-11/01`:

- Line 132 ruptured during a pressure increase associated with terminal work;
  released gas ignited in a residential area.
- SCADA limitations delayed PG&E's recognition and location of the break.
- City responders arrived promptly, while PG&E took 95 minutes to stop gas flow
  and isolate the rupture site.
- Automatic shutoff valves or remote control valves would have reduced
  isolation time; Line 132 lacked those protections along the affected length.
- Physical break, SCADA indications, public reporting, dispatch, location,
  valve operation, field response, isolation, flow cessation, municipal
  response, oversight, and standing remain distinct.
- Complete signal custody, command transfer, location decision, valve
  authority, response chronology, correction, implementation, relative causal
  weight, and control effect remain incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `rupture state`, `SCADA indication`, `public reporting and municipal
response`, `operator recognition`, `location and dispatch`, `valve operation
and isolation`, `standing and control effect`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_sanbruno_recognition_isolation_trace`
  or `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat the
  selected partial trace.
- **Unknowns:** `complete signal custody, command transfer, location decision,
  valve authority, response chronology, correction, implementation, relative
  causal weight, and control effect remain incomplete`
- **Non-effect:** `No recurrence, one rupture, pressure-control, SCADA,
  reporting, dispatch, location, valve, isolation, emergency-response,
  regulatory, or safety-management mechanism, shared controller, dispatcher,
  field operator, responder, regulator, community, or affected-party
  authority, schema, blame, duty, remedy, acceptance, receiver work, health
  causation, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 750 words.
