# Trace Amtrak 188 radio attention to speed control

Lineage ID: `SF-LIN-AMTRAK188-RADIO-SPEED-CONTROL-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence and bounded record `SF-0029`. Frontier review decides owner
truth. Do not retrieve sources. Do not invent unsupported facts. Do not
prescribe railroad, crew, radio, speed-control, positive-train-control,
passenger-protection, emergency-response, regulatory, or management changes;
infer recurrence, one universal mechanism, blame, duty, liability, remedy
efficacy, health causation, or external effect.

Supplied evidence from `NTSB/RAR-16/02`:

- The engineer monitored a six-minute radio exchange about an emergency
  involving a nearby SEPTA train and remained focused on that incident as train
  188 approached the accident area.
- NTSB concluded that he accelerated to 106 mph without slowing for the 50 mph
  Frankford Junction curve because he lost situational awareness, likely after
  his attention was diverted to the SEPTA emergency.
- Cab-signal protection did not enforce the eastbound 50 mph restriction; PTC
  was not implemented there, and NTSB found PTC or equivalent enforcement
  would have prevented the accident.
- The engineer applied emergency braking as the train entered the curve;
  seconds later the train derailed.
- Radio-information relevance, attention, location awareness, throttle action,
  rule and signal state, automatic enforcement, braking, derailment, occupant
  standing, and oversight remain distinct.
- Complete attention custody, cue receipt, train-control decision sequence,
  implementation history, correction, relative causal weight, and verified
  control effect remain incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `radio information`, `attention allocation`, `situational
awareness`, `speed and curve`, `signal and rule boundary`, `automatic
enforcement`, `braking, derailment, and standing`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_amtrak188_radio_speed_control_trace`
  or `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace.
- **Unknowns:** `complete attention custody, cue receipt, train-control
  decision sequence, implementation history, correction, relative causal
  weight, and verified control effect remain incomplete`
- **Non-effect:** `No recurrence, one radio, attention, situational-awareness,
  speed-control, signal, operating-rule, train-control, braking, derailment,
  occupant-protection, emergency-response, regulatory, or safety-management
  mechanism, shared engineer, dispatcher, operator, regulator, passenger, or
  affected-party authority, schema, blame, duty, remedy, acceptance, receiver
  work, health causation, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 800 words.
