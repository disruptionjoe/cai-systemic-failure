# Run Plan: RUN-20260731-021436-cai-systemic-progress

Status: active

## Target

- Owner: `cai-systemic-failure`
- Parent: scheduled CAI Repository Work Cycle
- Starting revision: `a9968e3aa0f99fd66cdf82087c9ba1c8a1f60f7f`
- Run mode: scheduled / non-interactive
- Working tree at selection: clean; `main` even with `origin/main`

## Run Family

- Workflow: `system-runtime#repo-progress-run`
- Workflow revision: `sha256:09ceebd5cdcb21090c418dd504a529b7bd10a906f5709a709a70f14d9adc918c`
- Mode: `system-canon#execute`
- Lane: `1`
- Method refs: `[]`

## Objective

Test whether the provisional review-chain candidate improperly qualifies a
synthetic record when its admitted packet directly and materially contradicts
a required positive-fit field, even though the record names sources,
revisions, and a generic countermodel. Tighten only the existing source and
counterevidence gate; keep the nine core fields and candidate status unchanged.

Purpose connection: source-preserving synthesis cannot be decision-useful when
the same admitted packet both supplies and directly undermines a required
field, yet the record presents the field as passed.

Intended material effect: add a bounded synthetic intra-packet-contradiction
falsifier, make direct material contradictions explicitly gradeable, and leave
an inspectable acceptance assertion and current-owner pointers.

Concrete first attempt: construct a safely shareable synthetic packet whose
identified source excerpts support and directly contradict the same claimed
assumption context, while the record labels that field passed; apply the
qualification gate and refuse the fixture if undispositioned contradiction
creates a false-positive path.

## Context Reads

- CapacityOS root authority, CAI work-cycle trigger and Progress workflow,
  safety contract, run-packet and required-flow contracts.
- Repository registry and CAI System steward service.
- Owner `AGENTS.md`, `README.md`, `GOVERNANCE.md`, `STATUS.md`, `ROADMAP.md`,
  `LANES.yaml`, `LANE-STATE.yaml`, topology index and candidate, synthetic
  acceptance controls, and recent closed Progress runs.
- Emergency revocations: `operations/lane-emergency-revocations.yaml`,
  revision `1`, digest
  `8a992d3eb3f61b51ef83aa7cb8f85a1865fd0bf76c1f690429fa200a1c698723`;
  matching entries: none.

## Lane Selection

- Owner: `cai-systemic-failure`; selected Lane: `1` (active, north-star,
  automation eligible; directed flow `null`).
- Charter digest: `c5ed88ef65ff823ad00f345c213c56d8d9652c50820f4c90f2062a6ab6de793c`.
- Governance digests: `AGENTS.md`
  `60ea3094f0885979bfb2dc378301b763ecf209c1d517becfd8495d18f1248dca`;
  `GOVERNANCE.md`
  `c5ed88ef65ff823ad00f345c213c56d8d9652c50820f4c90f2062a6ab6de793c`.
- Manifest digest / revision / definition / control:
  `7ee3081259d033a395f2ff1137a133cb036f42732d530fc0a38cda0448f16550` /
  `3` / `2` / `1`.
- Selection basis: `ROADMAP.md#30` admits bounded synthetic pressure on a
  source gate. Existing tests reject source thinness, omitted material later
  revisions, weak alternatives, incapable correction routes, and unbridged
  composite sources, but do not test a direct material contradiction already
  visible within the admitted packet for one required field.
- Effective permission: bounded owner-local synthetic versioned knowledge and
  current-truth updates with normal GitHub versioning only.
- Forbidden: schema acceptance; real-world claim; remedy; other-owner truth;
  human/field research; sensitive data; intervention; participation; and every
  external action other than GitHub versioning.

## Expected Writable Surfaces

- `topology/SF-IPC-0001-intra-packet-contradiction.md`
- `topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md`
- `topology/README.md`; `STATUS.md`; `ROADMAP.md`; `LANE-STATE.yaml`
- `tests/synthetic-acceptance.md`
- `RUN-20260731-021436-cai-systemic-progress.md`

## Recent Run Collision Check

The latest local Progress run (`RUN-20260727-071918`) is complete with a
receipt. No Run from the last hour is open or overlaps this source-contradiction
test, the tree is clean, `main` is even with `origin/main`, and the resolved
writer lock `.git/capacityos-writer.lock` is absent. This objective is disjoint
from source-revision lineage and composite-evidence coherence.

## Forbidden Actions And Stop Conditions

Stop on owner/Lane/permission/directed-flow/emergency/lock mismatch, dirty
overlap, changed starting revision, undeclared footprint, validation failure,
need for external research or action, or a result requiring schema acceptance.
Do not represent the synthetic fixture as evidence of a real source,
contradiction, failure, organization, or remedy.

## Joe-Review Points

None. Candidate acceptance, public posture, participation, field work, and
consequential action remain closed.

## Plan

1. Revalidate the formal packet and exact effect boundary.
2. Add the direct intra-packet contradiction falsifier and apply every gate.
3. Narrow only existing source and counterevidence treatment if the fixture
   reveals the false-positive path.
4. Refresh owner indexes, state, roadmap, and synthetic acceptance coverage.
5. Validate references, YAML, field freeze, acceptance assertion, public
   paths, whitespace, and exact footprint; rerank; append receipt; commit and
   push.

## Execution Notes

- The fixture isolated a source-gate false positive: one admitted packet can
  contain a direct material conflict over a required field while the record
  selectively quotes support and labels the field passed.
- The candidate refused the fixture. Required-field support now preserves and
  grades direct material contradictions in the admitted packet; contested,
  narrowed, or unresolved support remains explicit rather than silently passed.
- The nine core fields and `provisional_schema_candidate` status remain
  unchanged. No real-world source, failure, organization, remedy, or authority
  claim was added.

## Validation

- `git diff --check` passed.
- Ruby YAML parsing verified `LANES.yaml` and `LANE-STATE.yaml`.
- Reference validation found `SF-IPC-0001` in the falsifier, candidate,
  topology index, status, roadmap, Lane state, synthetic acceptance surface,
  and this Run record.
- Candidate validation confirmed provisional status, exactly nine core fields,
  and the direct-intra-packet-contradiction refusal.
- Synthetic acceptance, public-path, whitespace, and exact-footprint checks
  passed. No heavy job was started.

## Next-Work Handoff

- current work: `SF-IPC-0001`
- current disposition: `ENDPOINT_POSITIVE`
- durable priority owner: `ROADMAP.md`
- recommendation status: advisory
- recommended next: none until new public or synthetic material creates
  material pressure on a core field, refusal note, annotation, source gate, or
  correction-route gate
- switch signal: admitted direct material contradictions now require an
  explicit grade before a required field can pass
- overturning evidence: a bounded fixture showing this treatment incorrectly
  refuses a direct contradiction that is immaterial to the claimed field, or
  admits an undispositioned material contradiction as passed

## Receipt

- Closed: `2026-07-31T02:14:36-05:00`
- Phase / result: `progress` / `progressed`
- Service outcome: `progressed`
- Owner / Lane: `cai-systemic-failure` / `1`
- Starting revision: `a9968e3aa0f99fd66cdf82087c9ba1c8a1f60f7f`
- Actual footprint: `topology/SF-IPC-0001-intra-packet-contradiction.md`;
  `topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md`;
  `topology/README.md`; `STATUS.md`; `ROADMAP.md`; `LANE-STATE.yaml`;
  `tests/synthetic-acceptance.md`;
  `RUN-20260731-021436-cai-systemic-progress.md`.
- Owner effect:
  `RUN-20260731-021436-cai-systemic-progress#intra-packet-contradiction-gate`
- Material effect: the provisional candidate now refuses positive qualification
  when admitted evidence directly and materially contradicts a required field
  but the record leaves that conflict undispositioned.
- Lane revalidation: owner/governance and Lane digests, execute permission,
  directed-flow null, starting revision, empty emergency state, absent writer
  lock, and declared boundary matched before effects and close.
- Manifest SHA-256 / revision / definition / control:
  `7ee3081259d033a395f2ff1137a133cb036f42732d530fc0a38cda0448f16550` /
  `3` / `2` / `1`.
- Emergency-revocation SHA-256:
  `8a992d3eb3f61b51ef83aa7cb8f85a1865fd0bf76c1f690429fa200a1c698723`;
  matching entries: none.
- Required flows attested: `standard-run-safety-check`, `select-lane`,
  `create-run-plan`, `revalidate-lane-selection`, and `append-run-receipt`.
- Conditional flows invoked: `rerank-next-work`, `refresh-lane-state`, and
  `classify-artifact-disposition`.
- Required graph attested: `true`; exceptions: none.
- Method refs / effect: `[]` / `null`.
- External actions: GitHub commit and non-force push only.
- Uncertainty: the synthetic fixture validates refusal semantics, not a
  real-world source relationship, contradiction, failure, remedy, or schema
  acceptance.
- Attention route: none. Keep the candidate provisional; test again only on
  materially new public or synthetic pressure.
