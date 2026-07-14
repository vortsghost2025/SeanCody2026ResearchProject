# ARCH-EXT-001 — NVIDIA / Codex AutoResearch Workflow

```yaml
EXTERNAL_ARCHITECTURE_COMPARISON:
  id: ARCH-EXT-001
  title: "NVIDIA / Codex AutoResearch Workflow"
  status: SUPPORTED_COMPARISON
  system: SYS-002

  source:
    platform: YouTube
    video_id: qP0uXRbg9hc
    source_title_as_transcribed: "Agent-Led Coding and Research"
    publication_date: UNKNOWN_FROM_TRANSCRIPT
    accessed_date: 2026-07-14
    transcript_record: research_inbox/SESSION_035_NVIDIA_CODEX_AUTORESEARCH_VIDEO_MANIFEST.md
    source_visibility: PUBLIC

  comparison_role:
    evidence_lane: INDEPENDENT_CONVERGENCE
    lineage_value: NONE
    comparison_value: HIGH
    influence_or_contact: NOT_ESTABLISHED

  described_stack:
    - Codex
    - NVIDIA NeMo RL
    - NVIDIA NeMo Gym
    - Brev GPU environment

  problem_constraints:
    - long-running agent work
    - disposable or interruptible session
    - state-loss risk
    - real repository and GPU runtime
    - measurable experiment objective
    - dependency and environment failures
    - finite compute and time budget
    - consequential human tradeoffs

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

  mechanisms_shared_with_SYS_002:
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

  mechanisms_absent_or_not_shown:
    - INDEPENDENT_MULTI_MODEL_BRANCHING
    - CROSS_MODEL_CRITIQUE
    - DISAGREEMENT_AS_PERSISTENT_DATA
    - PROVENANCE_AWARE_ENSEMBLE_SYNTHESIS
    - HUMAN_CROSS_DOMAIN_ENTITY_RESOLUTION

  control_structure:
    human_sets_objective: SUPPORTED
    human_sets_budget: SUPPORTED
    human_reviews_failures: SUPPORTED
    agent_operates_between_checkpoints: SUPPORTED
    environment_enforces_limits: UNKNOWN
    exact_enforcement_layer: UNKNOWN

  persistence_structure:
    session_memory_present: SUPPORTED
    persistence_medium: UNKNOWN
    reload_trigger: UNKNOWN
    state_schema_available: NOT_ACQUIRED
    failed_branches_preserved: UNKNOWN

  execution_structure:
    real_repo_or_runtime: SUPPORTED
    baseline_defined: SUPPORTED_BY_DESCRIPTION
    experiments_logged: PARTIAL_FROM_TRANSCRIPT
    metrics_recorded: SUPPORTED_BY_DESCRIPTION
    checkpoints_recorded: UNKNOWN
    reproducible_from_public_artifacts: UNKNOWN

  ensemble_structure:
    multiple_independent_models: NOT_SHOWN
    role_specialization_across_models: NOT_SHOWN
    disagreement_preserved: NOT_SHOWN
    provenance_aware_synthesis: NOT_SHOWN
    human_final_resolver: PARTIAL_AS_CHECKPOINT_JUDGE

  independent_convergence_assessment:
    same_problem_class: SUPPORTED
    similar_constraints: SUPPORTED
    similar_mechanisms:
      - externalized memory
      - encoded operating rules
      - monitored real-system execution
      - failure recovery
      - explicit budgets
      - human checkpoints
    alternative_design_choices:
      - single-agent optimization rather than multi-model disagreement
      - session memory not yet shown as a public provenance graph
    solution_space_significance: >
      Similar operational constraints independently produce several mechanisms also
      present in SYS-002. This supports the interpretation that externalized state,
      operating rules, monitored execution, budgets, and human checkpoints are coherent
      responses to a recurring agent-research problem class rather than arbitrary personal
      preferences. It does not corroborate the multi-model disagreement layer because that
      layer is not shown.
    non_arbitrary_design_support: SUPPORTED_FOR_SHARED_SUBSYSTEM

  evidence_for_comparison:
    - transcript describes all three skills
    - transcript shows repeated human intervention after failure and weak results
    - transcript describes state retained for resumption after disconnection
    - transcript describes budget-aware experiment planning and monitoring

  evidence_against_equivalence:
    - no independent model branches shown
    - no cross-model critic or verifier shown
    - no first-class disagreement object shown
    - no provenance-aware cross-domain synthesis shown

  reproduction_gaps:
    - exact skill files unavailable in supplied source
    - repository commit and configuration not acquired
    - experiment logs and checkpoints not acquired
    - final performance claim not independently reproducible from transcript
    - budget enforcement layer unknown
    - session-memory storage and reload protocol unknown

  prohibited_inferences:
    - priority
    - originality
    - copying
    - influence
    - direct contact
    - equivalence between the execution subsystem and full SYS-002 architecture

  current_assessment:
    evidence_class: A_FOR_TRANSCRIPT_CONTENT_B_FOR_ARCHITECTURAL_INTERPRETATION
    confidence: HIGH_FOR_COMPARISON_LOW_FOR_REPRODUCIBILITY
    curator_note: >
      High-value independent-convergence example for the agent-execution and continuity
      subsystem. No lineage value and no evidence of the disagreement-preserving ensemble layer.

  related_question: RQ-030
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

## Correct containment relationship

```text
ARCH-EXT-001
= agent-execution and continuity subsystem

SYS-002
= multi-model, provenance-aware research architecture
  that could contain one or more such subsystems
```

## Open acquisition questions

1. Are the skill files publicly available with version history?
2. Does session memory persist as a structured file, timeline, database, or hidden platform state?
3. What triggers memory reload after disconnection?
4. Are experiment decisions and failed branches preserved or only summarized?
5. Does the system support independent agent branches and adversarial review?
6. Can the result be reproduced from published commits, configurations, checkpoints, and metrics?
7. How are compute budgets enforced—prompt instruction, controller, or infrastructure limit?
8. Do checkpoints correspond to designed human-review boundaries or merely runtime events?
9. What happens when a long-running agent's summary is incorrect or incomplete?
