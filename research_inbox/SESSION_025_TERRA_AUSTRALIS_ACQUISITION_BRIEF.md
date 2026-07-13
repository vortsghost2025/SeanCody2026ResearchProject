# SESSION_025 — Terra Australis / Antarctica Map-Lineage Acquisition Brief

**Primary question:** [RQ-031](../research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md)  
**Mode:** Public-source acquisition only  
**Status:** OPEN — curator review required

## Objective

Build a source-traceable chronology showing how a theoretical southern continent became a repeated cartographic object, changed as voyages added evidence, separated from Australia, and was eventually replaced by observed Antarctic geography.

Do not begin with the assumption that any old map accurately depicts Antarctica. Record what each artifact actually shows, what its catalogue says, what sources the mapmaker likely used, and when later writers reinterpreted it.

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
  title:
  creator:
  creation_date:
  publication_date:
  edition_state:
  publishing_city:
  language:
  institution:
  catalogue_id:
  stable_scan_url:
  projection:
  scale:
  southern_labels: []
  observed_features: []
  inferred_features: []
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
  relationship: KNOWN_COPY | DIRECT_CITATION | TRANSLATION | SHARED_PUBLISHER | DOCUMENTED_INFLUENCE | POSSIBLE_INFLUENCE | UNKNOWN
  first_possible_date:
  first_verified_date:
  evidence:
  confidence:
  notes:
```

## Source priorities

Prefer institutional primary sources and scholarly catalogues:

- national libraries and archives;
- university special collections;
- museum map collections;
- voyage logs and official expedition publications;
- digitized rare-map repositories with catalogue metadata;
- peer-reviewed history-of-cartography work for interpretation.

Commercial map sellers, blogs, social posts, and alternative-history sites may identify candidates but cannot establish provenance by themselves.

## Deliverables

1. Raw acquisition report.
2. Twelve to twenty map or text records.
3. A chronology table.
4. A map-lineage edge table.
5. A separate modern-reinterpretation table.
6. Contradictions and priority disputes.
7. Failed-search and inaccessible-source log.
8. Acquisition summary.
9. New research questions generated by unresolved evidence.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md`, `docs/METHODOLOGY.md`, and the map rules in `ChatGPTfirstentryjuly12.md`. Execute `research_inbox/SESSION_025_TERRA_AUSTRALIS_ACQUISITION_BRIEF.md`. Use public primary sources and institutional scans. Build exact map records and source-supported transmission edges. Keep observed geography, inferred geography, speculative geography, and modern reinterpretation separate. Do not assume visual resemblance proves accurate Antarctic mapping. Record failed searches and disagreements. Return raw acquisition only; do not commit, ingest, freeze, or mark the question resolved.
