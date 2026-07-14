# SYS-002 — Human–AI Ensemble Research Architecture

```yaml
SYSTEM:
  id: SYS-002
  title: "Human–AI Ensemble Research Architecture"
  status: ACTIVE_SEEDING
  created: 2026-07-13

  purpose: >
    Reconstruct and formalize the architecture through which Sean used multiple
    AI models, persistent repositories, role specialization, cross-model review,
    verification, and human connection-detection to produce knowledge that
    survives individual chat sessions and model replacements.

  core_principle: >
    Models and sessions are replaceable processing components. The persistent,
    provenance-aware system is the product.

  human_role:
    - notices connections across apparently separate domains
    - selects or supplies puzzle pieces
    - detects when model outputs diverge meaningfully
    - provides historical and project context
    - acts as final entity resolver and system-level judge

  model_roles:
    - acquisition researcher
    - solver
    - critic
    - synthesizer
    - verifier
    - curator
    - source checker
    - contradiction auditor
    - implementation agent

  persistent_objects:
    - raw model outputs
    - source records
    - claims
    - disagreements
    - implementation decisions
    - test results
    - regressions
    - handoffs
    - state files
    - research questions
    - negative evidence

  architecture_stages:
    - same task sent to multiple models
    - outputs preserved independently
    - differences classified
    - recommendations tested or implemented
    - consequences recorded
    - failures become new evidence
    - useful structure enters persistent repository
    - next agent receives explicit state instead of relying on chat memory

  current_source_classes:
    - thousands of comparative model-test documents
    - ai-ensemble-lab proof of concept
    - private January 2026 development archive
    - Copilot and Claude handoff/state protocols
    - LM Arena A/B reviews and implementation records
    - public July 12, 2026 Sean & Cody genesis sequence
    - later Hermes, lane, subagent, and control-plane experiments
    - current Sean & Cody research workflow
    - external public agent-research comparison artifacts

  privacy_rule: >
    Extract architecture, chronology, model behavior, and workflow lessons from
    private projects. Do not copy financial data, credentials, private code,
    operational details, unrelated private content, or model scratchpads into
    the public corpus when a sanitized evidence record is sufficient.

  external_comparison_rule: >
    Public systems with similar mechanisms may be compared to SYS-002, but similarity
    is not evidence that Sean encountered them, that they encountered Sean's work,
    or that either architecture caused the other.

  related_questions:
    - RQ-030

  related_documents:
    - RESEARCH_ATLAS.md
    - graph/systems/SYS-002-ARTIFACT-REGISTRY.md
    - graph/systems/ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md
    - research_inbox/SESSION_024_KILO_PUBLIC_GENESIS_ACQUISITION.md
    - research_inbox/SESSION_035_NVIDIA_CODEX_AUTORESEARCH_VIDEO_MANIFEST.md
    - docs/PUZZLE_PIECE_INTAKE.md
    - docs/REPOSITORY_ARCHITECTURE.md
```

## System boundary

SYS-002 is not a trading system, a mythology, or a single software product. It is the recurring research architecture visible across multiple projects and domains.

A project belongs in SYS-002 only when it provides evidence about one or more of these mechanisms:

- independent model diversity;
- adversarial or complementary model roles;
- persistent state outside the model;
- provenance-preserving synthesis;
- human-in-the-loop connection detection;
- implementation and verification of model recommendations;
- preservation of disagreement, failure, or regression as data.

An external comparison may document only a subset. It must not be treated as equivalent to the entire system.

## Established public evidence

The first curated public batch establishes this July 12, 2026 sequence:

```text
ARCH-001 — Sean creates a cross-domain seed corpus
        ↓
ARCH-002 — ChatGPT adds a specialized provenance/QC layer
        ↓
ARCH-003 — a later session explicitly audits and applies that layer
        ↓
ARCH-004 — combined session state preserves deltas and assigns implementation tasks
```

Read the evidence registry:

- [`SYS-002-ARTIFACT-REGISTRY.md`](SYS-002-ARTIFACT-REGISTRY.md)

Important limits:

- Session 003 proves an audit of a ChatGPT artifact; it does not identify the auditing model.
- Session 004 specifies an implementation script; it does not prove execution or testing.
- The July sequence is the earliest public evidence currently curated, not the earliest architecture evidence overall.

## External convergence example — NVIDIA / Codex AutoResearch

A supplied 2026 public video transcript describes a Codex-based NeMo/Brev workflow with:

- environment-specific skills;
- persistent session memory;
- paper-to-code and goal-driven experiment loops;
- real repository and GPU execution;
- dependency repair and failure recovery;
- metric and GPU monitoring;
- compute-budget and stopping rules;
- resumability after interruption;
- repeated human review and redirection.

```text
human goal
        ↓
skill-constrained agent
        ↓
repository + GPU runtime
        ↓
experiment / failure / metric
        ↓
human checkpoint
        ↓
revised parameters or budget
        ↓
continued monitored execution
```

This independently converges with several SYS-002 mechanisms, especially externalized state, operating rules, execution against real systems, failure tracking, and human judgment.

It does **not** show:

- independent multi-model branches;
- cross-model critic or verifier roles;
- disagreement preserved as a persistent object;
- provenance-aware synthesis across models;
- human cross-domain entity resolution.

Read: [`ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md`](ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md).

## Working lineage

```text
comparative model experiments
        ↓
manual same-question branching
        ↓
solver / critic / synthesizer / verifier concept
        ↓
model reviews applied to real repositories
        ↓
repo-based handoffs and persistent state
        ↓
role/persona continuity across disposable agents
        ↓
lanes, subagents, control planes, and orchestration
        ↓
provenance-aware research graph with first-class disagreements and RQs
```

Every arrow remains a working hypothesis until supported by dated artifacts.

External comparison artifacts sit beside this lineage rather than inside it unless historical contact or influence is documented.

## Key distinction

Earlier ensemble designs often treated disagreement as something to resolve into one final answer.

The current architecture treats disagreement as a persistent object:

```text
disagreement
  ├── provenance
  ├── model identity
  ├── source differences
  ├── contradiction type
  ├── implementation consequence
  ├── later correction
  └── new research question
```

The external AutoResearch example demonstrates an execution loop, but the supplied transcript does not demonstrate this disagreement-preservation layer.

## Current acquisition target

The public July genesis is partially established. The next lineage target remains the earlier private record: independent LM Arena branches, Copilot/Claude implementation records, checkpoint/state files, and recommendation-to-test-to-regression chains.

External comparison acquisition may proceed separately by collecting exact skill files, public repositories, experiment artifacts, and documented human/agent control boundaries.

See [RQ-030](../../research_questions/RQ-030-ENSEMBLE-ARCHITECTURE-LINEAGE.md).
