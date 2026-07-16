# SESSION 044 — Four-Variant Manifest

> **Input class:** four model acquisitions supplied by Sean after one Claude run split into two responses  
> **Target:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `DULCE-CAND-013`  
> **Status:** preserved and cross-compared; no origin declared; canonical seed unchanged

```yaml
SESSION:
  id: SESSION_044
  date_processed: 2026-07-16
  target_question: >
    What is the earliest exact carrier of the Castello/Branton mature
    Draco-master / Grey-worker-caste / Dulce linked hierarchy?

  variants:
    - id: VARIANT_A
      uploaded_name: "Pasted text(9).txt"
      size_bytes: 22905
      character_count: 22777
      sha256: 54b2c480841ca444c545dcc87c0688542dac36e31f700745bcd23b91ec24c848
      profile: EXACT_TEXT_AND_LAYER_RECOVERY_DATE_UNKNOWN

    - id: VARIANT_B
      uploaded_name: "Pasted markdown (2)(1).md"
      size_bytes: 15373
      character_count: 15291
      sha256: 1b96fcf64748706a743260055447f2c12ae6972b28e4a174e56b734dca3bade2
      profile: EXACT_CONTROL_SENTENCE_PLUS_SEPTEMBER_1990_LETTER_LEAD

    - id: VARIANT_C
      uploaded_name: "Pasted text (3)(2).txt"
      size_bytes: 10742
      character_count: 10568
      sha256: ccfb0839a224b3b48bac83ee1f5d0703f315040bbaad7dac296db471512d3197
      profile: CLAIMED_1991_SECURE_CARRIER

    - id: VARIANT_D
      uploaded_name: "Pasted markdown (4).md"
      size_bytes: 18766
      character_count: 18658
      sha256: 62ec6c5bc9031809331daad180ad5e01fa8b23dec5affc4e755f6278949bb08f
      profile: CLAIMED_SOFT_1996_CARRIER_AND_TEXTUAL_CONTINUITY
```

## Shared content finding

All four variants identify the surviving Castello/Branton Q&A layer as containing explicit mature hierarchy language, including variants of:

```text
The Draco are the undisputed masters of levels 5–6–7.

They work for, and are controlled by the Draco.

Grey worker caste / reptilian worker caste / Draconian leaders.

The Draco Race created type-one and type-two beings.
```

At the **text-content level**, the surviving Q&A satisfies the strict linked-chain test:

```text
identified Draco authority
        ↓ controls / creates / commands
identified Grey or worker group
        ↓ inside
Dulce levels / laboratories / secret-program system
```

## Date disagreement

```text
Variant A:
  original composition date unknown
  mid-1990s BBS carrier suggested but not item-level verified

Variant B:
  Q&A date unknown
  separate September 1990 Castello-to-Bishop letter reported in another chapter

Variant C:
  claims 1991 Branton compilation is securely dated
  does not supply an independently authenticated 1991 file header,
  physical copyright page, BBS timestamp or contemporaneous carrier

Variant D:
  claims 1996 as earliest securely datable carrier
  then correctly admits the date rests on retailer/catalogue metadata
  rather than physical first-edition inspection
```

## Curator result

```yaml
content_level_full_linked_chain: CONFIRMED_IN_SURVIVING_DERIVATIVE_TEXT
first_composition_date: UNKNOWN
first_carrier: UNKNOWN
first_securely_dated_carrier: UNRESOLVED
soft_1996_carrier_lead: PRESERVED_NOT_PROMOTED
claimed_1991_carrier: UNVERIFIED_DATE_ASSERTION
september_1990_letter: SEPARATE_ARTIFACT_LEAD
canonical_edge: false
seed_modified: false
```

## Layer boundaries

- `CASTELLO_VOICE` means the answer voice assigned by the document, not an authenticated historical speaker.
- An unmarked sentence is not automatically pre-Branton or non-Branton.
- `– Branton` reliably identifies some explicit editor notes, but the absence of that tag does not establish authorship.
- The questioner is not internally identified in the recovered Q&A.
- Branton-as-interviewer remains an inference.
- Multiple web hosts reproducing the same text are derivative copies, not independent witnesses.

## Outputs

- `reports/SESSION_044_FOUR_VARIANT_CROSS_QC.md`
- `graph/chronologies/CASTELLO_BRANTON_QA_VERSION_MATRIX.md`
- `data/error_fingerprints/ERR-036-007-QA-INTERVIEWER-INFERENCE-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-008-SOFT-DATE-HARD-DATE-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-009-DERIVATIVE-MIRROR-INDEPENDENCE-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-010-UNMARKED-TEXT-AUTHORSHIP-COLLAPSE.md`
- `research_inbox/SESSION_045_CASTELLO_QA_DATE_AND_CARRIER_AUDIT.md`
