# RQ-031 — How did Terra Australis become mapped Antarctica?

```yaml
RQ:
  id: RQ-031
  title: "How did the theoretical southern continent evolve into mapped and observed Antarctica?"
  status: SEARCHING
  priority: HIGH

  why_it_matters: >
    Terra Australis is a controlled test case for the wider project. A theoretical
    landmass appeared in texts and maps, was copied and reshaped across generations,
    contracted as voyages added evidence, and was eventually separated from observed
    Australia and Antarctica. Tracing that process can show how speculation becomes
    a persistent visual object and how later evidence corrects it.

  date_scope:
    start: "classical geography"
    end: 1825

  core_questions:
    - What is the earliest traceable textual basis for a balancing southern continent?
    - Which surviving maps first depict or label a southern landmass?
    - Which mapmakers copied, translated, enlarged, fragmented, or renamed it?
    - How were Tierra del Fuego, New Holland/Australia, imagined southern lands, and Antarctica separated over time?
    - Which voyages and reports changed the plausible geometry of the southern continent?
    - What are the earliest authenticated observations and published maps of Antarctic land or ice?
    - When did modern writers begin claiming that older maps showed an ice-free or advanced-surveyed Antarctica?

  evidence_needed:
    - high-resolution primary map scans
    - library or archive catalogue identifiers
    - exact title, mapmaker, date, edition, state, plate or sheet, language, and publishing city
    - institutional call number or shelfmark
    - stable item-level scan or IIIF URL
    - labels and annotations on the southern landmass
    - documented predecessor and descendant maps
    - voyage reports or geographical texts available to the mapmaker
    - exact coastline or geometry changes between editions
    - first authenticated observation reports and resulting maps
    - first dated modern publications making ancient-map or ice-free-Antarctica claims
    - failed searches and inaccessible collections

  do_not_treat_as_proof:
    - visual resemblance to the modern Antarctic coastline by itself
    - a modern overlay without projection and georeferencing analysis
    - catalogue dates copied from unsourced websites
    - a map's existence as proof that the depicted land existed
    - later labels projected backward onto earlier maps
    - repeated alternative-history claims without the earliest dated publication
    - modern redrawing or restoration presented as the original artifact
    - a family-level label treated as one historical map
    - a generic collection hostname treated as an item citation
    - similarity between maps treated as a transmission edge without a bibliographic trail
    - agreement between model outputs treated as independent source confirmation
    - a model's self-declared INGESTED, COMPLETE, CANONICAL, or confidence status

  positive_resolution: >
    A source-supported chronology identifies the principal textual and cartographic
    nodes, documents copying or influence where evidence exists, and separates the
    imagined southern continent from observed Australia and Antarctica.

  partial_resolution: >
    Major item-level maps and voyages are dated and described, but some copying
    relationships, editions, annotations, or first-observation claims remain uncertain.

  negative_resolution: >
    Searches find no authenticated support for specific modern claims that an early
    map depicts an accurately surveyed or ice-free Antarctica; those claims remain
    speculative or contradicted while the historical map itself remains Evidence A.

  related_objects:
    - SYS-001
    - MAP-CHAIN-001

  generated_session: SESSION_025
  last_updated: 2026-07-13
```

## Current QC state

```text
Acquisition variants received: 3
Core item-level candidates identified: 5
Extended map/event/reinterpretation leads: preserved
Curator-promoted map records: 0
Canonical transmission edges: 0
Canonical findings: 0
RQ-031 status: SEARCHING
```

The original family buckets remain search organizers, not artifacts. The three new acquisition variants produced item-level-looking candidates, but they also conflict on exact identifiers, dates, titles, edge directions, and historical interpretation.

> **Evidence prohibition:** No statement from a cloud output, family bucket, candidate registry, or model-generated acquisition may be cited as evidence in a synthesis, chronology, graph, lineage, or final report until the corresponding item-level `MAP_RECORD` passes curator review.

Read:

- [Variant manifest](../research_inbox/SESSION_025_TERRA_VARIANT_MANIFEST.md)
- [Cross-variant QC](../reports/SESSION_025_TERRA_CROSS_VARIANT_QC.md)
- [Candidate registry](../graph/chronologies/MAP-CHAIN-001-CANDIDATE-REGISTRY.md)
- [Acquisition brief](../research_inbox/SESSION_025_TERRA_AUSTRALIS_ACQUISITION_BRIEF.md)

## Current cross-variant findings

The variants agree on five high-priority item candidates:

1. a printed Ptolemaic world map from Ulm, 1482;
2. Ortelius's *Typus Orbis Terrarum*, 1570;
3. a Bertius South Polar / Terra Australis map, 1616;
4. the Bonaparte–Tasman map or directly related voyage cartography;
5. Cook's Southern Hemisphere chart, 1777.

This agreement changes the search queue, not the evidence class.

### Blocking contradictions

- Variant A reverses the Mercator/Ortelius and Ortelius/Bertius chronological directions.
- The Tasman map is assigned conflicting call numbers and competing object dates.
- Bertius title forms differ across outputs.
- The earliest use and originator of the Latin phrase `Terra Australis recenter inventa, sed nondum plene cognita` remains disputed.
- One claimed Ortelius plate-state sequence ends before the 1616 discovery used to explain it.
- Cook's contribution is alternately overstated as disproving all southern land and more narrowly described as constraining a large temperate continent.
- The 1820 Bellingshausen, Bransfield/Smith, and Palmer priority claims remain unresolved.
- Ptolemy's enclosed-Indian-Ocean model must not be silently converted into later Terra Australis terminology.

## Candidate map families and records — verify, do not assume

- Ptolemaic textual and printed-map traditions;
- Oronce Fine and Mercator item-level maps;
- Ortelius 1570 and its exact plate/state history;
- Bertius South Polar maps and alleged plate reuse;
- Nuyts, Tasman, Blaeu, and Thévenot voyage-data transmission;
- cartography before and after Cook's southern voyages;
- competing 1820 observation records;
- Mallery, Hapgood, Piri Reis, Fine, and Buache in the modern ice-free-Antarctica reinterpretation layer.

Every candidate requires an exact edition, stable scan, catalogue record, evidence classification, and curator sign-off before becoming canonical.

## Priority work packages

1. **Ptolemy 1482:** choose one exact institutional copy and inspect its printed labels and enclosed-ocean geometry.
2. **Ortelius 1570:** identify the exact world-map plate/state, institutional scan, catalogue ID, southern label, and source-list evidence.
3. **Bertius 1616:** confirm exact printed title, catalogue title, edition/state, item ID, and any same-plate reuse.
4. **Tasman artifact:** resolve the State Library identifier, object date versus source-data date, authorship, and depicted blanks/joins.
5. **Cook 1777:** confirm the exact chart item, transcribe annotations, and state precisely what the voyage ruled out and what it still considered possible.
6. **Mercator/Fine edge:** inspect primary scans before asserting feature-level copying or phrase transmission.
7. **1820 observation records:** preserve competing claims and the exact documentary basis for each.
8. **Modern reinterpretation origin:** locate the earliest exact Mallery/Hapgood publication, page, quotation, and invoked reproduction.

After at least three core item records pass the promotion gate, the curator may reconsider `RQ-031` for `PARTIAL` status.
