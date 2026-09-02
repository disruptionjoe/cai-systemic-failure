# Trace American Airlines Flight 587 wake encounter to stabilizer separation

Lineage ID: `SF-LIN-AMERICAN587-WAKE-RUDDER-STABILIZER-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence and bounded record `SF-0034`. Frontier review decides owner
truth. Do not retrieve sources. Do not invent unsupported facts. Do not
prescribe aircraft, wake-turbulence, rudder, training, upset-recovery, design,
certification, airline, manufacturer, flight-crew, surveillance, regulatory,
or management changes; infer recurrence, one universal mechanism, blame
beyond supplied NTSB findings, duty, liability, remedy efficacy, health
causation, or external effect.

Supplied evidence from `NTSB/AAR-04/04`:

- American Airlines Flight 587 encountered a second wake-turbulence event
  shortly after takeoff from John F. Kennedy International Airport on
  November 12, 2001.
- The first officer responded with control-wheel and rudder-pedal input, then
  made five subsequent alternating full rudder-pedal inputs over about 6.5
  seconds until the vertical stabilizer separated.
- NTSB determined that unnecessary and excessive rudder-pedal inputs created
  loads beyond ultimate design and caused the vertical stabilizer to separate
  in flight.
- The A300-600 rudder system combined increasing sensitivity with airspeed and
  unusually light pedal forces among transport aircraft NTSB evaluated.
- Alternating inputs rapidly built sideslip and aerodynamic loads. Pedal
  command, rudder motion, aircraft response, load, structural capacity, and
  separation remain distinct.
- The stabilizer and rudder separated before the engines; the airplane then
  departed controlled flight and crashed.
- NTSB identified A300-600 rudder-system design characteristics and elements
  of American Airlines' Advanced Aircraft Maneuvering Program as contributors
  to the rudder inputs.
- The 2 flight crewmembers, 7 flight attendants, and 251 passengers aboard,
  plus 5 people on the ground, died.
- Complete cue perception, input-by-input intent and effect, training-to-
  action custody, design and certification chronology, post-separation control
  chronology, correction, implementation, relative causal weight, and
  verified control effect remain incomplete.

Return exactly one Markdown table with nine ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `wake encounter`, `initial control response`, `alternating rudder
inputs`, `rudder-system response`, `sideslip and aerodynamic load`, `vertical-
stabilizer separation`, `aircraft response`, `training design and
certification`, `standing and consequence`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_american_587_wake_rudder_stabilizer_trace`
  or `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied input-load-separation relation whose
  removal would defeat the selected partial trace.
- **Unknowns:** `complete cue perception, input-by-input intent and effect,
  training-to-action custody, design and certification chronology, post-
  separation control chronology, correction, implementation, relative causal
  weight, and verified control effect remain incomplete`
- **Non-effect:** `No recurrence, one wake-turbulence, rudder, pilot-input,
  training, upset-recovery, aircraft-pilot-coupling, aerodynamic-load,
  structural-failure, aircraft-response, design, certification, airline,
  manufacturer, FAA, flight-crew, passenger, ground-resident, responder, or
  affected-party mechanism or authority, schema, blame beyond supplied NTSB
  findings, duty, remedy, acceptance, receiver work, health causation,
  liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 1,100 words.
