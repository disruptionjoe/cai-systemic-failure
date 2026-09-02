# Compare Marshall and San Bruno rupture recognition and stopping

Lineage ID: `SF-LIN-COMP-MARSHALL-SANBRUNO-RECOGNITION-STOP-01`, opportunity
1. Prepare one proposal-only comparison from supplied official NTSB evidence
and owner records `SF-0025`, `SF-0027`, and
`SF-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-0001`. Frontier review decides owner
truth. Do not retrieve sources. Do not invent unsupported facts. Do not infer
recurrence, one universal mechanism, blame, duty, liability, remedy efficacy,
health causation, or external effect.

Supplied evidence:

- Marshall: Line 6B ruptured during a planned shutdown. Pressure and material-
  balance indications were interpreted as column separation; the governing
  procedure required leak exclusion within ten minutes or shutdown, but two
  later startups added most of the release before recognition more than 17
  hours later. Staff treated absent outside reports as evidence against rupture.
- San Bruno: Line 132 ruptured during a pressure increase. SCADA limitations
  delayed recognition and location; city responders arrived promptly, while
  PG&E took 95 minutes to stop gas flow and isolate the site. The affected
  length lacked automatic shutoff or remote-control valves.
- Marshall concerns a hazardous-liquid shutdown/restart sequence with repeated
  interpretation and startup decisions. San Bruno concerns a gas-transmission
  rupture with delayed location and field isolation after ignition.
- Complete signal and report custody, accountable review, recognition,
  shutdown or isolation authority, correction, implementation, relative causal
  weight, community-information effect, and control effect remain incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Comparison object | Marshall boundary | San Bruno boundary | Shared relation
or preserved separation`: `transported material and physical state`, `remote
indication`, `interpretation and recognition`, `procedure or protection`,
`stopping action`, `community information and response`, `standing and control
effect`.

Then return exactly four lines:

- **Decision:** choose `preserve_separate_restart_and_isolation_sequences` or
  `prepare_bounded_recognition_stop_comparison`.
- **Falsifier:** name one exact supplied fact whose removal would defeat the
  selected decision.
- **Unknowns:** `complete signal and report custody, accountable review,
  recognition, shutdown or isolation authority, correction, implementation,
  relative causal weight, community-information effect, and control effect
  remain incomplete`
- **Non-effect:** `No recurrence, one rupture, leak-detection, SCADA, alarm,
  procedure, restart, reporting, dispatch, valve, isolation, emergency-
  response, regulatory, environmental, or safety-management mechanism, shared
  controller, analyst, supervisor, field operator, responder, regulator,
  community, or affected-party authority, schema, blame, duty, remedy,
  acceptance, receiver work, health causation, liability, or external action
  is accepted.`

Plain Markdown, no frontmatter, under 800 words.
