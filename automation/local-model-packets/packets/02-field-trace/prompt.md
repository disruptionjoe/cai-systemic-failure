# Compare CAPECO and DuPont emergency-control boundaries

Lineage ID: `SF-LIN-COMP-CAPECO-DUPONT-EMERGENCY-CONTROL-01`, opportunity 1.
Prepare one proposal-only comparison ledger from supplied owner facts. Do not
retrieve sources. Frontier review decides owner truth. Do not invent
unsupported facts or infer recurrence,
one shared mechanism, one root cause, complete custody, authority, disposition,
stop status, implementation, exposure or health causation, remedy efficacy,
receiver action, or external effect.

CAPECO supplied facts:

- Tank 409 overflowed for about 26 minutes after a long multi-tank transfer;
  unreliable gauging, an out-of-service transmitter card, no independent high-
  level alarm, and no automatic shutoff or diversion remained distinct.
- The gasoline formed a large vapor cloud, ignited, damaged tanks and nearby
  property, and entered environmental resources. The exact ignition source and
  complete warning, custody, authority, stop, and protection-effect chain are
  unknown.

DuPont supplied facts:

- A distress call led unprotected rescue entry during an unrecognized major
  toxic release. The process coordinator was unavailable, no on-shift backup
  filled the role, readiness and air monitoring were delayed, maps were absent,
  and hot-zone control was unclear.
- Process data and release characterization were incomplete; timely fence-line
  and adequate air-monitoring data were unavailable for public-protection
  decisions. Complete custody, authority, disposition, stop, exposure, and
  control effect are unknown.

Return a Markdown table with exactly these columns:

`Dimension | CAPECO | DuPont | Comparison boundary`

Use exactly six ordered rows: `initiating control`, `signal and detection`,
`command or technical support`, `protective zone and access`, `release and
public characterization`, `complete-chain gate`.

After the table return exactly four lines:

- **Decision:** choose `preserve_separate_emergency_control_boundaries` or `candidate_shared_pattern_requires_frontier_review`.
- **Shared residue:** name only any bounded relation present in both supplied records.
- **Unknowns:** `complete custody, accountable authority, disposition, stop status, implementation, exposure, relative causal weight, recurrence, and remedy efficacy remain unknown`
- **Non-effect:** `No recurrence, shared mechanism, schema pressure, blame, duty, environmental or health conclusion, remedy, receiver work, or external action is accepted.`

Plain Markdown, no frontmatter, under 700 words.
