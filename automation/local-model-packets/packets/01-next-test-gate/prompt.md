# Build a CAPECO overfill signal-to-stop partial trace

Lineage ID: `SF-LIN-CAPECO-OVERFILL-SIGNAL-STOP-TRACE-01`, opportunity 1.
Prepare one proposal-only trace ledger from the supplied CSB-grounded owner
facts. Do not retrieve sources. Frontier review decides owner truth. Do not
invent unsupported facts or complete knowledge, custody, authority,
disposition, stop status,
implementation, ignition source, health or environmental causation, recurrence,
schema fit, blame, duty, remedy efficacy, receiver action, or external effect.

Supplied facts from owner record `SF-0016`:

- A ship-to-terminal transfer was distributed among four tanks over more than
  24 hours; remaining flow was later directed to tanks 409 and 411.
- Tank 409 overflowed for about 26 minutes and released nearly 200,000 gallons
  through vents into the containment dike.
- Float-and-tape gauging was primary; instruments were poorly maintained and
  frequently failed. Tank 409's transmitter card was out of service, so manual
  hourly readings were required.
- Tank 409 lacked an independent high-level alarm, and the terminal lacked an
  automatic system able to shut off or divert flow.
- The release formed a large vapor cloud that ignited; the exact ignition
  source remains unknown.

Return a Markdown table with exactly these columns:

`Layer | Supported fact | Boundary | Unknown`

Use exactly seven ordered rows: `transfer allocation`, `level evidence`,
`instrument condition`, `independent alarm`, `automatic flow control`,
`overflow and release`, `stop-chain decision`.

After the table return exactly three lines:

- **Decision:** choose `current_record_supports_partial_signal_stop_trace` or `current_record_insufficient_for_trace`.
- **Missing links:** `complete knowledge, custody, accountable receipt, authority, disposition, stop status, implementation, ignition, and control effect remain unknown`
- **Non-effect:** `No recurrence, shared mechanism, schema pressure, blame, duty, environmental or health conclusion, remedy, receiver work, or external action is accepted.`

Use the partial-trace decision only if every layer remains separate. Plain
Markdown, no frontmatter, under 650 words.
