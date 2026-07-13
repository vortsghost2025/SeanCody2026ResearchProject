# RQ-031 — How did Terra Australis become mapped Antarctica?

```yaml
RQ:
  id: RQ-031
  title: "How did the theoretical southern continent evolve into mapped and observed Antarctica?"
  status: SEARCHING
  priority: HIGH
  last_updated: 2026-07-13

  why_it_matters: >
    Terra Australis is a controlled test case for tracing how a theoretical object
    enters maps, is copied and reshaped, contracts as voyages add evidence, separates
    from Australia, and is eventually replaced by observed Antarctic geography.

  date_scope:
    start: "classical geography"
    end: 1825

  core_questions:
    - What is the earliest textual basis for a balancing southern continent?
    - Which surviving maps first depict or label a southern landmass?
    - Which mapmakers copied, translated, enlarged, fragmented, or renamed it?
    - How were Tierra del Fuego, New Holland/Australia, imagined southern lands, and Antarctica separated?
    - Which voyages changed the plausible geometry?
    - What are the earliest authenticated observations and published maps of Antarctic land or ice?
    - When did modern writers begin claiming that older maps showed an ice-free or advanced-surveyed Antarctica?

  evidence_needed:
    - primary scans and institutional catalogue identifiers
    - exact titles, creators, dates, editions, imprints, states, plates or sheets
    - call numbers, shelfmarks, stable item URLs, and IIIF links
    - transcribed map labels and annotations
    - documented predecessor/descendant relationships
    - voyage reports and chart evidence
    - first dated modern reinterpretation claims
    - failed searches and inaccessible-source records

  do_not_treat_as_proof:
    - visual resemblance alone
    - modern overlays without projection analysis
    - generic collection hosts
    - a family bucket treated as one historical map
    - agreement between model outputs
    - a model's self-declared INGESTED, COMPLETE, CANONICAL, or confidence score
    - source-list acknowledgment treated as proof of a specific copied feature
    - Ptolemaic geography silently renamed with later Terra Australis terminology

  partial_resolution_gate: >
    At least three core item records must pass curator review, with a source-supported
    chronology and clearly scoped relationships. One verified map is meaningful but
    does not make the overall question PARTIAL.

  positive_resolution: >
    A source-supported chronology identifies the principal textual, cartographic,
    voyage, and observation nodes, while separating imagined geography, observed
    geography, and later reinterpretation.
```

## Current QC state

```text
Acquisition variants received: 5
Core item records promoted: 1
Remaining core candidates: 4
Verified narrow map edges: 1
Canonical full lineage: 0
RQ-031 status: SEARCHING
```

## First promoted item

### TERRA-MAP-002-A — Ortelius, *Typvs Orbis Terrarvm* (1570)

The selected artifact is the Library of Congress 1570 Latin atlas copy:

```yaml
institution: Library of Congress, Geography and Map Division
call_number: "G1006 .T5 1570"
lccn: "2003683482"
digital_id: "g3200m.gct00126"
map_sheet: 12
item_url: "https://www.loc.gov/item/2003683482/"
scan_url: "https://www.loc.gov/resource/g3200m.gct00126/?sp=12"
imprint: "third imprint of the original 1570 Latin edition"
```

Accepted conclusions:

- the exact institutional artifact and scan are established;
- the map depicts a named speculative southern continent;
- Mercator's 1569 world map has a documented general influence on Ortelius's world-map synthesis.

Still unresolved:

- exact first-plate state diagnostics for this sheet;
- feature-by-feature Terra Australis copying;
- Finé's exact role in label or coastline transmission;
- final diplomatic transcription details.

Read:

- [Promoted Ortelius item](../graph/chronologies/TERRA-MAP-002-A-ORTELIUS-1570.md)
- [Mercator → Ortelius edge](../graph/transmissions/MAP-EDGE-001-MERCATOR-ORTELIUS-WORLD-MAP.md)
- [Session 026 variant manifest](../research_inbox/SESSION_026_ORTELIUS_VARIANT_MANIFEST.md)
- [Session 026 curator QC](../reports/SESSION_026_ORTELIUS_QC.md)
- [Item registry](../graph/chronologies/MAP-CHAIN-001-CANDIDATE-REGISTRY.md)

## Remaining core queue

1. **TERRA-MAP-001-A — Ptolemy/Ulm 1482**  
   Select one institutional copy, identify exact shelfmark and scan, transcribe the southern land bridge, and keep the enclosed Indian Ocean distinct from later Terra Australis nomenclature.

2. **TERRA-MAP-003-A — Bertius 1616**  
   Confirm printed and catalogue titles, edition/state, item identifier, scan, and alleged plate reuse.

3. **TERRA-MAP-004-A — Bonaparte–Tasman map**  
   Resolve call number, object date versus voyage-data date, authorship, and depicted blanks/joins.

4. **TERRA-MAP-005-A — Cook 1777**  
   Confirm the exact chart, annotations, publication context, and the narrow conclusion supported by the second voyage.

## Extended queue

- inspect one surviving Mercator 1569 map directly;
- resolve the Schöner/Finé terminology sequence using exact artifacts;
- preserve Bellingshausen, Bransfield/Smith, and Palmer as competing 1820 observation claims;
- locate the earliest Mallery/Hapgood ice-free-Antarctica publication and page.
