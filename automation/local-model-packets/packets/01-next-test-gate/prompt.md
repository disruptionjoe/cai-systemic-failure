# Trace Schoharie out-of-service evidence to dispatch

Lineage ID: `SF-LIN-SCHOHARIE-OOS-DISPATCH-PARTIAL-TRACE-01`, opportunity 1.
Prepare one proposal-only partial trace from supplied official NTSB evidence
and bounded record `SF-0030`. Frontier review decides owner truth. Do not
retrieve sources. Do not invent unsupported facts. Do not prescribe vehicle,
carrier, driver, maintenance, inspection, registration, repair-verification,
enforcement, occupant-protection, regulatory, or management changes; infer
recurrence, one universal mechanism, blame beyond the supplied NTSB finding,
duty, liability, remedy efficacy, health causation, or external effect.

Supplied evidence from `NTSB/HAR-20/03`:

- NYSDOT placed the limousine out of service before the crash for safety
  defects that included brake deficiencies; the vehicle had not been verified
  as repaired.
- Prestige Limousine dispatched it for a passenger charter despite the out-of-
  service order and without operating authority.
- NTSB found the brake system inadequately maintained and in poor condition;
  rear-brake components showed evidence they had not been appreciably working.
- NTSB found NYSDOT oversight ineffective despite knowledge of repeated out-
  of-service violations and lack of authority, and found its repair-
  verification process inadequate.
- NTSB separately found inadequate DMV oversight of state-licensed inspection
  stations and improper registration enabled avoidance of more rigorous safety
  requirements.
- Out-of-service finding, carrier receipt, repair representation, verification,
  operating authority, dispatch, driver receipt, brake condition, enforcement,
  occupant standing, and consequence remain distinct.
- Complete order custody, repair history, inspection decision, information
  transfer, enforcement chronology, dispatch decision, correction,
  implementation, relative causal weight, and verified control effect remain
  incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `out-of-service finding`, `carrier receipt`, `repair representation
and verification`, `operating authority`, `dispatch`, `brake condition and
operation`, `standing and consequence`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_schoharie_oos_dispatch_trace` or
  `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat
  the selected partial trace.
- **Unknowns:** `complete order custody, repair history, inspection decision,
  information transfer, enforcement chronology, dispatch decision,
  correction, implementation, relative causal weight, and verified control
  effect remain incomplete`
- **Non-effect:** `No recurrence, one out-of-service, repair, verification,
  operating-authority, dispatch, brake, maintenance, inspection, registration,
  enforcement, occupant-protection, regulatory, or safety-management
  mechanism, shared carrier, maintainer, inspector, agency, regulator, driver,
  occupant, pedestrian, responder, or affected-party authority, schema, blame
  beyond the supplied NTSB finding, duty, remedy, acceptance, receiver work,
  health causation, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 850 words.
