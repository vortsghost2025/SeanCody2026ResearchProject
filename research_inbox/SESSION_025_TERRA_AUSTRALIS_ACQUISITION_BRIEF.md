# SESSION_025 — Terra Australis / Antarctica Map-Lineage Acquisition Brief

**Primary question:** [RQ-031](../research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md)  
**Mode:** Public-source acquisition only  
**Status:** OPEN — curator review required

> ## Evidence gate
>
> All overview statements, candidate names, generic host links, and `TERRA-MAP-001` through `TERRA-MAP-004` begin as `UNVERIFIED_LEAD` records. The four `TERRA-MAP` identifiers are `FAMILY_BUCKETS`, not artifacts.
>
> No claim from a lead list may be cited as evidence in synthesis, chronology, graph, lineage, or final-report tasks until it is tied to an item-level `MAP_RECORD` containing a dated primary-map scan, institutional catalogue identifier, and stable item URL.

## Objective

Build a source-traceable chronology showing how a theoretical southern continent became a repeated cartographic object, changed as voyages added evidence, separated from Australia, and was eventually replaced by observed Antarctic geography.

Do not begin with the assumption that any old map accurately depicts Antarctica. Record what each artifact actually shows, what its catalogue says, what sources the mapmaker likely used, and when later writers reinterpreted it.

## Lead, family-bucket, and artifact classes

```text
UNVERIFIED_LEAD
  └── candidate statement, mapmaker name, generic collection host, or overview claim

FAMILY_BUCKET
  └── organizational search group such as TERRA-MAP-002; never an Evidence-A artifact

ITEM_LEVEL_MAP_RECORD
  └── one exact map, edition, state, plate, sheet, or chart with primary scan and catalogue metadata
```

Family buckets must split into item IDs such as `TERRA-MAP-002-A`, `TERRA-MAP-002-B`, and `TERRA-MAP-002-C`. Promotion requires curator review. A family bucket may never be promoted wholesale.

## Research waves

### Wave 1 — Textual ancestry and early printed geography

Find the earliest traceable textual arguments for a balancing southern landmass and the earliest surviving printed maps that visualize it.

Capture:

- exact work and edition;
- author/mapmaker;
- date and publishing city;
- original terminology;
- whether the southern land is textual, schematic, or coastlined;
- institutional scan and catalogue ID.

### Wave 2 — Sixteenth-century expansion

Acquire primary scans for major `Terra Australis` map families and document:

- southern labels;
- coastline geometry;
- connection or separation from Tierra del Fuego;
- connection or separation from New Guinea/New Holland;
- annotations admitting uncertainty;
- known copying, engraving, translation, or publisher relationships.

Candidate names are listed in RQ-031. Verify exact maps and editions rather than trusting the candidate list.

### Wave 3 — Seventeenth-century fragmentation and Australia

Track how Dutch and other voyage information changed the southern landmass and how New Holland/Australia became a distinct mapped object.

Separate:

- observed coast;
- inferred coast;
- blank space;
- hypothetical continent;
- copied legacy geometry.

### Wave 4 — Cook and contraction of the hypothetical continent

Compare maps and geographical texts before and after the major southern voyages of the eighteenth century.

Look for explicit evidence that:

- the plausible area of a southern continent shrank;
- map labels changed;
- coastlines disappeared or fragmented;
- mapmakers cited voyage reports or newly published charts.

Keep Cook’s first voyage (`1768–1771`) distinct from the southern-ocean second voyage (`1772–1775`). A 1770 Australian coastline chart and a second-voyage southern chart answer different research questions and must not be merged.

### Wave 5 — Authenticated Antarctic observation and mapping

Build a cautious chronology around the 1820-era observation claims.

For each candidate event record:

- expedition and vessel;
- observer;
- exact date under the calendar used;
- claimed feature observed;
- logbook, report, chart, or official publication;
- whether land, ice shelf, sea ice, mountain, or coastline was actually described;
- later priority dispute;
- evidence class.

Do not resolve national priority by assertion. Preserve competing claims and the documentary basis for each.

### Wave 6 — Modern myth and reinterpretation layer

Separately trace the first dated modern claims that older maps show:

- an ice-free Antarctica;
- advanced prehistoric surveying;
- lost-civilization source maps;
- impossible longitude knowledge;
- suppressed Antarctic geography.

For each claim, record:

- first located author and publication;
- exact year, edition, and page;
- which historical map was invoked;
- what the original map actually shows;
- whether the modern claim used a redrawing, overlay, or altered reproduction;
- scholarly or cartographic criticism;
- status: `DIRECT_CITATION`, `RETROACTIVE_REINTERPRETATION`, `SPECULATIVE_SIMILARITY`, `NEGATIVE_EVIDENCE`, or `UNKNOWN`.

## Required map record

```yaml
MAP_RECORD:
  map_id:
  parent_family_bucket:
  record_class: ITEM_LEVEL_MAP_RECORD
  verification_status: UNVERIFIED | PRIMARY_SCAN_CONFIRMED | CATALOGUE_CONFIRMED | CURATOR_REVIEWED
  title_as_printed:
  catalogue_title:
  creator:
  engraver:
  publisher:
  creation_date:
  publication_date:
  edition_state:
  plate_or_sheet_number:
  publishing_city:
  language:
  institution:
  catalogue_id:
  call_number_or_shelfmark:
  stable_scan_url:
  iiif_manifest_url:
  projection:
  scale:
  region_shown:
  southern_labels: []
  legend_transcription:
  observed_features: []
  inferred_features: []
  copied_legacy_features: []
  speculative_features: []
  predecessor_maps: []
  descendant_maps: []
  voyage_reports_available: []
  exact_quotation_or_annotation:
  evidence_class:
  uncertainties: []
```

## Required transmission edge

```yaml
MAP_EDGE:
  edge_id:
  from_map_or_text:
  to_map_or_text:
  relationship: KNOWN_COPY | DIRECT_CITATION | TRANSLATION | SHARED_PUBLISHER | SHARED_PLATE_OR_ENGRAVER | DOCUMENTED_INFLUENCE | POSSIBLE_INFLUENCE | UNKNOWN
  first_possible_date:
  first_verified_date:
  evidence:
  evidence_locator:
  confidence:
  notes:
```

No `MAP_EDGE` may be asserted from visual resemblance alone. It requires a bibliographic trail, catalogue note, direct citation, known-copy relationship, shared plate or engraver evidence, or a specific historical analysis with page-level citation.

## Priority item-level work packages

### WP-031-A — Ortelius 1570

- identify the exact world-map plate or state in the 1570 *Theatrum Orbis Terrarum*;
- transcribe the southern label exactly;
- record plate/state details, institution, catalogue ID, and stable scan;
- distinguish the map from later Ortelius editions.

### WP-031-B — Bertius miniature maps

- locate specific Bertius map items and confirm whether the relevant edition is 1596, circa 1616, or another state;
- record exact title, edition, plate/sheet, institution, and call number;
- do not treat a generic “Bertius map” reference as one artifact.

### WP-031-C — Nuyts and Tasman comparison

- acquire one exact chart or map representing the 1627 Nuyts coastline information;
- acquire one exact 1642–1644 Tasman-era item;
- compare only item-level observed coastlines, inferred joins, blanks, and copied speculative geometry.

### WP-031-D — Mercator 1569 → Ortelius 1570

- search for explicit bibliographic or scholarly evidence of adoption, copying, engraving lineage, or shared source use;
- return `UNKNOWN` or `NEGATIVE_EVIDENCE` if no authenticated edge is found;
- do not convert resemblance into `KNOWN_COPY`.

### WP-031-E — Cook primary records

- locate digitized primary logs, charts, or official publications from Cook’s first and second voyages;
- separate 1770 east-coast Australia charting from the second voyage’s southern-ocean search;
- compare one pre-second-voyage and one post-second-voyage map or geographical text.

## Source priorities

Prefer institutional primary sources and scholarly catalogues:

- national libraries and archives;
- university special collections;
- museum map collections;
- voyage logs and official expedition publications;
- digitized rare-map repositories with catalogue metadata;
- peer-reviewed history-of-cartography work for interpretation.

Commercial map sellers, blogs, social posts, Wikipedia, and alternative-history sites may identify candidates but cannot establish provenance by themselves.

## Deliverables

1. Raw acquisition report.
2. Twelve to twenty item-level map or text records.
3. A chronology table.
4. A map-lineage edge table.
5. A separate modern-reinterpretation table.
6. Contradictions and priority disputes.
7. Failed-search and inaccessible-source log.
8. Acquisition summary.
9. New research questions generated by unresolved evidence.
10. A promotion table showing which leads remained `UNVERIFIED_LEAD`, which family buckets received item-level children, and which records passed curator review.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md`, `docs/METHODOLOGY.md`, and the map rules in `ChatGPTfirstentryjuly12.md`. Execute `research_inbox/SESSION_025_TERRA_AUSTRALIS_ACQUISITION_BRIEF.md`. Treat all overview claims as `UNVERIFIED_LEAD` and `TERRA-MAP-001` through `004` as `FAMILY_BUCKETS`. Return item-level map records with exact titles, editions/states, plate or sheet numbers, institutional catalogue IDs, call numbers or shelfmarks, stable scans or IIIF URLs, and transcribed southern labels. Do not assert a transmission edge from resemblance; cite a bibliographic trail or return `UNKNOWN`. Keep observed, inferred, copied, speculative, and modern-reinterpretation layers separate. Record failed searches and disagreements. Return raw acquisition only; do not commit, ingest, freeze, or mark the question resolved.