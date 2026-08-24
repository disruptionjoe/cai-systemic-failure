# Local-model packet experiment

This directory owns the prepared System Failures prompts used by the six
host-local Qwen slots during the PROG-008 / PROG-004 capability experiment.
The prompts are proposal-only experiment inputs, not accepted repository
findings or automation authority. Gate 1 established that six fixed,
Frontier-refined packets could produce repeated useful work. Gate 2 tests
whether a Frontier-authored new campaign transfers those lessons without
packet-by-packet benchmark overfitting.

The live shape is:

```text
six fixed-cadence local triggers
  -> one exact packet folder each in packets/
  -> qwen3.5:9b-prog008
  -> immutable request, response, and transport receipt in local-model-scout

one four-hour Frontier evaluator
  -> EVALUATE-AND-ADJUST.md
  -> read the prior evaluation cursor
  -> evaluate every completed attempt since it, grouped by prompt hash
  -> revise prompts when repeated evidence justifies it
  -> record the learning in LEARNING.md
```

The local executor transports exact prompt bytes and owns no prompt content,
evaluation, workflow decision, target-repository write, or acceptance. The
Frontier evaluator may refine the active prepared requests from repeated
evidence, but it does not integrate local-model results into repository truth.
Gate 2 has met the readiness floor for a Frontier ingestion trial. The active
target-side contract for that next gate is `OPERATING-CYCLE.md`.

## Active Phase 2 campaign

The folder names are stable transport-slot identifiers retained so the six Mac
triggers never need campaign-specific rewiring. The active prompt inside each
slot now requests:

- `01-next-test-gate`: temporal-coherence material-pressure admission;
- `02-field-trace`: five-falsifier control crosswalk;
- `03-positive-false-negative`: five-absorber refusal-boundary matrix;
- `04-refusal-consistency`: source-gated annotation-lineage reconciliation;
- `05-interacting-assumptions`: temporal-coherence qualification trace; and
- `06-acceptance-refresh`: complete temporal-coherence falsifier draft.

Each packet contains one complete `prompt.md`. Evidence required by the local
model is embedded in that file. A prompt revision creates a new request hash;
evaluations consume every attempt after the prior per-packet cursor but compare
quality and attribute failures only within the correct hash cohort.

Gate 2 preserves the first request hash for each new packet as the transfer
baseline. Later prompt repair may show that a packet can be stabilized, but it
cannot retroactively turn a failed first-hash cohort into Frontier-authored
first-pass success.
