# SESSION 045 — Castello Q&A Date and Carrier Audit

**Targets:** `DULCE-CAND-012`, `DULCE-CAND-013`, `DULCE-CAND-022`  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** exact-object dating, carrier reconstruction, version-layer audit  
**Status:** OPEN — no origin declaration

## Objective

The content question is resolved:

```text
surviving Castello/Branton Q&A
        = FULL_LINKED_CHAIN_AT_TEXT_LEVEL
```

The remaining question is:

> When, where and in which exact object did that wording first appear?

## Priority 1 — Original or earliest Q&A carrier

Search exact phrases and spelling variants:

```text
They work for, and are controlled by the Draco
other gray skinned beings that are not in league with the Draco
Draco are the undisputed masters of the 5-6-7 levels
gray worker caste
white Draconian boss
Khaarshfashst / Karsh
Leader Castello
Senior Security Technician
```

Acquire one exact:

- BBS file with header or timestamp;
- ParaNet/FidoNet/Usenet message;
- newsletter or fanzine;
- typed or photocopied manuscript;
- mail-order enclosure;
- conference handout;
- cassette transcript;
- early printed edition.

Return complete object images or raw file, not a modern mirror.

## Priority 2 — Test the claimed 1991 carrier

One Session 044 variant asserted a 1991 *Dulce Book* carrier.

Do not repeat the assertion. Acquire:

```text
original filename
BBS or post header
creation / upload / modification timestamp
internal version statement
copyright or foreword page
contemporaneous citation
collector or archive provenance
complete Q&A text
```

Distinguish:

- an article internally described as written in 1991;
- a later editor note referring to 1991;
- a compilation created in 1991;
- a file later labelled 1991;
- an upload occurring years later.

Valid result only with item-level proof.

## Priority 3 — Test the soft 1996 carrier

Acquire the earliest exact *The Dulce Book* object claimed as 1996.

Return:

```text
title page
copyright page
publisher / distributor
printing statement
ISBN or catalogue number
extent and chapter order
Chapter 11 pages
physical or digital provenance
contemporary advertisement or catalogue
```

Compare against later electronic and print copies.

Use:

- `PHYSICAL_1996_CARRIER_CONFIRMED`
- `SOFT_1996_METADATA_ONLY`
- `DATE_CONFLICT`
- `NOT_RECOVERED`

## Priority 4 — September 1990 letter

Target the separately reported object:

> a letter dated September 1990 from Thomas E. Castello to Jason Bishop

Acquire:

```text
original or earliest scan
full letter
address / salutation / signature
postmark or internal date
carrier chapter and editor framing
exact hierarchy wording
relationship to the Q&A
```

Do not transfer the letter date to the Q&A.

## Priority 5 — Source-layer version diff

For every recovered Q&A state tag each sentence:

```yaml
source_layer:
  - Q_AND_A_ANSWER_VOICE
  - QUESTIONER_VOICE_UNKNOWN
  - EXPLICIT_BRANTON_NOTE
  - COMPILER_HEADING_OR_SEQUENCE
  - TAL_OR_BISHOP_QUOTATION
  - HAMILTON_QUOTATION
  - BENNEWITZ_QUOTATION
  - LATER_WEB_EDITOR
  - UNKNOWN
```

Compare:

- hierarchy sentences;
- question order;
- spelling of names;
- bracketed notes;
- references to later figures;
- chapter headings;
- added and removed paragraphs.

## Priority 6 — Lexical-continuity test

Compare exact contexts for:

```text
Bishop: `in league with each other`
Q&A: `not in league with the Draco`
```

Test:

- shared rare wording;
- copied punctuation or errors;
- same paragraph neighbors;
- direct citation;
- same compiler source list;
- intermediate version.

Allowed result:

- `SUPPORTED_LEXICAL_CONTINUITY_CANDIDATE`
- `KNOWN_COPY`
- `DIRECT_DERIVATION`
- `COMMON_SOURCE`
- `COINCIDENTAL_OR_GENERIC`
- `UNKNOWN`

Do not promote resemblance alone.

## Required table

| Object | Exact date basis | Physical/digital state | Hierarchy text present | Source layers | Earliest carrier status | Main barrier |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

## Stop rules

Do not:

- count multiple mirrors as independent witnesses;
- infer authorship from absence of a `– Branton` signature;
- identify the questioner as Branton without direct evidence;
- treat an Archive.org upload date as composition date;
- call retailer metadata a securely dated first edition;
- transfer the September 1990 letter date to the Q&A;
- use an alleged event date as a document date;
- claim direct derivation from lexical resemblance alone;
- declare an origin without the exact object.

## Deliverables

1. Earliest exact carrier or bounded failure report.
2. 1991 date audit.
3. 1996 physical carrier audit.
4. September 1990 letter record.
5. Sentence-level version diff.
6. Lexical-continuity assessment.
7. Archive, dealer and collector contact log.
8. Recommendation only; curator promotion required.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/METHODOLOGY.md`, `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`, `graph/bridges/BRIDGE-036-001-REPTILIAN-GREY-FUSION.md`, `graph/chronologies/DULCE-HIERARCHY-CANDIDATE-REGISTRY.md`, `graph/chronologies/CASTELLO_BRANTON_QA_VERSION_MATRIX.md`, `reports/SESSION_044_FOUR_VARIANT_CROSS_QC.md`, and error fingerprints `ERR-036-007` through `ERR-036-010`. Execute `research_inbox/SESSION_045_CASTELLO_QA_DATE_AND_CARRIER_AUDIT.md`. The mature hierarchy text is already confirmed at the content level. Work only on its first exact carrier, exact date, version and source layers. Test the claimed 1991 state, the soft 1996 carrier, the separate September 1990 letter and the lexical relation between Bishop's `in league` wording and the Q&A. Return complete objects, headers, title/copyright pages, exact passages, provenance, version differences and failed searches. Do not declare an origin.
