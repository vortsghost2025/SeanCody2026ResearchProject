# SESSION 035 — NVIDIA / Codex AutoResearch Video Manifest

> **Input class:** public external comparison artifact supplied by Sean  
> **System:** `SYS-002 — Human–AI Ensemble Research Architecture`  
> **Status:** preserved as external comparison; not part of Sean's documented lineage

```yaml
SOURCE:
  session: SESSION_035
  platform: YouTube
  video_id: qP0uXRbg9hc
  url_supplied: "https://youtube.com/watch?v=qP0uXRbg9hc"
  source_title_as_transcribed: "Agent-Led Coding and Research"
  presenters_as_transcribed:
    - Chris
    - Vin_or_Ving
  organizations_or_products_named:
    - NVIDIA
    - NeMo RL
    - NeMo Gym
    - Brev
    - Codex
  transcript_filename: "Pasted text(7).txt"
  source_visibility: PUBLIC
  publication_date: UNKNOWN_FROM_TRANSCRIPT
  accessed: 2026-07-14
```

## 1. Workflow described

The video presents an agent-led machine-learning research workflow in which an agent can:

- set up a remote GPU environment;
- clone and modify a real repository;
- read a paper and implement an algorithm;
- install and repair dependencies;
- execute smoke tests and training runs;
- monitor experiments and GPU activity;
- track metrics;
- retain session decisions and progress;
- continue after interruption;
- stop or resize experiments according to a budget;
- summarize results for human review.

The transcript describes three supporting skills:

1. **Brev etiquette** — operational rules for using the remote environment and storing large files/checkpoints;
2. **session memory** — preservation of goals, decisions, paths, and progress;
3. **autoresearch loop** — establish a baseline, run experiments, track metrics, stop at a goal or budget, and summarize.

## 2. Demonstrated human checkpoints

Despite the language of autonomy, the transcript shows repeated human supervision:

```text
agent attempts implementation and training
        ↓
human reviews dependency failure
        ↓
human tells agent to continue
        ↓
human reviews low accuracy
        ↓
human changes batch-size direction
        ↓
agent estimates excessive runtime
        ↓
human sets a 20-hour budget
        ↓
agent determines a bounded run and monitors it
```

The video explicitly concludes that human judgment remains important.

## 3. Mechanisms relevant to SYS-002

```yaml
MECHANISMS:
  externalized_session_state: SUPPORTED_BY_TRANSCRIPT
  goal_and_budget_constraints: SUPPORTED_BY_TRANSCRIPT
  agent_operates_on_real_repo_and_runtime: SUPPORTED_BY_TRANSCRIPT
  recommendation_to_execution_loop: SUPPORTED_BY_TRANSCRIPT
  failure_recovery_and_iteration: SUPPORTED_BY_TRANSCRIPT
  metrics_and_experiment_monitoring: SUPPORTED_BY_TRANSCRIPT
  human_checkpoint_review: SUPPORTED_BY_TRANSCRIPT
  isolated_compute_environment: SUPPORTED_BY_TRANSCRIPT
  paper_to_code_workflow: SUPPORTED_BY_TRANSCRIPT
  multi_model_diversity: NOT_SHOWN
  disagreement_preserved_as_data: NOT_SHOWN
  provenance_aware_cross_model_synthesis: NOT_SHOWN
  independent_model_branches: NOT_SHOWN
```

## 4. External convergence with Sean's architecture

The public workflow independently resembles several mechanisms already present in SYS-002:

- persistent state outside the immediate conversational turn;
- explicit operating rules encoded as skills;
- long-running agent work across real code and infrastructure;
- measurable baselines and results;
- failure → diagnosis → revised action loops;
- human judgment at consequential checkpoints;
- budget and stopping constraints;
- resumability after interruption.

## 5. Important differences

The workflow is primarily:

```text
one agent
+ one experiment environment
+ goal-driven optimization loop
+ human checkpoint supervision
```

Sean's architecture additionally emphasizes:

```text
multiple independent models
+ preserved disagreements
+ role specialization across models
+ provenance-aware comparison
+ cross-domain human connection detection
+ long-term repository graph
```

Therefore the video is an **external architectural comparison**, not evidence of the origin of Sean's system and not evidence that either side encountered the other.

## 6. Claims not independently established by the transcript

- The introductory claim that a Qwen counting task improves from roughly 25% to 96% is not accompanied by complete result artifacts in the supplied transcript.
- The exact contents and versions of the three skills are not included.
- The transcript does not provide repository commit hashes, experiment logs, final metrics, or complete reproduction instructions.
- The isolated environment's security properties are described, not audited here.
- `full-stack autonomy` is bounded by multiple human interventions in the demonstrated workflow.

## 7. Curator output

- `graph/systems/ARCH-EXT-001-NVIDIA-CODEX-AUTORESEARCH.md`
- updates to `graph/systems/SYS-002-HUMAN-AI-ENSEMBLE-RESEARCH.md`
- updates to `graph/systems/SYS-002-ARTIFACT-REGISTRY.md`
- updates to `research_questions/RQ-030-ENSEMBLE-ARCHITECTURE-LINEAGE.md`

## 8. Curator decision

```text
External comparison relevance: HIGH
Sean lineage evidence: NONE
Architectural convergence: SUPPORTED
Exact performance claims: UNVERIFIED_FROM_TRANSCRIPT
Multi-model ensemble evidence: NOT SHOWN
Human-supervised autonomy: SUPPORTED
```
