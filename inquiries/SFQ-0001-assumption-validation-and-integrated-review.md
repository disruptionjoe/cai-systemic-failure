---
inquiry_id: SFQ-0001
status: routed_to_mechanism_design
source_record: evidence/records/SF-0001-boeing-737-max-certification-assumption-chain.md
created: 2026-07-18
receiver: cai-mechanism-design
external_action: none
---

# SFQ-0001 - Assumption Validation And Integrated Review

## Question

Can a source-preserving assumption-drift register force integrated review when
critical safety, legitimacy, or affected-party assumptions change across
incremental design updates, delegated review, and human response requirements?

## Why This Is Answerable

`SF-0001` identifies a concrete pattern: changed-function authority, review
delegation, and operator-response assumptions were not made into one
load-bearing contradiction object. A bounded mechanism can be tested
synthetically by asking whether it exposes the unvalidated assumption and routes
it to review without claiming to solve the aviation case.

## Owner Fit

- CAI Systemic Failure owns the source-backed failure record and this inquiry.
- CAI Mechanism Design may own a generic candidate mechanism because the
  question is integrative and not aviation-specific.
- Aviation-specific certification, rulemaking, training, and implementation
  belong to aviation authorities and domain experts.

## Falsifiers

- The proposed register only restates an ordinary checklist without increasing
  contradiction visibility.
- It requires authority, deployment, human subjects, confidential data, or
  domain-specific certification power to test.
- A better existing owner already has the mechanism and the candidate should be
  transferred or closed.

## Refinement From SF-0001-CM1

The first causal-model comparison narrows the test. A receiver should check
whether a proposed mechanism keeps three contradiction types visible:

1. a changed function or input path changes the validation burden;
2. a human-response assumption becomes unvalidated under changed alert,
   workload, or interface conditions; and
3. delegated review can see the contradiction without a central owner absorbing
   domain authority.

Passing paperwork fields is insufficient if the contradiction can remain hidden.

## Permitted Receiver Disposition

The receiver may kill, revise, defer, transfer, or admit a synthetic-only
candidate. The receiver may not deploy, publish externally, contact parties,
create accounts, recruit participants, or impose obligations on another owner.
