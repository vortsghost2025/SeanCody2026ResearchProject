# Issue #3 Remediation Report

## Ingest and validate Sessions 013–020

**Status:** Pre-ingestion QC complete; canonical ingestion remains blocked by source population and record validation.

This committed report records the binding remediation decisions from the full July 12, 2026 QC pass. The detailed source-by-source working report remains the controlling research document for implementation.

## Resolved structural decisions

### Record ranges

- Session 013 delivered `FLOOD-009` through `FLOOD-014`.
- Session 014 delivered `FLOOD-015` through `FLOOD-020`.
- `FLOOD-021` through `FLOOD-030` are reserved and documented in `data/claims/FLOOD/FLOOD-ID-REGISTRY.md`.
- Future session headings must list only IDs actually delivered.

### Canonical schema

The base schema was upgraded to v1.1 with these record types added:

- `comparative`
- `claim`
- `publication`
- `institution`

`amplification_chain` maps to `convergence`; `person_and_publication` maps to `person`; `claims_audit` and negative-evidence master records map to `hypothesis` unless a later version explicitly adds new types.

Cluster-specific fields now belong in `cluster_data`, identified by `cluster_schema`. They must be validated separately. Initial validators:

- `schemas/clusters/flood.schema.json`
- `schemas/clusters/traditions.schema.json`

### Completion language

Until traceable source objects are populated:

- `COMPLETE` becomes `DRAFTED — sources pending`.
- `CLOSED` becomes `AGENT TASK ADDRESSED — verification pending`.
- `definitive refutation` becomes `well-supported scholarly refutation`.
- `conclusively refuted` becomes `contradicted by documented evidence`.

Strong completion language may return only when the cited source exists in `sources[]` with adequate access status and edition/page/context metadata.

## Source policy

### Tier 1 — Primary

Original manuscripts, artifacts, official excavation reports, institutional archives, government records, maps, logs, and physical objects.

### Tier 2 — Academic secondary

Peer-reviewed journal articles, academic monographs, accredited theses, and museum catalogues.

### Tier 3 — Reliable tertiary

Established reference works, national museum sites, scholarly institutes, and recognized encyclopedias.

### Tier 4 — Reinterpretation

Von Däniken, Hancock, Sitchin, Ancient Aliens, apologetics, fringe publications, and similar material. These sources document reinterpretation and diffusion; they do not prove the underlying claim.

### Tier 5 — Lead-only sources

Wikipedia, Grokipedia, anonymous summaries, Answers in Genesis, Got Questions, and similar pages may locate better sources but cannot independently support evidence-class upgrades.

A claim rated Class A requires at least one traceable Tier 1 or Tier 2 source. `verified` language requires `verified_excerpt` or `verified_full_text`, not merely a bibliographic citation.

## Quarantine findings

### NAZ-002

The attribution of Joe Nickell's recreated-condor result as “remarkable in its exactness” conflicts across web sources: some attribute it to *National Geographic*, others to *Scientific American*. The quote remains unverified until the original publication is located. NAZ-002 cannot leave quarantine with this attribution stated as fact.

### FLOOD-018

The current Lakota flood wording is exposed because it was derived through Young Earth Creationist apologetics. The rainbow covenant and bird-messenger elements cannot be treated as pre-contact tradition until located in an actual ethnographic source. James R. Walker's 1917 Oglala work is a candidate, not yet confirmation.

### Additional source gaps

- Exact Von Däniken Dogū page.
- Exact George Grey Wandjina pages.
- Earliest Wandjina-as-alien publication.
- Earliest Tell Asmar alien reinterpretation.
- Hatnub ramp peer-reviewed publication.
- Roggersdorf / Wilhelm Utermann bibliographic confirmation.
- Full citation and peer-review status for the 2023 Hancock paper.
- Sebottendorff 1933 primary text.

## Oral and living traditions

Oral-tradition records require all four clocks:

1. Claimed cosmological or ancestral time.
2. Estimated material-culture age.
3. Earliest written or audio recording.
4. Date of the exact wording quoted.

The `traditions` cluster schema also supports structured colonial recording context and living custodianship. Missionary or colonial recording must be explicit, with contamination risk rated separately for each narrative element.

Wandjina and Rainbow Serpent records must name specific custodian communities and distinguish community meanings from later Western scholarly or fringe interpretations.

## HYP-013 status

HYP-013 remains **PROPOSED**, evidence class C.

**Hypothesis:** Skilled journalistic presentation, selective engagement with legitimate contested science, and conspiracy-of-silence framing may create a more durable pseudoarchaeological system than direct fabrication.

**Null hypothesis:** Platform scale and audience reach—not methodological sophistication—explain the difference between Von Däniken's and Hancock's cultural footprints.

Testing must compare belief correction, persistence, academic response, and ability to absorb contradicting evidence while controlling for platform.

## Required execution order

1. Schema gate — completed with v1.1 and initial cluster schemas.
2. Flood ID registry — completed.
3. Populate formal source objects in priority order.
4. Quarantine nonconforming or unresolved records.
5. Populate oral-tradition clocks and living-tradition fields.
6. Replace unsupported completion language.
7. Commit HYP-013 after canonical validation.
8. Recompute record totals from actual validated JSON files.

## Acceptance status

| Criterion | Status |
|---|---|
| Stable IDs and reserved ranges | Ready |
| Base and initial cluster schema gate | Open |
| Every record validates | Not yet met |
| Major claims have traceable sources | Not yet met |
| Quotations include edition/page/context | Not yet met |
| Machine-readable ingestion report | Pending ingestion tooling |
| Counts derived from committed files | Blocked until records are ingested |

No Sessions 013–020 record should be counted as canonical merely because it appears in a session Markdown file. Canonical count begins only when a JSON record exists, validates, and passes source review.
