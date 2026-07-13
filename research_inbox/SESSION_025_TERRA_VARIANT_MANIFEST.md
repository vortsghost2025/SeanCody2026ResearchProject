# SESSION 025 — Terra Australis Acquisition Variant Manifest

**Status:** RAW SOURCE MANIFEST — NOT INGESTED  
**Related question:** `RQ-031`  
**Normalized session:** `SESSION_025`

Two Google Doc outputs label themselves `SESSION_024`, but that identifier is already used in this repository for the Kilo public-genesis acquisition. They are therefore preserved here as Session 025 variants without rewriting their original self-labels.

## Variant A — concise artifact-claim pass

- **Source type:** Google Doc tab
- **Tab ID:** `t.cocjh043fuw4`
- **Source URL:** https://docs.google.com/document/d/1bRjBuxtBOj0xa9HjhqjGGnY6GKbktzATO4tlGMskh_Y/edit?tab=t.cocjh043fuw4
- **Document revision observed:** `ALtnJHwkdiWwnbEek1SVthG2BFlehfz5YLofU_yaBJPilYvCFJ2V6gGg7Mj7IW4Vi63Ky4QPM_P79whnDCPW3jgQgICMS-Rbi0OJygy23pg`
- **Original self-description:** `ARTIFACT-LEVEL INGESTION`
- **Original claimed counts:** five exact map records, three transmission edges, two canonical findings

### Claimed item records

1. Ptolemaic world map, Ulm edition, 1482.
2. Abraham Ortelius, *Typus Orbis Terrarum*, 1570.
3. Petrus Bertius, South Polar / Terra Australis map, 1616.
4. Bonaparte–Tasman map, approximately 1644.
5. James Cook, *A Chart of the Southern Hemisphere*, 1777.

### Claimed edges

- `Ortelius 1570 → Mercator 1569`
- `Bertius 1616 → Ortelius 1570`
- `Cook 1777 → Dalrymple 1770`

### Immediate preservation note

The first two edge directions run from later artifacts to earlier artifacts and therefore cannot represent ordinary historical transmission as written. The output's declarations of ingestion, canonical findings, and RQ status change are source claims only and have no curator force.

---

## Variant B — detailed artifact and lineage pass

- **Source type:** Google Doc tab
- **Tab ID:** `t.tpdmcjv83hvi`
- **Source URL:** https://docs.google.com/document/d/1bRjBuxtBOj0xa9HjhqjGGnY6GKbktzATO4tlGMskh_Y/edit?tab=t.tpdmcjv83hvi
- **Document revision observed:** `ALtnJHwkdiWwnbEek1SVthG2BFlehfz5YLofU_yaBJPilYvCFJ2V6gGg7Mj7IW4Vi63Ky4QPM_P79whnDCPW3jgQgICMS-Rbi0OJygy23pg`
- **Original self-description:** `DRAFT — First artifact pass`
- **Original closing claim:** `DOCUMENTED TRANSMISSION CHAIN — COMPLETE`
- **Original curator status:** `PENDING`

### Main candidate records

- Berlinghieri *Geographia*, Florence, 1482.
- Nicolaus Germanus / Ptolemy *Cosmographia*, Ulm, 1482.
- Stanford interpretive exhibit on Terra Australis.
- Ortelius, *Typus Orbis Terrarum*, 1570 and later states.
- Mercator world map, 1569.
- Bertius, *Descriptio Terrae Subaustralis* / *Magallanica sive Terra Australis Incognita*, 1616.
- Bonaparte–Tasman map, after 1644, possibly circa 1695.
- Blaeu and Thévenot derivatives.
- Cook's 1777 Southern Hemisphere chart.
- Bellingshausen and the 1820 observation transition.

### Useful self-quarantines already present

- Mercator 1569 southern content not yet verified from a surviving scan.
- Thévenot 1664 supported only by secondary material in the output.
- Bonaparte–Tasman map date and authorship disputed.
- Curator sign-off pending.

### Immediate preservation note

The output is much stronger as a research inventory than Variant A, but several records aggregate multiple holdings, editions, or states instead of identifying one exact item. Its claim of a complete chain conflicts with its own unresolved scans, disputed dates, secondary-only sources, and pending curator review.

---

## Variant C — Kilo public-source acquisition

- **Source type:** uploaded text export
- **Uploaded name:** `Pasted text(3).txt`
- **Observed byte size:** `26404`
- **SHA-256:** `0292caa36306bfd173d6c50c0ec28fbc07dad341fbed11e2ee20f7ebe02ee6a4`
- **Completion state:** TRUNCATED by model output limit
- **Raw export includes:** agent reasoning, search traces, acquisition records, edge table, chronology, reinterpretation layer, contradiction log, and an incomplete failed-search section

### Main contribution

Variant C broadens the lane beyond the five core maps. It adds candidate records for Waldseemüller, Schöner, Oronce Fine, Mercator, Plancius, Buache, Vaugondy, the competing 1820 observation claims, and the Mallery/Hapgood ice-free-Antarctica reinterpretation chain.

### Immediate preservation note

The export is incomplete and mixes raw tool chatter with research output. Several records still use generic hosts, commercial map descriptions, Wikipedia-derived relationships, or pending archive identifiers. One edge also reuses an already assigned record ID for a different map, so its IDs cannot be imported without normalization.

---

## Cross-variant preservation rule

These variants are independent acquisition outputs, not votes. Agreement between them raises a candidate's priority but does not establish truth or provenance.

No self-declared status such as `INGESTED`, `COMPLETE`, `CANONICAL`, `CONFIRMED`, or a numerical confidence score changes repository state. Only curator-reviewed item records and source-supported edges may be promoted.

See:

- `reports/SESSION_025_TERRA_CROSS_VARIANT_QC.md`
- `graph/chronologies/MAP-CHAIN-001-CANDIDATE-REGISTRY.md`
- `research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md`
