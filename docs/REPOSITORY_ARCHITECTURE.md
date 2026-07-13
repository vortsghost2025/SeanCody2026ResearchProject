# Sean & Cody Research Project — Repository Architecture v2.0

**Established:** 2026-07-13  
**Trigger:** SESSION_022  
**Principle:** Sessions are delivery vehicles. The structured corpus is the product.

## Top-level structure

```text
research_inbox/          raw, unreviewed acquisitions
sessions/                archived session logs after ingestion
schemas/                 object and validation schemas
graph/
  entities/
    people/
    organizations/
    publications/
    locations/
    expeditions/
  claims/
  sources/
  motifs/
  transmissions/
  negative_evidence/
  systems/
research_questions/      first-class agent work queue
data/claims/              canonical claim records
data/quarantine/          unresolved or nonconforming records
reports/                  synthesis and ingestion reports
project_audit/            significant QC, migration, and recovery notes
```

## Workflow

1. Research tools and contributors place raw output in `research_inbox/`.
2. Curator performs source-role separation, entity resolution, duplicate detection, evidence classification, and schema validation.
3. Accepted objects move into canonical graph/data locations.
4. Unresolved claims move to quarantine.
5. Failed or incomplete searches become negative-evidence records.
6. Open problems become research-question objects.
7. The original session is archived unchanged under `sessions/`.

## Session acquisition summary

Every ingested session should end with a machine-readable summary containing:

- session ID and date
- focus
- new entities, publications, sources, claims, and edges
- citation links, documented influence links, and shared motifs
- negative records and quarantines
- generated research questions
- primary sources verified and pending
- discrepancies flagged
- ingestion status and curator sign-off

## Frozen ontology

The core object types are:

- canonical record
- entity
- source
- claim
- motif
- system
- transmission edge
- research question
- negative-evidence record
- session acquisition

Architecture changes after v2.0 should be incremental unless a demonstrated structural limitation requires migration.