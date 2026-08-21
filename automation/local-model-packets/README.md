# Local-model packet experiment

This directory owns the prepared System Failures prompts used by the six
host-local Qwen slots during the PROG-008 / PROG-004 capability experiment.
The prompts are proposal-only experiment inputs, not accepted repository
findings or automation authority.

The live shape is:

```text
six fixed-cadence local triggers
  -> one exact packet folder each in packets/
  -> qwen3.5:9b-prog008
  -> immutable request, response, and transport receipt in local-model-scout

one four-hour Frontier evaluator
  -> EVALUATE-AND-ADJUST.md
  -> compare the newest same-prompt cohort
  -> revise prompts when repeated evidence justifies it
  -> record the learning in LEARNING.md
```

The local executor transports exact prompt bytes and owns no prompt content,
evaluation, workflow decision, target-repository write, or acceptance. During
this first gate the Frontier evaluator may refine the six existing work
requests, but it does not create new work packets or integrate local-model
results into repository truth. Those are later gates.

## Active packets

- `01-next-test-gate`
- `02-field-trace`
- `03-positive-false-negative`
- `04-refusal-consistency`
- `05-interacting-assumptions`
- `06-acceptance-refresh`

Each packet contains one complete `prompt.md`. Evidence required by the local
model is embedded in that file. A prompt revision creates a new request hash;
evaluations compare responses only within the same hash cohort.

