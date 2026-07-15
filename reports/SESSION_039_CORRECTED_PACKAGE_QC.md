# SESSION 039 — Corrected Session 036 Package Curator QC

> ## TOP-LEVEL STATUS
>
> ```text
> Submitted extension rows: 11
> Header columns: 23
> Structurally valid rows in submitted v2: 8
> Structurally malformed rows in submitted v2: 3
> Mechanically repaired v3 rows: 11/11
> Canonical imports approved: 0
> Mahoraga entity-collapse correction: supported
> Mahoraga modern-reptilian lineage: not established
> Canonical seed modified: no
> ```

## 1. CSV structural audit

The submitted file is not strict 23-column CSV despite its accompanying report.

| Record | Submitted fields | Audit result | Mechanical repair |
|---|---:|---|---|
| `GREY-014B` | 25 | two surplus trailing empty fields | trim to 23 |
| `MIX-004A` | 22 | missing `Possible Transmission / Influence` position | insert one empty field at column 13 |
| `MIX-004B` | 24 | one surplus trailing empty field | trim to 23 |

All other rows contain 23 fields.

The repaired output is:

```text
research_inbox/SESSION_036_EXTENSION_QC_FIXED_v3_STAGING.csv
```

This repair changes column alignment only. It does not authenticate dates, quotations, descriptions, source chains, or influence claims.

## 2. Corrective package strengths

### Wells

The corrected Selenite description no longer converts lateral bulging eyes into large black wraparound eyes. This removes an artificial resemblance to later Grey imagery.

### Hill chronology

The package now distinguishes:

```text
1961 event and earliest statements
        ≠
Betty's dreams
        ≠
1964 hypnosis sessions
        ≠
artist reconstructions
        ≠
1966 publication
        ≠
1975 dramatization
```

### Dulce fusion

The colliding proposed `MIX-003` is no longer treated as a timeline row. The target remains `BRIDGE-036-001` and Session 038's item-level `FULL / PARTIAL / NOT-MET` hierarchy test.

### Canonical boundary

The package correctly leaves:

```text
data/grey_reptilian_motif_timeline_seed_2026-07-12.csv
```

unchanged.

## 3. Evidence-readiness audit

The v3 staging CSV remains noncanonical because many rows rely on summaries or unresolved chronology.

### `GREY-010`

The episode's existence and broadcast date can be item-level facts. The proposed visual match and influence on Barney Hill remain separate claims. Actual exposure, session timing, exact prompts, and pre-exposure wording remain open.

### `INTERP-001-FISH`

The interpretation is correctly separated from the 1961 event. The exact first presentation date and publication sequence still require archival or contemporaneous records.

### `GREY-012` and `GREY-013A`

These are authentic media-object candidates. `Grey-adjacent`, normalization, and later mythology-carrier claims remain interpretations requiring feature and episode-level analysis.

### `REPT-006-ACQ`

The row remains an acquisition target. It cannot become an artifact record until exact Doreal editions, dates, pages, and scans are obtained.

### `REPT-007`

The 1983 miniseries is a valid media object. Influence on named later writers requires citation, interview, ownership, or distinctive reuse.

### `GREY-014A/B`

The event and book have been structurally separated, but neither row yet contains the earliest exact witness wording or item-level edition evidence needed for canonical comparison.

### `MIX-004A/B`

The split is methodologically better than one multi-decade row. The current sources remain summaries. Exact 1947 newspaper/military artifacts and exact later book editions must be ingested separately.

## 4. Mahoraga correction

### Corrected entity resolution

The name `Mahoraga` is not solely a modern manga invention. Scholarly references and Buddhist classification systems treat mahoragas as a class of serpent-associated nonhuman beings or deities, including among the classes protecting the Dharma. The modern *Jujutsu Kaisen* usage is a later pop-cultural reuse or English-rendering issue.

### Translation boundary

The uploaded correction repeats the English gloss `Great Reptilians`. That phrase should not become canonical without lexical qualification.

```text
mahā
        = great

uraga
        = serpent / snake

mahoraga
        = great serpent / great-serpent being
```

`Reptilian` has a modern biological and conspiracy-cultural meaning that can falsely imply continuity. The project should preserve the exact Sanskrit term and use `serpent-class being` or `great serpent` unless a cited translation uses another wording.

### Religious tradition boundary

Supported at current acquisition level:

- Mahoraga is an older religious/cosmological term, not created by modern manga.
- Buddhist sources and reference works place mahoragas among serpent-associated classes of beings.
- Anthropomorphic or part-serpent iconography is reported in later reference and art sources.

Still requiring decomposition:

- earliest dated textual occurrence by tradition;
- exact Hindu, Buddhist, and Jain source attestations separately;
- exact iconographic traditions and dates;
- whether `huge subterranean serpents rotating the earth` is tied to one specific text, commentary, or later dictionary description;
- documented modern conspiracy citation of Mahoraga;
- direct use by Icke or another named transmitter.

## 5. Error pattern

The Mahoraga case contains two opposite AI failures:

```text
POP-CULTURE COLLAPSE
older religious entity → reduced to current manga character

CONSPIRACY TRANSLATION COLLAPSE
older serpent term → translated into modern “reptilian” ontology
```

Both erase chronology and source type.

## 6. Promotion decisions

```yaml
GREY_009_CORRECTION:
  status: ACCEPTED_AS_STAGING_CORRECTION

SESSION_036_V2:
  status: PRESERVED_AS_SUBMITTED_NOT_IMPORT_SAFE

SESSION_036_V3:
  status: STRUCTURALLY_VALID_STAGING
  canonical_import: false

SERP_007_MAHORAGA:
  status: SUPPORTED_RELIGIOUS_MOTIF_CANDIDATE
  canonical_seed_row: false

MAHORAGA_TO_MODERN_REPTILIAN_CONSPIRACY:
  status: RETROACTIVE_REINTERPRETATION_HYPOTHESIS
  direct_transmission: NOT_ESTABLISHED
```

## 7. Next exact acquisitions

### RQ-035

- UNH collection-level and box/folder-level Hill records;
- earliest pre-hypnosis witness wording;
- exact hypnosis sessions and prompts;
- exact *Bellero Shield* visual artifact;
- exposure evidence or a documented negative.

### RQ-036

- Session 038 earliest `FULL` Grey/Reptilian hierarchy artifact;
- exact Doreal editions and passages;
- exact historical Mahoraga textual attestations by tradition;
- first dated modern source that appropriates `Mahoraga` or the gloss `Great Reptilians` into conspiracy framing.
