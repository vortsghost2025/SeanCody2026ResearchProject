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
    which mechanisms repeatedly worked, preserve lessons from failed systems,
    and compare the architecture with independently developed solutions to the
    same problem class without confusing comparison with ancestry.

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

  evidence_lanes:
    lineage:
      purpose: >
        Establish what Sean built, when it appeared, how it changed, and which
        artifacts document each transition.
      can_support:
        - chronology
        - internal development
        - implementation history
        - documented influence within Sean's own projects
        - priority relative to later dated artifacts
      requires:
        - dated internal artifacts
        - repository history
        - prompts or task records
        - implementation and test evidence

    independent_convergence:
      purpose: >
        Compare outside systems that encounter similar constraints and independently
        adopt similar mechanisms, with no contact or influence established.
      can_support:
        - recurring utility
        - discoverability from shared constraints
        - architectural coherence
        - non-arbitrary design
        - subsystem comparison
      cannot_support:
        - Sean's chronology
        - originality
        - priority
        - influence
        - copying
        - contact

    external_divergence:
      purpose: >
        Compare outside systems that solve the same problem differently, exposing
        which SYS-002 mechanisms are distinctive, optional, absent, or potentially
        overengineered.
      can_support:
        - alternative designs
        - missing-layer analysis
        - failure-mode comparison
        - subsystem boundaries
      cannot_support:
        - lineage or influence without contact evidence

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
    - external comparison artifacts with problem constraints and mechanisms separated
    - explicit contact searches before any influence inference

  do_not_treat_as_proof:
    - a file's recent upload date when its content is older
    - retrospective claims without a dated artifact
    - generic multi-agent terminology that appeared after the fact
    - model-generated claims of completeness or originality
    - similar architectures without evidence Sean encountered them
    - external public convergence as evidence of Sean's lineage
    - independent convergence as proof of originality or priority
    - an audit of a model output as proof that a different model performed the audit
    - an implementation task as proof that the implementation was executed or tested

  positive_resolution: >
    A source-supported chronology documents the major architectural transitions,
    with representative artifacts for model diversity, role specialization,
    persistent state, cross-model review, implementation verification, and the
    human curator role.

  corroboration_resolution: >
    Multiple external systems with no established contact encounter substantially
    similar constraints and independently adopt overlapping mechanisms, while
    meaningful differences remain explicit. This may corroborate the coherence and
    recurring utility of the mechanisms but does not resolve lineage.

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
    - ARCH-EXT-001
    - EXTERNAL-ARCHITECTURE-COMPARISON-SCHEMA
    - SESSION_024
    - SESSION_035

  generated_session: SESSION_023
  last_updated: 2026-07-14
```

## Evidence-lane rule

```text
LINEAGE
= dated internal development

INDEPENDENT CONVERGENCE
= similar mechanisms under similar constraints, without established contact

EXTERNAL DIVERGENCE
= alternative solutions revealing what is distinctive or optional
```

Only the lineage lane can establish the chronology of Sean's architecture. External convergence and divergence sit beside the lineage as architectural evidence, not inside it.

Use: [`schemas/EXTERNAL_ARCHITECTURE_COMPARISON.md`](../schemas/EXTERNAL_ARCHITECTURE_COMPARISON.md).

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

This is enough to keep RQ-030 at `PARTIAL`.

### What remains open

The July public sequence does not yet establish:

- the earliest same-prompt independent model branches;
- a verified different-provider critique;
- the earliest solver/critic/synthesizer/verifier design;
- the first recommendation → implementation → test → regression chain;
- the earliest checkpoint, state file, bootstrap, handoff, or onboarding record;
- the 2016–January 2026 chronology preceding the public July corpus.

## External comparison — ARCH-EXT-001

A public YouTube transcript supplied in Session 035 describes a Codex / NVIDIA NeMo / Brev AutoResearch workflow with:

- skills encoding environment rules;
- session memory preserving goals, paths, decisions, and progress;
- autonomous work across a repository and GPU runtime;
- paper-to-code implementation;
- smoke tests, dependency repair, and training runs;
- metric and GPU monitoring;
- human review after failures and weak results;
- compute-budget and stopping constraints;
- resumability after disconnection.

```text
human goal
        ↓
skill-constrained agent
        ↓
real repository + GPU environment
        ↓
experiment / failure / result
        ↓
human checkpoint and revised budget
        ↓
continued monitored execution
```

This is a high-value comparison because it independently converges on several mechanisms present in Sean's architecture:

- externalized memory;
- skills and operating rules;
- long-running real-system execution;
- measurable outcomes;
- failure recovery;
- budget control;
- human judgment.

It does not demonstrate:

- independent multi-model branches;
- solver/critic/synthesizer/verifier separation across models;
- disagreement preserved as first-class data;
- provenance-aware cross-model synthesis;
- cross-domain human entity resolution.

Therefore:

```yaml
ARCH-EXT-001:
  evidence_lane: INDEPENDENT_CONVERGENCE
  comparison_value: HIGH
  Sean_lineage_value: NONE
  influence_or_contact: NOT_ESTABLISHED
  performance_reproducibility: UNKNOWN
  solution_space_significance: >
    Similar constraints independently produce overlapping mechanisms, supporting
    the interpretation that externalized state, skills, human checkpoints, budgets,
    and monitored execution are coherent responses to a recurring agent-research
    problem rather than arbitrary personal preferences.
```

Read:

- [`ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md`](../graph/systems/ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md)
- [`SESSION_035_NVIDIA_CODEX_AUTORESEARCH_VIDEO_MANIFEST.md`](../research_inbox/SESSION_035_NVIDIA_CODEX_AUTORESEARCH_VIDEO_MANIFEST.md)

## Why independent convergence matters

Independent convergence can strengthen a bounded claim:

> When long-running agents face state loss, real-system failures, measurable objectives, finite budgets, and consequential choices, externalized memory, operating rules, monitored execution, and human checkpoints recur as practical solutions.

It cannot strengthen these claims without additional evidence:

- Sean invented the mechanisms first;
- the outside system copied Sean;
- Sean encountered the outside system;
- the two architectures are equivalent;
- the multi-model disagreement layer is implied by a single-agent execution loop.

```text
same constraints
+ independently similar mechanism
        = coherence / recurring-utility evidence

same mechanism
+ dated contact or exposure
        = possible influence test

similar mechanism alone
        ≠ lineage evidence
```

## External divergence as useful evidence

Outside systems that omit or replace SYS-002 mechanisms may be equally informative.

Examples of comparison questions:

- What happens when failed branches are summarized instead of preserved?
- What changes when one agent optimizes a metric but no independent critic exists?
- Is state stored as prose, schema, timeline, database, or hidden platform memory?
- Are budgets enforced by prompt, controller, infrastructure, or human supervision?
- Does the system preserve disagreement, or only the chosen result?
- Which layers are necessary for execution, and which are necessary for trustworthy research?

A divergent architecture may show that one SYS-002 component is distinctive, unnecessary for a certain task, or required only at larger scale.

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

## External comparison acquisition

Collect outside artifacts separately using the external-comparison schema:

- exact public skill files and version history;
- state or memory format;
- session-reload protocol;
- experiment and failure log schema;
- commit and checkpoint structure;
- budget-enforcement layer;
- public metrics and reproduction artifacts;
- evidence for or against independent branches and critic/verifier roles.

## Required lineage return format

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
- current Sean & Cody variant-preserving research workflow;
- external public agent-research systems, kept in separate convergence/divergence lanes.

Candidate does not mean verified. Each lineage stage needs a dated artifact. External comparisons require problem-constraint and mechanism analysis but never enter the lineage without documented contact.
