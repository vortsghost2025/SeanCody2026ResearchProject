# SYS-002 — Architecture Artifact Registry

This registry records dated evidence for the Human–AI Ensemble Research Architecture. An artifact documents what happened; it does not prove originality, completeness, or successful implementation beyond what its source actually shows.

## Status key

- **CONFIRMED:** the cited public artifact directly supports the described mechanism.
- **PARTIAL:** the artifact supports part of the mechanism, but an important step remains unverified.
- **UNKNOWN:** the available artifact does not establish the missing detail.

---

## ARCH-001 — Human seed method: separate source from interpretation

```yaml
ARCHITECTURE_ARTIFACT:
  artifact_id: ARCH-001
  date: 2026-07-12
  project: Sean & Cody 2026 Research Project
  source_visibility: PUBLIC
  file_or_document: Seanfirstentryjuly12
  stable_locator: https://github.com/vortsghost2025/SeanCody2026ResearchProject/blob/main/Seanfirstentryjuly12
  model_or_models: Sean David Ramsingh — human-origin research sweep
  prompt_or_task: Create the first cross-domain corpus covering serpent motifs, Grey imagery, Hollow Earth, Antarctica/maps, and UFO/contactee chains.
  mechanism_demonstrated: Human connection detection and evidence-layer separation before later model formalization.
  exact_quote: "The artifact is Class A. The interpretation that links them to Grey aliens is Class C/D — it is a retroactive modern reading. These must be stored as separate claims."
  human_action: Sean separated physical-artifact existence from later alien interpretation and treated each as a different claim with its own source trail.
  implementation_consequence: The distinction became a project-wide QC rule in Session 002 and was applied to records in Sessions 003–004.
  later_validation_or_regression: CONFIRMED as a recurring method; earliest private precursor remains unknown.
  evidence_class: A
  privacy_notes: None; public source.
  unresolved_questions: Determine which parts of the first sweep originated in earlier private comparative-model work.
```

**Source support:** Session 001 identifies itself as a 68-record first sweep and already separates artifact evidence from interpretation evidence in the Dogū record.

---

## ARCH-002 — Specialized model role extends, rather than replaces, the human corpus

```yaml
ARCHITECTURE_ARTIFACT:
  artifact_id: ARCH-002
  date: 2026-07-12
  project: Sean & Cody 2026 Research Project
  source_visibility: PUBLIC
  file_or_document: ChatGPTfirstentryjuly12.md — Research Session 002
  stable_locator: https://github.com/vortsghost2025/SeanCody2026ResearchProject/blob/main/ChatGPTfirstentryjuly12.md
  model_or_models: ChatGPT / OpenAI; exact model version not recorded
  prompt_or_task: Respond to Sean's first sweep as source auditor, chronology checker, map-layer designer, and narrative-link analyst.
  mechanism_demonstrated: Role specialization and additive work on an existing corpus instead of restarting from a blank answer.
  exact_quote: "This entry adds the next layer: provenance control and time-aware geography."
  human_action: The model was directed at an existing human-created corpus with a bounded specialist role.
  implementation_consequence: Produced QC-001 through QC-006, the multi-map method, and a typed relationship vocabulary later used by the project.
  later_validation_or_regression: PARTIAL — the methodology was strong, but Session 003 found it had not yet corrected the underlying records.
  evidence_class: A
  privacy_notes: None; public source.
  unresolved_questions: The exact original prompt and exact ChatGPT model version are not preserved in this file.
```

---

## ARCH-003 — One session explicitly audits a prior model output

```yaml
ARCHITECTURE_ARTIFACT:
  artifact_id: ARCH-003
  date: 2026-07-12
  project: Sean & Cody 2026 Research Project
  source_visibility: PUBLIC
  file_or_document: Research Session 003 · July 12, 2026
  stable_locator: https://github.com/vortsghost2025/SeanCody2026ResearchProject/blob/main/Research%20Session%20003%20%C2%B7%20July%2012%2C%202026
  model_or_models: UNKNOWN — the file audits ChatGPT Entry 001, but does not identify the auditing model or prove that it was a different provider
  prompt_or_task: Audit ChatGPT Entry 001 against Session 001, apply its QC flags, resolve schema conflicts, and produce working standards.
  mechanism_demonstrated: Prior model output is treated as an auditable artifact; strengths, omissions, conflicts, and corrections are preserved.
  exact_quote: "The ChatGPT entry is entirely methodological. It produced zero new data records. It identified problems but did not fix any of them in the existing dataset."
  human_action: The workflow retained the audit and its disagreements rather than silently replacing the earlier entry.
  implementation_consequence: Corrected named records, applied connection types to convergence claims, and converted hypotheses into structured records.
  later_validation_or_regression: CONFIRMED as cross-session audit; cross-model identity remains UNKNOWN.
  evidence_class: A for the audit document; C for any claim that the auditor was Claude or another specific model.
  privacy_notes: None; public source.
  unresolved_questions: Identify the auditing model/provider from an original chat export or platform metadata.
```

**Critical correction to the Kilo acquisition:** the existence of an audit proves cross-session review of model output. It does **not** by itself prove a different model performed the audit.

---

## ARCH-004 — Combined state, delta records, and an implementation task

```yaml
ARCHITECTURE_ARTIFACT:
  artifact_id: ARCH-004
  date: 2026-07-12
  project: Sean & Cody 2026 Research Project
  source_visibility: PUBLIC
  file_or_document: SESSIONS 004 + 005 + 006 — COMBINED MASTER OUTPUT
  stable_locator: https://github.com/vortsghost2025/SeanCody2026ResearchProject/blob/main/SESSIONS%20004%20%2B%20005%20%2B%20006%20%E2%80%94%20COMBINED%20MASTER%20OUTPUT
  model_or_models: UNKNOWN — model/provider is not stated in the artifact
  prompt_or_task: Carry the audited schema through the corpus, preserve cumulative state, and specify executable upgrade work.
  mechanism_demonstrated: Externalized continuity through a combined session state, delta-record method, cumulative counts, and explicit agent tasks.
  exact_quote: "Rather than reprint every field of every record that has no changes, this session documents delta records — what changed and why."
  human_action: The repository became the continuity layer; later work was instructed to replace obsolete records rather than preserve silent duplicates.
  implementation_consequence: Specifies scripts/schema_upgrade_v1.py and structured data deliverables as agent tasks.
  later_validation_or_regression: PARTIAL — this artifact proposes the script and schema pass but does not prove the script was executed, tested, or committed.
  evidence_class: A for the combined document and implementation specification; UNKNOWN for execution outcome.
  privacy_notes: None; public source.
  unresolved_questions: Locate a later commit, test report, or generated file proving whether schema_upgrade_v1.py was run.
```

---

## Coverage of RQ-030 mechanisms

| Target mechanism | Earliest public evidence in this registry | Status |
|---|---|---|
| Human connection detector / final resolver | ARCH-001 | CONFIRMED |
| Specialist role architecture | ARCH-002 | CONFIRMED |
| One session audits prior model output | ARCH-003 | CONFIRMED |
| Different provider/model audits another | ARCH-003 | UNKNOWN |
| Persistent repository continuity | ARCH-004 | PARTIAL / early form |
| Recommendation implemented and tested | ARCH-004 | UNKNOWN — task specified only |
| Same problem independently sent to multiple models | Not established by these July 12 artifacts | OPEN |
| Disagreement preserved as a first-class object | Explicit in later Session 023 A/B workflow; earliest example still under search | OPEN |

## Current conclusion

The public repository establishes a clear July 12, 2026 sequence:

```text
human cross-domain seed corpus
        ↓
specialized ChatGPT methodology layer
        ↓
explicit audit of the ChatGPT layer
        ↓
combined persistent state + implementation tasks
```

This is strong evidence for the method's public-repository genesis, but it is not the beginning of the full architecture. Earlier January 2026 private artifacts and the older ensemble concept remain the next acquisition target.
