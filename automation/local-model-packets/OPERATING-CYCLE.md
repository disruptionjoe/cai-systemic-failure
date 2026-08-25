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
  -> reads sealed Frontier contribution evaluations
  -> owns Phase 2 prompt repair
  -> advances separate raw-attempt and contribution cursors

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

An ingestion trial may select only exact completed attempts whose packet type,
prompt hash, and attempt ID the newest sealed evaluation makes eligible. Do
not preserve a static packet allowlist after evaluator state changes.

Eligibility is not acceptance and does not require all eligible packet types
to be used. Frontier Progress must choose an exact candidate or compatible
batch,
verify it independently against current repository truth, and preserve every
source, uncertainty, provisional, falsifier, no-remedy, non-promotion, and
external-action boundary.

## Progress semantics

The local model performs candidate production, not a governed owner Run. A
candidate counts as useful only when the Frontier model can verify and retain a
material part of it. Repository Progress occurs only when a separately
admitted Progress effect passes native validation and durably changes owner
truth.

Each Frontier Progress receipt records retained contribution, candidate error
burden, non-error Frontier verification/integration/scope-extension burden,
net leverage, owner effect, and validation. Correct but incomplete work may
require material Frontier integration without being an error. Formatting or
draft polish is not a defect unless it materially increases production work.

Transport success, nonempty text, a receipt, a summary, or a claim that no work
was needed is never candidate or repository Progress. Evidence, authority,
safety, proposal, uncertainty, and provenance violations remain hard failures.

Every end-to-end record preserves packet family/version, prompt hash, attempt
ID, evaluator receipt, Progress receipt, target starting revision, and
resulting owner revision. Compare only like prompt versions. Advance the
operating cursor only after every candidate through the mark has a terminal
disposition; failed or interrupted integration retains the prior cursor, and
retries deduplicate by attempt ID plus target starting revision.

## State transitions

`ingestion_trial` may change to `operational_pilot` only after Joe accepts the
trial evidence. At that point Systemic Stewardship may become the sole owner of
packet selection and replenishment, and the four-hour evaluator may become
read-only, be absorbed, or be retired. No scheduled process changes this state
implicitly.
