# MAP-CHAIN-001 — Terra Australis Item Registry

> **Related question:** `RQ-031`  
> **Curator-promoted item records:** 1  
> **Verified narrow map edges:** 1  
> **RQ status:** SEARCHING

This registry separates curator-reviewed artifacts from cross-variant candidates. Model agreement changes priority, not evidence class.

## Promotion rule

A candidate becomes an `ITEM_LEVEL_MAP_RECORD` only after curator review confirms one exact artifact, institutional metadata, a stable scan, relevant labels, chronology, uncertainties, and the permitted scope of any transmission edge.

---

## Promoted item records

### TERRA-MAP-002-A — Ortelius, *Typvs Orbis Terrarvm* (1570)

```yaml
record_class: ITEM_LEVEL_MAP_RECORD
curator_status: PROMOTED_WITH_LIMITS
verification_status:
  artifact_identity: CURATOR_REVIEWED
  primary_scan: CONFIRMED
  imprint: THIRD_IMPRINT_OF_1570_LATIN_EDITION
  plate_state: UNRESOLVED
institution: "Library of Congress, Geography and Map Division"
call_number: "G1006 .T5 1570"
lccn: "2003683482"
digital_id: "g3200m.gct00126"
map_sheet: 12
stable_item_url: "https://www.loc.gov/item/2003683482/"
stable_scan_url: "https://www.loc.gov/resource/g3200m.gct00126/?sp=12"
southern_label: "TERRA AVSTRALIS NONDVM COGNITA"
related_record: "graph/chronologies/TERRA-MAP-002-A-ORTELIUS-1570.md"
related_edge: "graph/transmissions/MAP-EDGE-001-MERCATOR-ORTELIUS-WORLD-MAP.md"
```

### Accepted boundary

- The 1570 LOC artifact identity is verified.
- The online LOC copy is the third imprint of the original 1570 Latin edition, not automatically the first state.
- Mercator's 1569 world map has a verified general influence relationship to Ortelius's world-map synthesis.
- Specific Terra Australis geometry, Finé nomenclature transmission, and detailed plate-state claims remain unresolved.

---

## Core item candidates

### TERRA-MAP-001-A — Ptolemaic world map, Ulm, 1482

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
candidate_creator: "Nicolaus Germanus after Claudius Ptolemy"
candidate_date: 1482
candidate_place: Ulm
candidate_printer: "Leinhart/Leinhard Holle"
claimed_holdings:
  - British Library
  - Osher Map Library
  - Princeton University Library
blocking_conflicts:
  - one exact holding and shelfmark not selected
  - printed labels not transcribed from one confirmed scan
  - Ptolemaic enclosed-Indian-Ocean geography must not be silently renamed Terra Australis
promotion_task: "Select one institutional copy and inspect the primary scan."
```

### TERRA-MAP-003-A — Bertius South Polar map, 1616

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
candidate_creator: Petrus Bertius
candidate_date: 1616
candidate_titles:
  catalogue_or_section_title: "Descriptio Terrae Subaustralis"
  printed_map_title: "Magallanica sive Terra Australis Incognita"
claimed_holding: "Princeton University Library"
blocking_conflicts:
  - title spelling differs across outputs
  - exact edition/state and identifier are not curator-confirmed
  - first-South-Pole-map and 1676 same-plate-reuse claims require specialist verification
promotion_task: "Confirm one exact item, title, edition/state, scan, and any plate reuse."
```

### TERRA-MAP-004-A — Bonaparte–Tasman map

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
candidate_creator: "Tasman voyage cartography; draftsman uncertain"
source_data_dates: [1642-1643, 1644]
candidate_object_dates: ["after 1644", "circa 1695"]
claimed_holding: "State Library of New South Wales, Mitchell Library"
conflicting_locators: ["ML 800", "ML 863"]
blocking_conflicts:
  - call number conflict
  - object date differs from voyage-data and heraldic dates
  - authorship and depicted joins/blanks remain uncertain
promotion_task: "Open the exact State Library item and separate object, source, voyage, and provenance dates."
```

### TERRA-MAP-005-A — Cook, Southern Hemisphere chart, 1777

```yaml
record_class: ITEM_CANDIDATE
verification_status: CROSS_VARIANT_UNVERIFIED
candidate_title: "A Chart of the Southern Hemisphere; shewing the Tracks of some of the most distinguished Navigators"
candidate_creator: "James Cook / voyage publication cartography"
candidate_date: 1777
claimed_holding: "Royal Museums Greenwich / National Maritime Museum"
claimed_locator: "G201:1/1 / object 540700"
blocking_conflicts:
  - exact item and accession not curator-confirmed
  - outputs alternate between disproving all southern land and only constraining a large temperate continent
  - claimed direct refutation of Dalrymple needs documentary support
promotion_task: "Confirm the item, annotations, publication context, and narrow empirical conclusion."
```

---

## Extended map leads

### TERRA-MAP-006-A — Mercator world map, 1569

```yaml
record_class: UNVERIFIED_LEAD
status_note: "General influence on Ortelius is verified; the Mercator artifact itself is not yet an item-level record."
next_task: "Select one surviving institutional copy and transcribe its southern labels."
```

### TERRA-MAP-007-A — Oronce Finé, 1531/1534

```yaml
record_class: UNVERIFIED_LEAD
blocking_issues:
  - exact relevant artifact/date varies
  - earliest occurrence and originator of the disputed Latin phrase remain unresolved
next_task: "Locate exact institutional Finé and earlier Schöner artifacts before asserting terminology transmission."
```

---

## Non-map clusters

### ANT-OBS-1820 — Competing observation records

```yaml
record_class: EVENT_CLUSTER_LEAD
candidates: [Bellingshausen, Bransfield_and_Smith, Palmer]
rule: "Do not resolve priority without exact logs/charts, calendar conversion, coordinates, and observed-feature classification."
```

### ANT-REINT-001 — Ice-free Antarctica reinterpretation chain

```yaml
record_class: REINTERPRETATION_LEAD
candidate_people: [Arlington_H_Mallery, Charles_H_Hapgood]
candidate_maps: [Piri_Reis_1513, Oronce_Fine, Philippe_Buache_1739]
rule: "Locate the earliest exact publication, page, quotation, reproduction, and criticism."
```

## Current counts

```yaml
acquisition_variants: 5
core_items_total: 5
curator_promoted_item_records: 1
remaining_core_candidates: 4
verified_narrow_edges: 1
extended_map_leads: 2
event_clusters: 1
reinterpretation_clusters: 1
```
