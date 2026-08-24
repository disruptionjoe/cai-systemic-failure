# System Failures local-model operating cycle

Status: `ingestion_trial`

This is the target-owned interface for the Frontier Repository Operating Cycle
that observes System Failures, stewards the repository service, prepares work,
and conditionally verifies and incorporates bounded candidate work through a
normal Progress Run. The complete execution contract and receipts remain in
System Runtime. This file owns only the target-side experiment state and
packet boundaries.

## Current topology

```text
six unchanged Mac packet triggers
  -> prepared prompt.md files
  -> qwen3.5:9b-prog008
  -> immutable local candidate attempts

four-hour Frontier evaluator
  -> evaluates completed attempts by prompt hash
  -> owns Phase 2 prompt repair
  -> advances LEARNING.md cursors

Frontier Repository Operating Cycle
  -> read-only Repository Observation
  -> Systemic Repository Stewardship and routing ledger
  -> conditional Prepared Progress
  -> pointer-only cycle close
```

There is no scheduled self-selecting Deep Progress source for this pilot.

## Phase 2 ownership

The four-hour evaluator is the only process allowed to modify the six active
`prompt.md` files while status is `ingestion_trial`. Systemic Stewardship may
recommend future work or a later campaign, but it must leave current prompt
bytes and the six Mac jobs unchanged.

The first ingestion trial may select only exact completed attempts from packet
types whose newest sealed evaluation makes them eligible. The current Gate 2
floor is:

- eligible original-hash packet types: `02-field-trace`,
  `03-positive-false-negative`, `04-refusal-consistency`, and
  `06-acceptance-refresh`;
- not yet eligible: repaired `01-next-test-gate` and
  `05-interacting-assumptions`.

Eligibility is not acceptance and does not require all four packet types to be
used. Frontier Progress must choose an exact candidate or compatible batch,
verify it independently against current repository truth, and preserve every
source, uncertainty, provisional, falsifier, no-remedy, non-promotion, and
external-action boundary.

## Progress semantics

The local model performs candidate production, not a governed owner Run. A
candidate counts as useful only when the Frontier model can verify and retain a
material part of it. Repository Progress occurs only when a separately
admitted Progress effect passes native validation and durably changes owner
truth.

Transport success, nonempty text, a receipt, a summary, or a claim that no work
was needed is never candidate or repository Progress.

## State transitions

`ingestion_trial` may change to `operational_pilot` only after Joe accepts the
trial evidence. At that point Systemic Stewardship may become the sole owner of
packet selection and replenishment, and the four-hour evaluator may become
read-only, be absorbed, or be retired. No scheduled process changes this state
implicitly.
