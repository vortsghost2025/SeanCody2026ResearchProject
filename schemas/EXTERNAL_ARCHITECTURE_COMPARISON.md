# Canonical Schema: External Architecture Comparison

**Purpose:** Compare an outside public system with SYS-002 without inserting that system into Sean's historical lineage.

External convergence may show that a mechanism is independently discoverable, useful under recurring constraints, or part of an emerging design pattern. It cannot establish chronology, priority, influence, originality, or contact without separate evidence.

```yaml
EXTERNAL_ARCHITECTURE_COMPARISON:
  id: ARCH-EXT-001
  title: ""
  status: OPEN                 # OPEN | PARTIAL | SUPPORTED_COMPARISON | REJECTED | SPLIT

  source:
    project_or_system: ""
    organization: ""
    publication_or_artifact: ""
    publication_date: ""
    accessed_date: ""
    stable_locator: ""
    source_visibility: PUBLIC

  comparison_role:
    lineage_value: NONE        # NONE | POSSIBLE_CONTACT_LEAD | DOCUMENTED_CONTACT
    comparison_value: UNKNOWN  # LOW | MEDIUM | HIGH
    influence_or_contact: NOT_ESTABLISHED

  problem_constraints:
    - long-running agent work
    - disposable sessions
    - state loss risk
    - real repository or runtime
    - measurable objective
    - compute or time budget
    - consequential human decisions

  mechanisms_shared_with_SYS_002: []
  mechanisms_absent_or_not_shown: []
  mechanisms_unique_to_external_system: []
  mechanisms_distinctive_to_SYS_002: []

  control_structure:
    human_sets_objective: UNKNOWN
    human_sets_budget: UNKNOWN
    human_reviews_failures: UNKNOWN
    agent_operates_between_checkpoints: UNKNOWN
    environment_enforces_limits: UNKNOWN
    exact_enforcement_layer: UNKNOWN

  persistence_structure:
    session_memory_present: UNKNOWN
    persistence_medium: UNKNOWN
    reload_trigger: UNKNOWN
    state_schema_available: UNKNOWN
    failed_branches_preserved: UNKNOWN

  execution_structure:
    real_repo_or_runtime: UNKNOWN
    baseline_defined: UNKNOWN
    experiments_logged: UNKNOWN
    metrics_recorded: UNKNOWN
    checkpoints_recorded: UNKNOWN
    reproducible_from_public_artifacts: UNKNOWN

  ensemble_structure:
    multiple_independent_models: UNKNOWN
    role_specialization_across_models: UNKNOWN
    disagreement_preserved: UNKNOWN
    provenance_aware_synthesis: UNKNOWN
    human_final_resolver: UNKNOWN

  independent_convergence_assessment:
    same_problem_class: UNKNOWN
    similar_constraints: UNKNOWN
    similar_mechanisms: []
    alternative_design_choices: []
    solution_space_significance: ""
    non_arbitrary_design_support: UNKNOWN

  evidence_for_comparison: []
  evidence_against_equivalence: []
  reproduction_gaps: []
  contact_or_exposure_searches: []

  prohibited_inferences:
    - priority
    - originality
    - copying
    - influence
    - direct contact
    - equivalence of a subsystem and the full architecture

  current_assessment:
    evidence_class: C
    confidence: LOW
    curator_note: ""

  related_question: RQ-030
  generated_session: SESSION-XXX
  last_reviewed: YYYY-MM-DD
```

## Evidence lanes

### 1. Lineage evidence

Dated artifacts showing what Sean built, used, changed, tested, or documented.

This lane can establish chronology, transitions, and internal development.

### 2. Independent-convergence evidence

Outside systems solving a similar problem with similar mechanisms where contact is not established.

This lane can support:

- recurring utility;
- discoverability from shared constraints;
- non-arbitrary design;
- architectural coherence;
- subsystem comparison.

It cannot establish Sean's chronology, influence, or priority.

### 3. External-divergence evidence

Outside systems solving the same problem differently.

This lane can reveal:

- which SYS-002 mechanisms are optional;
- which mechanisms are distinctive;
- alternative control or memory structures;
- failure modes caused by omitted layers;
- places where SYS-002 may be overengineered or incomplete.

## Rules

1. External artifacts use `ARCH-EXT-*`, never the internal `ARCH-*` lineage sequence.
2. Similarity alone remains `EXTERNAL_COMPARISON`, not `DOCUMENTED_INFLUENCE`.
3. Record the shared problem constraints before comparing mechanisms.
4. Compare a subsystem with the corresponding SYS-002 layer, not automatically with the whole architecture.
5. Preserve meaningful differences and absent mechanisms.
6. A commercially polished external system is not automatically better evidence than a dated internal artifact.
7. Performance claims require run artifacts, logs, metrics, configurations, and reproduction evidence.
8. Independent convergence can corroborate coherence but not originality.
