# RQ-030 — How did the human–AI ensemble research architecture evolve?

```yaml
RQ:
  id: RQ-030
  title: "What is the documented chronology through which Sean's model-comparison experiments evolved into a persistent human–AI ensemble research architecture?"
  status: PARTIAL
  priority: HIGH

  why_it_matters: >
    The current workflow appears to be the result of years of comparative model
    testing and several generations of architecture. Reconstructing the lineage
    can distinguish genuinely early ideas from later reinterpretation, identify
    which mechanisms repeatedly worked, and preserve lessons from failed systems.

  date_scope:
    start: 2016
    end: 2026

  target_mechanisms:
    - same problem given independently to multiple models
    - outputs compared for divergence and convergence
    - solver / critic / synthesizer / verifier role separation
    - one model reviewing another model's output
    - model recommendations implemented against a real system
    - post-implementation testing and regression discovery
    - repository-based state, handoff, checkpoint, and onboarding systems
    - persistent agent roles across disposable sessions
    - disagreement preserved as data
    - human acting as connection detector and final entity resolver

  evidence_needed:
    - dated documents or chat exports
    - repository paths and commit history
    - exact model/provider names when available
    - exact prompts or task descriptions
    - independent outputs or branch variants
    - human decisions made from those outputs
    - implementation records
    - tests, failures, regressions, and later corrections
    - exact quotations describing the architecture or philosophy

  do_not_treat_as_proof:
    - a file's recent upload date when its content is older
    - retrospective claims without a dated artifact
    - generic multi-agent terminology that appeared after the fact
    - model-generated claims of completeness or originality
    - similar architectures without evidence Sean encountered them
    - an audit of a model output as proof that a different model performed the audit
    - an implementation task as proof that the implementation was executed or tested

  positive_resolution: >
    A source-supported chronology documents the major architectural transitions,
    with representative artifacts for model diversity, role specialization,
    persistent state, cross-model review, implementation verification, and the
    human curator role.

  partial_resolution: >
    Several dated stages are established, but the earliest model-comparison
    experiments or transitions between stages remain uncertain.

  negative_resolution: >
    Available archives cannot establish chronology beyond retrospective accounts;
    the lineage remains a working reconstruction.

  privacy_constraints:
    - do not publish credentials or secrets
    - do not publish private financial or personal operational data
    - do not copy unrelated proprietary code
    - use sanitized quotations and structural descriptions when sources are private
    - do not publish model scratchpads or environment-specific tool chatter when a curated evidence record is sufficient

  related_objects:
    - SYS-002
    - SYS-002-ARTIFACT-REGISTRY
    - SESSION_024

  generated_session: SESSION_023
  last_updated: 2026-07-13
```

## First acquisition result — public July 12 genesis

The first acquisition batch establishes four dated public artifacts:

| Artifact | Date | Mechanism | Status |
|---|---|---|---|
| `ARCH-001` — Sean's first sweep | 2026-07-12 | Human connection detection and source/interpretation separation | CONFIRMED |
| `ARCH-002` — ChatGPT first research entry | 2026-07-12 | Specialist role extends an existing corpus | CONFIRMED |
| `ARCH-003` — Session 003 audit | 2026-07-12 | Prior model output audited, corrected, and preserved | CONFIRMED; auditor model UNKNOWN |
| `ARCH-004` — Sessions 004–006 combined | 2026-07-12 | Externalized cumulative state, delta records, implementation task | PARTIAL; execution/test UNKNOWN |

Read:

- [`SYS-002-ARTIFACT-REGISTRY.md`](../graph/systems/SYS-002-ARTIFACT-REGISTRY.md)
- [`SESSION_024_KILO_PUBLIC_GENESIS_ACQUISITION.md`](../research_inbox/SESSION_024_KILO_PUBLIC_GENESIS_ACQUISITION.md)

### What this resolves

The public repository supports this sequence:

```text
human seed corpus
        ↓
specialized ChatGPT methodology layer
        ↓
explicit audit of prior model work
        ↓
combined persistent state and agent-addressed implementation tasks
```

This is enough to move RQ-030 from `SEARCHING` to `PARTIAL`.

### What remains open

The July public sequence does not yet establish:

- the earliest same-prompt independent model branches;
- a verified different-provider critique;
- the earliest solver/critic/synthesizer/verifier design;
- the first recommendation → implementation → test → regression chain;
- the earliest checkpoint, state file, bootstrap, handoff, or onboarding record;
- the 2016–January 2026 chronology preceding the public July corpus.

## Next acquisition batch — earlier private lineage

Search the private January 2026 development archive and the earlier ensemble repository for three to five sanitized artifacts covering:

| Stage | Ideal artifact |
|---|---|
| Independent diversity | Same prompt/problem sent to multiple models with outputs preserved |
| Role architecture | Earliest solver/critic/synthesizer/verifier design |
| Cross-model implementation | Arena or other model feedback implemented by Copilot/Claude/another agent |
| Externalized continuity | Earliest checkpoint, handoff, state file, bootstrap, or onboarding protocol |
| Consequence tracking | Recommendation → code/system change → test → regression or validation |
| Human curator | Explicit evidence that Sean selected connections, resolved conflicts, or redirected models |
| Disagreement as data | Earliest record retaining variants rather than merging them into one answer |

## Required return format

```yaml
ARCHITECTURE_ARTIFACT:
  artifact_id:
  date:
  project:
  source_visibility: PUBLIC | PRIVATE | SANITIZED
  file_or_document:
  stable_locator:
  model_or_models:
  prompt_or_task:
  mechanism_demonstrated:
  exact_quote:
  human_action:
  implementation_consequence:
  later_validation_or_regression:
  evidence_class:
  privacy_notes:
  unresolved_questions:
```

## Initial candidate source families

- comparative documents predating modern ChatGPT usage;
- `ai-ensemble-lab-` theory and proof-of-concept files;
- January 2026 private development archive containing Copilot/Claude and LM Arena interactions;
- persistent-state, bootstrap, checkpoint, and handoff documents;
- Hermes, lane, subagent, and control-plane experiments;
- current Sean & Cody variant-preserving research workflow.

Candidate does not mean verified. Each stage needs a dated artifact.
