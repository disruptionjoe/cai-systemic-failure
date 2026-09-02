# Trace Marshall leak indications to restart and recognition

Lineage ID: `SF-LIN-MARSHALL-ALARM-RESTART-PARTIAL-TRACE-01`, opportunity 1.
Prepare one proposal-only partial trace from supplied official NTSB evidence.
Frontier review decides owner truth. Do not retrieve sources. Do not invent
unsupported facts. Do not prescribe leak-detection, control-center, training,
public-awareness, emergency-response, regulatory, or pipeline changes; infer
recurrence, one universal mechanism, blame, duty, liability, remedy efficacy,
health causation, or external effect.

Supplied official evidence from `NTSB/PAR-12/01` and bounded record `SF-0025`:

- Line 6B ruptured during a planned shutdown. A sudden pressure drop, local
  pump-station shutdown alarm, and material-balance alarm were identified leak
  triggers, but the rupture was not recognized for more than 17 hours.
- The suspected-column-separation procedure required shutdown within 10
  minutes, mainline-valve closure, field leak confirmation, and designated-
  supervisor permission before restart if no leak was found.
- Control-center staff used an unapproved draft procedure, exceeded the ten-
  minute restriction during both startups, and accepted an analyst's
  interpretation that alarms were false because of column separation.
- Staff did not first use elevation profiles, historical pressure and flow
  trends, or alarm logs to rule out a leak. The report found inconsistent
  procedures did not ensure leaks were ruled out during shutdown and startup.
- Staff treated the absence of external notification as evidence against a
  rupture and did not actively seek local confirmation before visual
  confirmation arrived. Complete alarm custody, challenge, accountable review,
  authority, verification, correction, implementation, relative causal
  weight, and control effect remain incomplete.

Return exactly one Markdown table with eight ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `rupture and transient state`, `leak indications`, `initial
interpretation`, `ten-minute stop rule`, `first shutdown`, `restart
authorization`, `external-notification inference`, `recognition and stop`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_marshall_alarm_restart_trace` or
  `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace, not merely narrow one row.
- **Unknowns:** `complete alarm custody, challenge, accountable review,
  authority, verification, correction, implementation, relative causal
  weight, and control effect remain incomplete`
- **Non-effect:** `No recurrence, one alarm, column-separation, shutdown,
  startup, procedure, training, public-notification, control-center,
  emergency-response, regulatory, environmental, or health mechanism, shared
  operator, analyst, supervisor, field, responder, regulator, community, or
  affected-party authority, schema, blame, duty, remedy, acceptance, receiver
  work, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 750 words.
