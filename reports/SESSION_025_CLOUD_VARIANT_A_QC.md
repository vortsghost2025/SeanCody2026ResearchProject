# SESSION 025 — Cloud Variant A QC

> ## TOP-LEVEL QC BANNER
>
> ```text
> Lead list: preserved
> Exact map records: 0
> Transmission edges: 0
> Canonical findings: 0
> RQ-031 status change: none
> ```
>
> Every Terra Australis / Antarctica statement in the reviewed cloud output remains `UNVERIFIED_LEAD`. `TERRA-MAP-001` through `TERRA-MAP-004` are `FAMILY_BUCKETS`, not artifacts.
>
> **Prohibition:** No claim in the reviewed lead file may be cited as evidence in synthesis, chronology, graph, lineage, or final-report tasks without a corresponding item-level primary-map record, institutional catalogue identifier, and stable archive/scan URL.

**Reviewed source:** `research_inbox/SESSION_025_CLOUD_VARIANT_A_LEADS.md`  
**Related question:** `RQ-031`  
**Decision:** PRESERVE AS LEADS; DO NOT PROMOTE TO MAP RECORDS

## What is useful

- Correctly identifies the transition from hypothetical southern continent to observed Antarctic geography as a constrained map-lineage problem.
- Separates early cosmographic traditions, sixteenth-century expansion, Dutch/Tasman-era differentiation, and Cook-era contraction into workable research waves.
- Identifies candidate mapmaker families that can be tested against institutional scans.
- Proposes a deliverable compatible with the repository’s chronology and transmission-edge methods.

## Blocking deficiencies

1. **Citation placeholders only.** `[archive]`, `[nationalarchives.gov]`, and `[static-prod.lib.princeton]` are not usable citations or stable locators.
2. **No artifact-level records.** `TERRA-MAP-001` through `004` are broad `FAMILY_BUCKETS`, not exact maps or editions.
3. **No catalogue metadata.** Titles, creators, dates, editions, publishing cities, institutions, call numbers/shelfmarks, and catalogue IDs are absent.
4. **No exact map text.** No legend, annotation, southern label, plate number, or translated quotation is supplied.
5. **No demonstrated transmission edges.** The response does not prove copying, translation, citation, engraving lineage, or documented influence.
6. **Cook-era wording is too strong.** “Empirical demolition” is a useful shorthand but must be replaced with exact voyage reports, charts, and before/after map evidence.
7. **Structural analogy only.** The comparison with Shaver/Dulce may be methodologically suggestive, but it is not a historical transmission claim and must not be modeled as one.
8. **Generic hosts are not records.** Naming Princeton, a national archive, or a government PDF host without a stable item URL and catalogue identifier does not satisfy provenance.

## Classification

```yaml
acquisition_type: LEAD_LIST
record_class: UNVERIFIED_LEAD
family_bucket_ids:
  - TERRA-MAP-001
  - TERRA-MAP-002
  - TERRA-MAP-003
  - TERRA-MAP-004
source_status: PRESERVED
canonical_status: NOT_CANONICAL
map_records_created: 0
transmission_edges_created: 0
research_question_status_change: NONE
confidence: LOW_FOR_FACTUAL_INGESTION
```

## Artifact promotion gate

A family bucket must split into item-level records (`TERRA-MAP-00X-A`, `-B`, `-C`, etc.). Each item must identify one exact artifact and include:

- title exactly as printed or catalogued;
- cartographer/engraver/publisher;
- date, edition, state, plate, or sheet number where applicable;
- publication place and language;
- institution plus catalogue ID, call number, or shelfmark;
- stable item-level scan, IIIF manifest, or archival URL;
- legend text or southern labels transcribed from the artifact;
- observed, inferred, copied, and speculative geography separated;
- provenance and uncertainty notes.

No `MAP_EDGE` may be created from generalized resemblance. A transmission edge requires an explicit bibliographic trail, catalogue note, direct citation, known-copy relationship, shared plate/engraver evidence, or a specific scholarly historical analysis.

## Required next pass

For each candidate family, return one or more exact artifacts using the `MAP_RECORD` schema in `SESSION_025_TERRA_AUSTRALIS_ACQUISITION_BRIEF.md`.

### Priority item-level targets

1. An exact 1570 Ortelius world-map artifact from *Theatrum Orbis Terrarum*, including plate/state details and institutional catalogue metadata.
2. One exact Bertius miniature-map artifact dated and catalogued at item level; do not assume “1596” or “1616” until edition metadata is confirmed.
3. An exact pre-Tasman Dutch chart relevant to the 1627 Nuyts coastline and a separately catalogued 1642–1644 Tasman-era chart for comparison.
4. A documented Mercator 1569 → Ortelius 1570 relationship, or a negative finding if no explicit copying trail can be authenticated.
5. One chart or geographical text before Cook’s second voyage and one after it, with exact evidence of changed southern-continent geometry or labels.
6. Digitized primary logs, charts, or official publications from Cook’s voyages, keeping the 1768–1771 first voyage distinct from the 1772–1775 southern-ocean second voyage.
7. One earliest authenticated 1820-era Antarctic observation or chart record.
8. One earliest dated modern publication making an ice-free-Antarctica claim.

The next agent must return artifacts with bibliographic spines and legible legends—not another overview.