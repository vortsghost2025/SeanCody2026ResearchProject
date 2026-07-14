# ARCH-EXT-001 — NVIDIA / Codex AutoResearch Workflow

```yaml
EXTERNAL_ARCHITECTURE_ARTIFACT:
  artifact_id: ARCH-EXT-001
  system: SYS-002
  status: EXTERNAL_COMPARISON
  lineage_role: NONE

  source:
    platform: YouTube
    video_id: qP0uXRbg9hc
    source_title_as_transcribed: "Agent-Led Coding and Research"
    publication_date: UNKNOWN_FROM_TRANSCRIPT
    accessed: 2026-07-14
    transcript_record: research_inbox/SESSION_035_NVIDIA_CODEX_AUTORESEARCH_VIDEO_MANIFEST.md

  described_stack:
    - Codex
    - NVIDIA NeMo RL
    - NVIDIA NeMo Gym
    - Brev GPU environment

  workflow:
    - configure isolated remote compute
    - read paper or receive experiment goal
    - modify repository code
    - execute smoke tests
    - resolve software and dependency failures
    - launch training runs
    - monitor GPU and metrics
    - preserve goals, paths, decisions, and progress
    - adjust experiments under human direction
    - stop according to goal or compute budget
    - summarize results

  skills_described:
    - BREV_ETIQUETTE
    - SESSION_MEMORY
    - AUTORESEARCH_LOOP

  mechanisms_supported:
    - EXTERNALIZED_STATE
    - OPERATING_RULES_AS_SKILLS
    - GOAL_DRIVEN_AGENT_LOOP
    - REAL_REPOSITORY_EXECUTION
    - EXPERIMENT_AND_METRIC_TRACKING
    - FAILURE_RECOVERY
    - HUMAN_CHECKPOINT_REVIEW
    - BUDGET_AWARE_STOPPING
    - RESUMABILITY
    - ISOLATED_COMPUTE_ENVIRONMENT

  mechanisms_not_shown:
    - INDEPENDENT_MULTI_MODEL_BRANCHING
    - CROSS_MODEL_CRITIQUE
    - DISAGREEMENT_AS_PERSISTENT_DATA
    - PROVENANCE_AWARE_ENSEMBLE_SYNTHESIS
    - HUMAN_CROSS_DOMAIN_ENTITY_RESOLUTION

  evidence_class:
    workflow_description: A_FOR_TRANSCRIPT_CONTENT
    actual_reproducibility: UNKNOWN
    final_performance_claims: UNVERIFIED_FROM_TRANSCRIPT
    security_claims: DESCRIBED_NOT_AUDITED

  curator_note: >
    The artifact is a high-value external convergence example. It independently presents
    persistent session memory, explicit skills, long-running repository and GPU work,
    experiment monitoring, budget constraints, failure recovery, and human judgment.
    It does not establish any historical relationship to Sean's architecture and does
    not demonstrate the multi-model disagreement-preservation layer central to SYS-002.

  generated_session: SESSION_035
  last_reviewed: 2026-07-14
```

## Architecture shown

```text
human goal
        ↓
skill-constrained coding agent
        ↓
repository + GPU runtime
        ↓
baseline / implementation / experiment
        ↓
metrics + failures + runtime estimate
        ↓
human checkpoint
        ↓
revised parameters or budget
        ↓
continued monitored run
        ↓
result summary
```

## Three skills

### Brev etiquette

Encodes environment-specific operational knowledge, including where to place large files and checkpoints. This reduces repeated documentation lookup and constrains how the agent uses infrastructure.

### Session memory

Tracks:

- goal;
- important decisions;
- file paths;
- current progress;
- latest instructions;
- resumable state after disconnection.

### AutoResearch loop

```text
run baseline
        ↓
try experiments
        ↓
track metrics
        ↓
compare against goal and budget
        ↓
continue, stop, or summarize
```

## Human supervision observed

The transcript documents several interventions:

1. the first implementation reached a dependency/driver barrier;
2. the human reviewed the result and told the agent to continue;
3. the agent later completed training but produced low accuracy;
4. the human directed larger batch sizes and additional training;
5. the agent estimated that a requested run could take roughly 100 hours;
6. the human imposed a 20-hour total budget;
7. the agent selected a bounded run and continued monitoring.

This is best classified as **human-supervised autonomy**, not unattended full autonomy.

## Comparison with SYS-002

| Mechanism | External workflow | Sean / SYS-002 |
|---|---|---|
| Persistent session state | Yes | Yes |
| Skills / operating rules | Yes | Yes, through schemas, briefs, profiles, and state protocols |
| Real repository execution | Yes | Yes |
| Experiment/test consequence tracking | Yes | Yes, historically partial and under acquisition |
| Human judgment | Yes | Yes, central |
| Budget/stopping rules | Yes | Present in agent routing and operational constraints |
| Multiple independent models | Not shown | Central target mechanism |
| Preserved disagreement | Not shown | Central current mechanism |
| Cross-model roles | Not shown | Solver/critic/synthesizer/verifier lineage |
| Provenance graph across domains | Not shown | Central current repository design |

## Why this matters

The artifact suggests that several mechanisms Sean developed through practical multi-agent work are becoming recognizable public patterns in agent-led research:

```text
skills
+ persistent memory
+ monitored execution
+ explicit budgets
+ human checkpoints
+ measured outcomes
```

The convergence is historically interesting, but it must not be used to claim:

- priority;
- influence;
- copying;
- direct contact;
- equivalence between single-agent autoresearch and a provenance-preserving ensemble.

## Open comparison questions

1. Are the skill files publicly available with version history?
2. Does session memory persist as a structured file, timeline, database, or hidden platform state?
3. Are experiment decisions and failed branches preserved or only summarized?
4. Does the system support independent agent branches and adversarial review?
5. Can the result be reproduced from published commits, configurations, checkpoints, and metrics?
6. How are compute budgets enforced—prompt instruction, controller, or infrastructure limit?
7. What happens when a long-running agent's summary is incorrect or incomplete?
