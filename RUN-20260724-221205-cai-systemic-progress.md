# Run Plan: RUN-20260724-221205-cai-systemic-progress

Status: complete

## Target

- Owner: `cai-systemic-failure`
- Parent: `RUN-20260724-221205-repository-work-cycle-cai-hourly`
- Starting revision: `fff1e5b2398ffc541afaa10cb25de701720d5b95`
- Run mode: scheduled / non-interactive
- Working tree at selection: clean; `main` even with `origin/main`

## Run Family

- Workflow: `system-runtime#repo-progress-run`
- Workflow revision:
  `sha256:3cc3db78e03c512e64206aa63ee96059c981f018888ed7b215776368fc38104d`
- Mode: `system-canon#execute`
- Lane: `1`
- Method refs: `[]`

## Objective

Test whether the provisional review-chain candidate can qualify a record by
citing a named but superseded source revision while ignoring a later revision
that withdraws or materially contradicts the qualifying synthesis. Add a
synthetic source-revision-lineage falsifier, tighten only the existing source
gate, and keep the core field list and candidate status unchanged.

Purpose connection: source-preserving models are not correctable when a citation
is present but its revision lineage and known material contradiction are hidden.
The swing makes that failure mode inspectable without manufacturing a real-world
claim or requiring external research.

Intended material effect: require records to identify the relied-on source
revision and preserve any known materially superseding or contradicting revision
before candidate qualification. A superseded revision may remain historical
evidence but cannot alone carry current positive qualification.

Concrete first attempt: run a two-revision synthetic fixture through the current
qualification gate and refine the existing `assumption_source_context` source
requirement only if the fixture exposes a real false-positive path.

## Context Reads

- CapacityOS `AGENTS.md`, `Agents Start Here.md`, and JB local-resource safety
- CAI Governance `AGENTS.md`, constitution, current phase, strategy, and Lanes
- System registry row and System steward service for `cai-systemic-failure`
- Owner `AGENTS.md`, `README.md`, `GOVERNANCE.md`, `LANES.yaml`,
  `LANE-STATE.yaml`, `STATUS.md`, `ROADMAP.md`, and authoritative indexes
- Candidate, acceptance bar, non-accepting packet, latest counterevidence
  falsifier, synthetic acceptance controls, recent local Runs, and Git history
- Repository Work Cycle Progress workflow, all required flows, standard safety
  rules, run-packet contract, Execute mode, emergency revocations, and result
  schema
- Automation memory for the immediately preceding CAI cycle

## Lane Selection

- Owner: `cai-systemic-failure`
- Charter digest: `GOVERNANCE.md`
  SHA-256 `c5ed88ef65ff823ad00f345c213c56d8d9652c50820f4c90f2062a6ab6de793c`
- Governance digests:
  - `AGENTS.md`
    SHA-256 `60ea3094f0885979bfb2dc378301b763ecf209c1d517becfd8495d18f1248dca`
  - `GOVERNANCE.md`
    SHA-256 `c5ed88ef65ff823ad00f345c213c56d8d9652c50820f4c90f2062a6ab6de793c`
- Lane manifest SHA-256:
  `2976336f679b996cb102f910192187985c13204ed153441b231fbca36b83bc29`
- Manifest / definition / control revision: `2` / `2` / `1`
- Lane state: active; in-flight policy: `continue_current`
- Directed flow / revision: `null` / `null`
- Selected work:
  `ROADMAP.md#27`; `STATUS.md`; `topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md`;
  `topology/SF-SCHEMA-ACCEPTANCE-PACKET-0001-review-chain-fields.md`;
  `topology/SF-CEQ-0001-counterevidence-quality-asymmetry.md`
- Selection basis: the source field names a revision but does not say how a
  known superseding or materially contradicting revision affects
  qualification. A synthetic two-revision fixture therefore creates materially
  new pressure on a core source gate rather than adding record-count churn.
- Effective permission: write owner-local versioned knowledge for this bounded
  synthetic Progress test and normal GitHub versioning.
- Allowed outputs: synthetic falsifier, narrow candidate-source-gate
  refinement, current-truth/index/acceptance updates, Lane-state refresh, and
  this owner Run record.
- Forbidden outputs: accepted schema or ontology; real-world failure claim;
  domain remedy; another owner's truth; human or field research; confidential,
  restricted, or regulated material; participation, intervention, deployment,
  posting, sending, spending, account, schedule, phase, identity, Lane-purpose,
  or non-GitHub external action.
- Joe-review points: none; the test cannot accept or promote the candidate.
- Unresolved references: none.
- Emergency-revocation SHA-256:
  `8a992d3eb3f61b51ef83aa7cb8f85a1865fd0bf76c1f690429fa200a1c698723`;
  matching entries: none.

## Expected Writable Surfaces

- `topology/SF-SRL-0001-source-revision-lineage.md`
- `topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md`
- `topology/README.md`
- `STATUS.md`
- `ROADMAP.md`
- `LANE-STATE.yaml`
- `tests/synthetic-acceptance.md`
- `RUN-20260724-221205-cai-systemic-progress.md`

## Recent Run Collision Check

No local Run created or modified in the preceding hour exists. The latest local
receipt is complete, the checkout is clean and even with `origin/main`, the
repository writer lock is absent, and no live overlapping writer is evidenced.
The selected footprint is disjoint from all closed prior work.

## Forbidden Actions And Stop Conditions

- Stop on changed owner identity, Lane definition, execute permission, directed
  flow, emergency state, writer state, starting revision, or undeclared
  footprint.
- Stop on dirty overlap, unexpected generated output, failed validation,
  external research/action need, or any result requiring schema acceptance,
  claim-status change, or Joe-reserved authority.
- Do not treat the synthetic fixture as evidence that an actual source was
  revised or that a real system failed.

## Joe-Review Points

None expected. Schema acceptance, public posture, phase, participation,
fieldwork, and consequential action remain closed.

## Plan

1. Revalidate the formal packet and exact effect boundary.
2. Add the two-revision synthetic fixture and apply each candidate gate.
3. Refine only the existing source-context gate if the fixture demonstrates a
   false-positive path; keep all nine core fields and candidate status frozen.
4. Refresh current indexes, state, roadmap, and synthetic acceptance coverage.
5. Run lightweight reference, YAML, whitespace, field-freeze, and footprint
   validation.
6. Rerank next work, append the receipt, stage explicit paths, commit,
   non-force push, and verify clean remote parity.

## Execution Notes

- The two-revision fixture isolated a source-lineage false-positive path: a
  record could name revision 1 while withholding a known revision 2 that
  materially removes the support carrying qualification.
- The candidate refused the fixture. `assumption_source_context` now requires
  the relied-on revision and disposition of any known materially superseding,
  narrowing, withdrawing, or contradicting revision in the admitted source
  packet.
- The refinement is deliberately bounded. It does not require external source
  monitoring, exhaustive proof that no later revision exists, or refusal for
  editorial and unrelated changes.
- The core field list remains nine fields, candidate status remains
  `provisional_schema_candidate`, and no real-world source-revision or failure
  claim was added.
- `STATUS.md`, `ROADMAP.md`, the topology index, synthetic acceptance surface,
  and Lane 1 current state now point to the falsifier and preserved
  non-promotion result.
- Artifact disposition: the falsifier, candidate refinement, current-truth
  updates, acceptance assertion, Lane-state refresh, and this Run record are
  deliberate owner-local versioned knowledge. No generated, third-party,
  secret, regulated, durable-binary, archive, scratch, or cache artifact was
  staged.

## Validation

- `git diff --check` passed.
- Ruby YAML parsing verified `LANES.yaml` and `LANE-STATE.yaml` and exact owner
  and Lane-ID parity.
- Reference validation found `SF-SRL-0001` in the falsifier, candidate,
  topology index, status, roadmap, Lane state, synthetic acceptance surface,
  and Run record.
- Candidate validation confirmed `status: provisional_schema_candidate`, the
  unchanged nine-field core list, and the new known-material-revision-conflict
  refusal.
- Synthetic acceptance validation confirmed the revision-lineage refusal and
  historical-evidence preservation assertion.
- Public-path validation found no absolute home path in the declared footprint.
- Exact footprint inspection found only the eight declared paths.
- A final fetch confirmed the pinned starting revision still matched
  `origin/main`; no heavy validation job was started.

## Receipt

- Closed: `2026-07-24T22:20:00-05:00`
- Phase / result: `progress` / `progressed`
- Service outcome: `progressed`
- Owner / Lane: `cai-systemic-failure` / `1`
- Starting revision: `fff1e5b2398ffc541afaa10cb25de701720d5b95`
- Actual footprint:
  `topology/SF-SRL-0001-source-revision-lineage.md`;
  `topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md`;
  `topology/README.md`; `STATUS.md`; `ROADMAP.md`; `LANE-STATE.yaml`;
  `tests/synthetic-acceptance.md`;
  `RUN-20260724-221205-cai-systemic-progress.md`
- Owner effect:
  `RUN-20260724-221205-cai-systemic-progress#source-revision-lineage-gate`
- Material effect: the provisional candidate now refuses positive
  qualification when a record knowingly relies on an earlier supporting source
  revision while omitting a later material contradiction already present in
  the admitted source packet.
- Lane revalidation: owner and governance digests, Lane manifest digest and
  revisions, execute permission, directed-flow null, starting revision, empty
  emergency state, absent writer lock, branch parity, and exact footprint
  matched before owner effects and close.
- Manifest SHA-256:
  `2976336f679b996cb102f910192187985c13204ed153441b231fbca36b83bc29`
- Manifest / definition / control revision: `2` / `2` / `1`
- Emergency-revocation SHA-256:
  `8a992d3eb3f61b51ef83aa7cb8f85a1865fd0bf76c1f690429fa200a1c698723`;
  matching entries: none.
- Required flows attested: `standard-run-safety-check`, `select-lane`,
  `create-run-plan`, `revalidate-lane-selection`, and `append-run-receipt`.
- Conditional flows invoked: `rerank-next-work`, `refresh-lane-state`
  (including read-only `derive-lane-health`), and
  `classify-artifact-disposition`.
- Required graph attested: `true`; exceptions: none.
- Method refs / effect: `[]` / `null`
- Validation: lightweight YAML, reference, status/field-freeze, synthetic
  acceptance, public-path, whitespace, branch-parity, and exact-footprint
  checks passed.
- External actions: GitHub commit and non-force push only.
- Uncertainty: the synthetic fixture validates refusal semantics, not any
  real-world source history, failure claim, or schema acceptance.
- Attention and methodology routes: none.
- Next-work handoff:
  - current work: `SF-SRL-0001`
  - current disposition: `ENDPOINT_POSITIVE`
  - durable priority owner: `ROADMAP.md`
  - recommendation status: advisory
  - recommended next: none until new public or synthetic material creates
    pressure on a core field, refusal note, annotation, source gate, or
    correction-route gate
  - switch signal: source-lineage control now refuses known material
    contradiction hidden behind an earlier revision-specific citation
  - strongest alternative: non-synthetic correction-route opacity; currently
    deferred by the non-accepting packet until official or safely shareable
    material avoids source-thin reconstruction
  - overturning evidence: a bounded case showing the lineage refinement
    wrongly rejects a still-supportive earlier revision or fails to expose a
    materially superseded one
  - steward reconciliation needed: no
