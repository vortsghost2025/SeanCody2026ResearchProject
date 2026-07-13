# Sean & Cody Research Project — Repository Architecture v2.0

**Established:** 2026-07-13  
**Trigger:** SESSION_022  
**Status:** FROZEN  
**Principle:** Sessions are delivery vehicles. The structured corpus is the product.

## Object hierarchy

```text
SYSTEM
  contains and relates Entities, Sources, Claims, Motifs,
  Chronologies, Propagations, Edges, Questions, and Negative Records

ENTITY
  person | organization | publication | location | expedition | concept

SOURCE
  a primary, secondary, tertiary, archival, catalog, or testimonial artifact

CLAIM
  a specific sourced assertion with truth-state separation

MOTIF
  an idea-complex tracked across sources without presuming transmission

CHRONOLOGY
  the event sequence of an object through claimed, source, manuscript,
  publication, translation, rediscovery, amplification, and internet dates

PROPAGATION
  movement through geography, culture, language, institutions, and media,
  including what changed at every transition

EDGE
  a typed relationship between any two compatible objects

RESEARCH_QUESTION
  a first-class work-queue object with resolution criteria

NEGATIVE_RECORD
  a documented search and null or adverse result

QUARANTINE
  unverified, contradictory, malformed, or insufficiently sourced material
```

## Repository structure

```text
research_inbox/          raw, unreviewed acquisitions and session briefs
sessions/                archived acquisition logs after ingestion
schemas/                 object definitions and validation rules
graph/
  systems/
  entities/
    people/
    organizations/
    publications/
    locations/
    expeditions/
  sources/
  claims/
  motifs/
  chronologies/
  propagations/
  transmissions/
  negative_evidence/
research_questions/      first-class agent work queue
data/claims/              existing canonical claim records
data/quarantine/          existing unresolved or nonconforming records
quarantine/               graph-era quarantine records and adjudication notes
reports/                  synthesis and ingestion reports
project_audit/            QC, discrepancy, migration, and acquisition summaries
```

The existing `data/` paths remain valid. New graph-era objects use `graph/`; migration is incremental rather than destructive.

## Workflow

1. Research tools and contributors place raw output in `research_inbox/`.
2. The curator separates source existence, claim existence, historical truth, and factual truth.
3. Entity resolution, duplicate detection, chronology validation, propagation mapping, evidence classification, and schema validation are performed.
4. Accepted objects move into canonical graph/data locations.
5. Unresolved claims move to quarantine.
6. Failed or incomplete searches become negative-evidence records.
7. Open problems become research-question objects.
8. The original session is archived unchanged under `sessions/`.
9. A machine-readable acquisition summary is filed under `project_audit/`.

## Frozen edge taxonomy

- `DIRECT_CITATION`
- `KNOWN_COPY`
- `SHARED_PUBLISHER`
- `PERSONAL_CONTACT`
- `DOCUMENTED_INFLUENCE`
- `MASS_MEDIA_EXPOSURE`
- `SHARED_MOTIF`
- `SPECULATIVE_SIMILARITY`
- `NEGATIVE_EVIDENCE`
- `UNKNOWN`

Edge type describes the relationship. Evidence class describes the quality of support for that relationship.

## Evidence classes

- **A:** Confirmed source or event exists.
- **B:** Well-supported interpretation.
- **C:** Plausible but unverified.
- **D:** Testimonial or narrative evidence.
- **E:** Contradicted or highly implausible.

These classes do not replace the separate truth fields in canonical records.

## Session acquisition summary

Every ingested session closes using `schemas/ACQUISITION_SUMMARY.md`. Counts include only adjudicated and committed objects—not every item mentioned in raw model output.

## Freeze policy

Permitted without reopening the architecture:

- additive schema fields that preserve existing meaning;
- new object instances;
- new research questions and status changes;
- new edge types only when existing taxonomy demonstrably cannot express the relationship;
- corrective migrations with explicit audit records.

Requires an explicit architecture revision:

- adding a new top-level object type;
- changing evidence-class definitions;
- renaming or semantically changing frozen edge types;
- destructive relocation of canonical data.

Future sessions feed this architecture. They do not redesign it unless ingestion exposes a demonstrated structural failure.
