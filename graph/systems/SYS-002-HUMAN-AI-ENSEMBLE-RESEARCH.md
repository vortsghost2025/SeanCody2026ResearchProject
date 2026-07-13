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

  privacy_rule: >
    Extract architecture, chronology, model behavior, and workflow lessons from
    private projects. Do not copy financial data, credentials, private code,
    operational details, unrelated private content, or model scratchpads into
    the public corpus when a sanitized evidence record is sufficient.

  related_questions:
    - RQ-030

  related_documents:
    - RESEARCH_ATLAS.md
    - graph/systems/SYS-002-ARTIFACT-REGISTRY.md
    - research_inbox/SESSION_024_KILO_PUBLIC_GENESIS_ACQUISITION.md
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

## Current acquisition target

The public July genesis is partially established. The next target is the earlier private lineage: independent LM Arena branches, Copilot/Claude implementation records, checkpoint/state files, and recommendation-to-test-to-regression chains.

See [RQ-030](../../research_questions/RQ-030-ENSEMBLE-ARCHITECTURE-LINEAGE.md).
