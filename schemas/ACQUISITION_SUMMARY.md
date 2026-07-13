# Canonical Schema: Acquisition Summary

**Version:** 1.0  
**Status:** Frozen with Repository Architecture v2.0  
**Purpose:** Provide a machine-readable closing record for every ingestion session.

```yaml
ACQUISITION_SUMMARY:
  session_id: SESSION_023
  date: 2026-07-13
  focus: "1948–1979 Shaver/Palmer transmission bridge"

  inputs:
    raw_documents: 0
    primary_sources: 0
    secondary_sources: 0
    model_outputs: 0

  objects_created:
    entities: 0
    publications: 0
    sources: 0
    claims: 0
    motifs: 0
    systems: 0
    chronologies: 0
    propagations: 0
    graph_edges: 0
    negative_records: 0
    research_questions: 0

  relationship_classes:
    direct_citation: 0
    known_copy: 0
    shared_publisher: 0
    personal_contact: 0
    documented_influence: 0
    mass_media_exposure: 0
    shared_motif: 0
    speculative_similarity: 0
    negative_evidence: 0
    unknown: 0

  quality_control:
    primary_sources_verified: 0
    primary_sources_pending: 0
    discrepancies_flagged: 0
    records_quarantined: 0
    duplicate_candidates: 0
    schema_violations: 0

  confidence:
    score: null
    scale: "0–10"
    rationale: TBD

  ingestion_status: NOT_STARTED   # NOT_STARTED | PARTIAL | COMPLETE | BLOCKED
  curator_sign_off: PENDING       # PENDING | APPROVED | REJECTED
  curator_notes: ""
```

## Rules

1. Counts describe committed canonical objects, not objects merely mentioned in raw research.
2. `primary_sources_verified` requires direct inspection of the artifact or an authoritative catalog record appropriate to the claim.
3. Quarantined material is counted separately and must not inflate canonical totals.
4. A session may be complete even with open research questions, provided all acquired material has been adjudicated.
5. The summary is filed under `project_audit/` and the raw session is archived under `sessions/` after ingestion.
