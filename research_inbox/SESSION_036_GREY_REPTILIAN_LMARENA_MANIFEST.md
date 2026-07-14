# SESSION 036 — Grey / Reptilian LM Arena Acquisition Manifest

> **Input class:** LM Arena model output plus two uploaded artifacts supplied by Sean  
> **System:** `SYS-001 — Underground / Hidden-World Narrative System`  
> **Status:** preserved as raw acquisition; no direct import into canonical `/data/`

```yaml
SESSION:
  id: SESSION_036
  date: 2026-07-14
  source_platform: LM_ARENA
  requested_focus:
    - Grey imagery chronology
    - serpent/reptilian modern synthesis
    - Grey/Reptilian fusion in underground-base lore

  uploaded_artifacts:
    - filename: GREY_REPTILIAN_DEEP_DIVE_2026.md
      size_bytes: 19039
      sha256: 6ae9b40ef9d72ec1052f0bf8ce72f16cbaebaf2c0577395fc2c0e4d2279db2c2
      class: NARRATIVE_ACQUISITION
    - filename: grey_reptilian_extended_TIMELINE_2026-07-14.csv
      size_bytes: 7780
      sha256: a1c11a2b2982c8b90b55627c27f2505e97233e37dac58a203836bcd0d054f8ac
      class: PROPOSED_DATA_ROWS

  csv_profile:
    header_columns: 23
    proposed_rows: 11
    malformed_rows: 2
    id_collisions: 1
    directly_importable_rows: 0

  source_seed:
    file: data/grey_reptilian_motif_timeline_seed_2026-07-12.csv
    existing_records: 25
```

## 1. What the acquisition attempts

The model extends the existing 25-record seed with proposed rows for:

- Wells's Selenites;
- the *Outer Limits* / Hill contamination hypothesis;
- Marjorie Fish's Zeta Reticuli interpretation;
- *E.T.* and *The X-Files* as mass-media carriers;
- Maurice Doreal as a proposed Howard-to-Icke bridge;
- the 1983 miniseries *V*;
- an alleged late-1980s Grey/Reptilian hierarchy in Dulce literature;
- Roswell body-description evolution;
- the Lacerta internet text;
- Travis Walton event/book/film chronology.

The accompanying deep-dive also proposes two broad lineages:

```text
fiction / occult imagery
        ↓
testimony and hypnosis
        ↓
mass-media standardization
        ↓
later testimony and conspiracy synthesis
```

and:

```text
ancient serpent traditions
        ↓ modern retrospective use
Theosophy / weird fiction / occult pamphlets
        ↓
UFO and underground-base publishing
        ↓
political reptilian conspiracy synthesis
```

These remain research hypotheses, not imported transmission chains.

## 2. Structural defects in the CSV

### ID collision

The proposed row `MIX-003` describes a late-1980s Dulce Grey/Reptilian hierarchy.

The canonical seed already uses `MIX-003` for:

> 2020s AI-generated alien and Antarctica imagery / synthetic-media contamination.

The uploaded ID cannot be imported or reused.

### Malformed rows

`MIX-004` and `REPT-008` each contain a twenty-fourth unnamed field beyond the twenty-three-column header.

### Record-type mixing

Several rows combine different object types:

- event + book + film;
- series premiere + later-season mythology;
- source artifact + proposed transmission edge;
- multi-decade chronology + one atomic CSV row.

These must be separated before canonical ingestion.

## 3. Source-quality profile

The package contains a mixture of:

- primary-text links;
- institutional archive leads;
- Wikipedia and IMDb summaries;
- Grokipedia and fact-check aggregation pages;
- proposed scholarly interpretations without page locators;
- unsupported earliest-source claims;
- exact artifact records mixed with literal-claim evidence.

The package is therefore useful as a search map but not as a verified extension.

## 4. Primary-source spot checks completed during intake

### Wells, *The First Men in the Moon*

Project Gutenberg confirms the 1901 text and underground insect-like Selenite civilization.

The primary text describes a Selenite face as having:

- no nose;
- no ears;
- `dull bulging eyes at the side`;
- an insect-like or mask-like quality.

It does **not** support the uploaded row's wording `large black eyes`.

Primary text:

- `https://www.gutenberg.org/ebooks/1013`

### Betty and Barney Hill archive

The University of New Hampshire finding aid confirms:

- collection `MC 197`;
- papers covering 1961–2006;
- hypnosis transcripts;
- Marjorie Fish correspondence and star-chart material;
- later Zeta Reticuli publications and commentary.

It provides the correct acquisition path but does not itself resolve the *Outer Limits* contamination hypothesis.

Institutional record:

- `https://library.unh.edu/find/archives/collections/betty-barney-hill-papers-1961-2006`

## 5. Curator outputs

- `reports/SESSION_036_GREY_REPTILIAN_QC.md`
- `graph/bridges/BRIDGE-035-001-GREY-VISUAL-STANDARDIZATION.md`
- `graph/bridges/BRIDGE-036-001-REPTILIAN-GREY-FUSION.md`
- `research_questions/RQ-035-GREY-IMAGERY-STANDARDIZATION.md`
- `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`
- `research_inbox/SESSION_037_GREY_VISUAL_CONTAMINATION_BRIEF.md`
- `research_inbox/SESSION_038_REPTILIAN_DULCE_FUSION_BRIEF.md`

## 6. Curator decision

```text
Raw package value: HIGH
Canonical data-import readiness: NO
New research lanes justified: YES
Proposed Grey/Reptilian full lineages: UNVERIFIED
Highest-priority candidate: earliest item-level Grey/Reptilian hierarchy in Dulce-era print
Highest-priority contamination test: Hill descriptions versus pre-hypnosis media and earliest statements
```
