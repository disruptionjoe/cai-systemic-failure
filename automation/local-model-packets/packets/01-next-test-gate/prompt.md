# Trace Merrimack design change to control-line overpressure

Lineage ID: `SF-LIN-MERRIMACK-DESIGN-CONTROL-LINE-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence. Frontier review decides owner truth. Do not retrieve sources or
invent unsupported facts. Do not prescribe engineering, project-management,
construction, inspection, overpressure-protection, emergency-response,
regulatory, or safety-management changes; infer recurrence, one universal
mechanism, blame, duty, liability, remedy efficacy, health causation, or
external effect.

Supplied official evidence from `NTSB/PAR-19/02` and bounded record `SF-0026`:

- Columbia Gas replaced an existing cast-iron main with a polyethylene main
  while the low-pressure distribution system remained operating.
- The project abandoned the cast-iron main before relocating regulator sensing
  lines to the new main. Pressure fell in the old main and sensing lines,
  causing regulators to open and admit high-pressure gas.
- NTSB found weak engineering management did not adequately plan, review,
  sequence, and oversee the project; the work package lacked documentation of
  regulator sensing lines and did not receive professional-engineer approval.
- SCADA detected high pressure but could only monitor it. Field technicians
  isolated regulator stations and the system was later shut down.
- Complete design-change custody, field communication, inspector awareness,
  accountable review, correction, implementation, regulator disposition,
  relative causal weight, and control effect remain incomplete.

Return exactly one Markdown table with eight ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `project operating state`, `design documentation`, `engineering
review and approval`, `sensing-line configuration`, `work sequence`,
`regulator response`, `monitoring and field control`, `standing and control
effect`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_merrimack_design_control_trace` or
  `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace, not merely narrow one row.
- **Unknowns:** `complete design-change custody, field communication,
  inspector awareness, accountable review, correction, implementation,
  regulator disposition, relative causal weight, and control effect remain
  incomplete`
- **Non-effect:** `No recurrence, one design, documentation, sensing-line,
  pressure-control, construction, inspection, protection, emergency-response,
  regulatory, or safety-management mechanism, shared engineer, approver,
  contractor, inspector, operator, responder, regulator, community, or
  affected-party authority, schema, blame, duty, remedy, acceptance, receiver
  work, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 800 words.
