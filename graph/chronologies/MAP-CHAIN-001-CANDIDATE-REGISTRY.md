# MAP-CHAIN-001 — Terra Australis Candidate Registry

> **Registry class:** CROSS-VARIANT CANDIDATES  
> **Canonical status:** NONE OF THESE RECORDS ARE CANONICAL  
> **Related question:** `RQ-031`

This registry exists so future agents can work from a numbered item queue without mistaking model agreement for verification.

## Promotion rule

A candidate becomes an `ITEM_LEVEL_MAP_RECORD` only after curator review confirms:

- one exact physical or digitized artifact;
- exact printed and catalogue titles;
- creator, engraver, publisher, and publication place where available;
- date, edition, state, plate, or sheet;
- institution and exact catalogue ID/call number/shelfmark;
- stable item-level scan or IIIF URL;
- transcription of relevant labels or legends;
- observed, inferred, copied, blank, and speculative geography kept separate;
- uncertainties and provenance recorded.

## Core candidates

### TERRA-MAP-001-A — Ptolemaic world map, Ulm, 1482

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
parent_family_bucket: TERRA-MAP-001
candidate_title: "World map from Ptolemy's Cosmographia / Geographia"
candidate_creator: "Nicolaus Germanus after Claudius Ptolemy"
candidate_date: 1482
candidate_place: Ulm
candidate_printer: Leinhart/Leinhard Holle
source_variants:
  - A
  - B
  - C
claimed_holdings:
  - British Library
  - Osher Map Library
  - Princeton University Library
blocking_conflicts:
  - exact holding and shelfmark not consistently supplied
  - printed labels not transcribed from one confirmed scan
  - Ptolemaic enclosed Indian Ocean must not be equated automatically with the later named Terra Australis
promotion_task: "Select one institutional copy, record its item metadata, and inspect the primary scan."
```

### TERRA-MAP-002-A — Ortelius, Typus Orbis Terrarum, 1570

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
parent_family_bucket: TERRA-MAP-002
candidate_title: "Typus Orbis Terrarum"
candidate_creator: Abraham Ortelius
candidate_engraver: Frans Hogenberg
candidate_date: 1570
candidate_atlas: "Theatrum Orbis Terrarum"
source_variants:
  - A
  - B
  - C
claimed_label: "TERRA AVSTRALIS NONDVM COGNITA"
claimed_holding:
  institution: Library of Congress
  locator_claim: "G3200 1570 .O7 / item 2002622206"
blocking_conflicts:
  - exact 1570 copy/state not curator-confirmed
  - Variant B aggregates multiple editions, states, and holdings
  - Catalogus Auctorum proves bibliographic acknowledgment but not every claimed feature-copying edge
  - alleged plate-state chronology is internally inconsistent with a 1616 discovery
promotion_task: "Open one exact 1570 item, identify state/plate, transcribe the label, and separate source-list evidence from feature-copying evidence."
```

### TERRA-MAP-003-A — Bertius South Polar map, 1616

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
parent_family_bucket: TERRA-MAP-003
candidate_creator: Petrus Bertius
candidate_date: 1616
candidate_atlas: "Tabularum Geographicarum Contractarum"
candidate_titles:
  catalogue_or_section_title: "Descriptio Terrae Subaustralis"
  printed_map_title: "Magallanica sive Terra Australis Incognita"
source_variants:
  - A
  - B
  - C
claimed_holding:
  institution: Princeton University Library
  locator_claims:
    - "HMC01.442"
    - "princeton-v405sc82k"
blocking_conflicts:
  - Variant A misspells the title as "Substralis"
  - exact edition/state and item identifier not curator-confirmed
  - first-map-of-the-South-Pole claim requires specialist source verification
  - alleged same-plate reuse in 1676 requires exact item comparison
promotion_task: "Confirm printed title, catalogue title, item ID, edition/state, scan, and any plate-reuse relationship."
```

### TERRA-MAP-004-A — Bonaparte–Tasman map

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
parent_family_bucket: TERRA-MAP-004
candidate_title: "Bonaparte–Tasman map / Tasman map"
candidate_creator: "Attributed to Tasman voyage cartography; draftsman uncertain"
source_data_dates:
  - 1642-1643
  - 1644
candidate_object_dates:
  - after 1644
  - circa 1695
source_variants:
  - A
  - B
  - C
claimed_holding:
  institution: State Library of New South Wales, Mitchell Library
  conflicting_locators:
    - "ML 800"
    - "ML 863"
blocking_conflicts:
  - call number conflict
  - object creation date differs from voyage-data date and heraldic date
  - authorship and drafting supervision uncertain
  - exact southern blanks, joins, and coastlines must be read from the artifact
promotion_task: "Open the exact State Library record and separate object date, source-map date, voyage date, provenance, and depicted geography."
```

### TERRA-MAP-005-A — Cook, Chart of the Southern Hemisphere, 1777

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
parent_family_bucket: TERRA-MAP-005
candidate_title: "A Chart of the Southern Hemisphere; shewing the Tracks of some of the most distinguished Navigators"
candidate_creator: James Cook / voyage publication cartography
candidate_date: 1777
candidate_publication: "A Voyage towards the South Pole and Round the World"
source_variants:
  - A
  - B
  - C
claimed_holding:
  institution: Royal Museums Greenwich / National Maritime Museum
  locator_claim: "G201:1/1 / object 540700"
blocking_conflicts:
  - exact item and accession not curator-confirmed
  - output language alternates between disproving all southern land and disproving a large temperate continent
  - claim that the chart was specifically designed to refute Dalrymple requires direct documentary support
  - chart annotations and Cook's own journal wording need item/page locators
promotion_task: "Confirm the museum item, scan, annotations, publication context, and the narrow empirical conclusion supported by Cook's records."
```

## Extended candidates

### TERRA-MAP-006-A — Mercator world map, 1569

```yaml
record_class: UNVERIFIED_LEAD
candidate_title: "Nova et Aucta Orbis Terrae Descriptio ad Usum Navigantium Emendate Accommodata"
blocking_issue: "No surviving institutional scan was inspected consistently across the variants."
next_task: "Select one surviving copy, transcribe its southern labels, and compare it directly with the exact Ortelius 1570 item."
```

### TERRA-MAP-007-A — Oronce Fine southern-continent map, 1531/1534

```yaml
record_class: UNVERIFIED_LEAD
candidate_titles:
  - "Nova et integra universi orbis descriptio"
  - "Recens et integra orbis descriptio"
blocking_issues:
  - exact relevant edition/date varies between outputs
  - earliest occurrence and originator of "Terra Australis recenter inventa, sed nondum plene cognita" is disputed
next_task: "Locate institutional scans for the exact Fine artifacts and compare the phrase against earlier Schöner material."
```

## Non-map clusters retained separately

### ANT-OBS-1820 — Competing first-observation records

```yaml
record_class: EVENT_CLUSTER_LEAD
candidates:
  - Bellingshausen
  - Bransfield and Smith
  - Palmer
rule: "Do not resolve priority without exact logs/charts, calendar conversion, coordinates, and a description of whether land, mountain, ice shelf, or sea ice was observed."
```

### ANT-REINT-001 — Ice-free Antarctica reinterpretation chain

```yaml
record_class: REINTERPRETATION_LEAD
candidate_people:
  - Arlington H. Mallery
  - Charles H. Hapgood
candidate_maps_invoked:
  - Piri Reis 1513
  - Oronce Fine 1531/1534
  - Philippe Buache 1739
rule: "Locate the earliest exact publication, edition, page, quotation, reproduction used, and scholarly/cartographic criticism. Keep the historical map artifact separate from the later claim."
```

## Current counts

```yaml
source_variants: 3
core_item_candidates: 5
extended_map_leads: 2
event_clusters: 1
reinterpretation_clusters: 1
curator_promoted_records: 0
canonical_edges: 0
```
