# Canonical Transmission Edge Schema

**Version:** 1.1

## Why this exists

`CONFIRMED` is not an edge type. It can mean that a publication exists, that one author cited another, that historians document influence, or merely that two sources share imagery. These must remain separate.

## Edge types

### Citation and contact

- `DIRECT_CITATION` — source explicitly names another source; requires page or verifiable quotation.
- `KNOWN_COPY` — a physical or digital copy is documented in a subject's possession.
- `PERSONAL_CONTACT` — documented meeting, correspondence, or institutional contact.
- `SHARED_PUBLISHER` — common publishing environment; indicates opportunity for exposure, not influence.

### Influence and exposure

- `DOCUMENTED_INFLUENCE` — academic, biographical, or primary evidence demonstrates that A shaped B or the surrounding field.
- `MASS_MEDIA_EXPOSURE` — circulation and audience overlap establish plausible exposure, but not actual reading or influence.

### Motif relationships

- `SHARED_MOTIF` — both sources contain a documented idea-complex, but no transmission path is established.
- `SPECULATIVE_SIMILARITY` — resemblance exists but evidence or source verification is too thin for `SHARED_MOTIF`.
- `INDEPENDENT_PARALLEL` — evidence supports separate development.
- `RETROACTIVE_REINTERPRETATION` — a later source imposes a newer meaning on earlier material.

### Negative and unknown

- `NEGATIVE_EVIDENCE` — a documented search failed to find an expected relationship; scope and limits must be recorded.
- `UNKNOWN` — insufficient evidence in either direction.

## Edge object

```yaml
EDGE:
  id: EDGE-001
  from_entity: ENTITY-Palmer-001
  to_entity: ENTITY-FlyingSaucerCulture-001
  edge_type: DOCUMENTED_INFLUENCE
  evidence:
    - source_id: SRC-004
      page_or_section: TBD
      note: Academic or biographical argument supporting the edge
  confidence: HIGH
  primary_verified: false
  research_status: QUARANTINED
  curator_notes: >
    Explain exactly what is proven, what is inferred, and why this edge type
    was chosen instead of a stronger or weaker one.
  added_session: SESSION_022
  last_reviewed: 2026-07-13
```

## Rule

A strong source can verify that an argument was published without proving the historical relationship asserted by that argument. Edge confidence must evaluate the relationship itself.