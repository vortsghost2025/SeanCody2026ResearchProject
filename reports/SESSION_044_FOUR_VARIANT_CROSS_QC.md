# SESSION 044 — Four-Variant Cross-QC

> ## TOP-LEVEL RESULT
>
> ```text
> Model variants reviewed: 4
> Exact mature linked wording recovered: YES
> FULL_LINKED_CHAIN at text-content level: YES
> Original composition date recovered: NO
> First exact carrier recovered: NO
> Claimed secure 1991 carrier: REJECTED_PENDING_ITEM-LEVEL PROOF
> Claimed 1996 carrier: SOFT BIBLIOGRAPHIC BOUND ONLY
> September 1990 letter: SEPARATE ARTIFACT LEAD
> Canonical hierarchy edge created: NO
> RQ-036: SEARCHING
> ```

## 1. What is now established

The surviving Castello/Branton Q&A text contains an explicit connected hierarchy, not merely co-presence.

The strongest relationship sentence reported across the variants is:

> `They work for, and are controlled by the Draco. There are other gray skinned beings that are not in league with the Draco.`

The surrounding Q&A layer also contains wording equivalent to:

- Draco as undisputed masters of Dulce levels 5–6–7;
- humans as second in command;
- white Draco deciding matters for worker castes;
- Grey, reptilian and other worker-caste categories;
- beings said to have been created by the Draco Race;
- Dulce laboratories, cages, vats and secret-program context.

Therefore:

```yaml
CASTELLO_BRANTON_QA_SURVIVING_TEXT:
  A_entity: DRACO_OR_WHITE_DRACO_AUTHORITY
  B_group: GREY_OR_WORKER_CASTE_SUBSET
  A_to_B_status: EXPLICIT
  C_system: DULCE_LEVELS_LABS_SECRET_PROGRAM
  AB_to_C_status: EXPLICIT_IN_DOCUMENT_CONTEXT
  hierarchy_result: FULL_LINKED_CHAIN_AT_TEXT_LEVEL
```

This resolves the **content question**.

It does not resolve the **chronology or authorship question**.

## 2. The four date claims

### Variant A — unknown date / probable mid-1990s compilation

Useful:

- recovered a large set of exact hierarchy passages;
- separated answer voice, questions and explicitly tagged Branton notes;
- correctly kept the first carrier unresolved;
- recognized that later web hosts descend from one textual family.

Corrections:

- `mid-1990s BBS` was not established by an exact timestamped carrier;
- references to later personalities inside Branton notes can date that edited note layer, not automatically the underlying Q&A answers;
- a reported fabrication admission requires exact page, recording or transcript before direct-confession promotion.

### Variant B — exact control sentence / September 1990 letter lead

Strongest contribution:

- recovered the cleanest single A→B sentence;
- separated the September 1990 Castello-to-Bishop letter from the Q&A;
- correctly concluded that text-level FULL and date-level FULL are different findings;
- correctly rejected the unverified July 1990 newsletter claim.

Corrections:

- multiple mirrors are not independent evidence;
- the absence of a `– Branton` tag does not prove the sentence predates Branton or belongs to another author;
- the September 1990 date is itself known through Branton's later chapter framing unless the original letter is recovered.

### Variant C — claimed secure 1991 carrier

Useful:

- supplied a detailed sentence-layer decomposition;
- recognized the strict linked chain in the Q&A;
- separated the later printed *Dulce Wars* object.

Rejected or quarantined:

- the report calls the 1991 Branton compilation `CONFIRMED_PRIMARY` without producing an original 1991 BBS header, dated file, physical copyright page, contemporaneous catalogue or archive record;
- an internal note saying an article was written in 1991 does not date the entire Q&A or compilation;
- an Archive.org item uploaded in 2016 does not authenticate a 1991 file state;
- the report claimed repository synchronization it did not itself perform.

Current classification:

```text
CLAIMED_1991_DULCE_BOOK_CARRIER
        = UNVERIFIED_DATE_ASSERTION
```

### Variant D — soft 1996 carrier

Useful:

- distinguished exact content from carrier dating;
- treated 1996 as retailer/catalogue metadata rather than physical inspection;
- preserved interviewer silence and hostile secondary claims as separate evidence classes;
- identified lexical continuity between `in league` phrasings as a transmission lead.

Corrections:

- retailer repetition does not make the date secure;
- a re-typeset PDF header is not a first-edition colophon;
- web pages that `look circa 1997` are not date evidence;
- lexical resemblance does not by itself establish direct derivation, copying or common authorship.

Current classification:

```text
THE_DULCE_BOOK_1996
        = SOFT_BIBLIOGRAPHIC_CARRIER_LEAD
        ≠ SECURE_FIRST_CARRIER
```

## 3. Layer-assignment rule

The surviving text supports at least these document roles:

```yaml
source_layers:
  CASTELLO_VOICE:
    meaning: answer voice presented by the document
    does_not_mean: authenticated historical speaker

  QUESTIONER_VOICE:
    meaning: questions in the Q&A
    identity: UNKNOWN

  BRANTON_EDITOR_NOTE:
    evidence: explicit Branton signature or clear bracketed attribution

  COMPILER_SEQUENCE:
    meaning: chapter order, headings and juxtaposition
    likely_editor: Branton in surviving compilation

  EARLIER_SOURCE_TEXT:
    meaning: quoted or incorporated TAL/Hamilton/Bennewitz material

  LATER_WEB_EDITOR:
    meaning: spelling, punctuation, markup and normalization changes
```

### Critical boundary

```text
explicitly tagged `– Branton`
        = Branton note

no tag
        ≠ automatically Castello-authored
        ≠ automatically pre-Branton
        ≠ automatically an untouched source layer
```

The unmarked hierarchy wording can be assigned to the **Q&A answer layer**, but not securely to an authenticated person or pre-compilation document.

## 4. Derivative mirror problem

The recovered hosts reproduce substantially the same chapter text, punctuation patterns, question order and editor notes.

They are evidence that the text circulated widely, but not evidence of independent testimony or independent transcription.

```text
nine matching web pages
        may equal
one inherited Branton compilation copied nine times
```

Use the earliest recoverable page only as a carrier bound, never as nine-source convergence.

## 5. September 1990 letter

One variant reports a separate chapter introduction:

> `In a letter dated Sept. 1990, written by Thomas E. Castello and addressed to researcher Jason Bishop...`

Current status:

```yaml
DULCE_CAND_022:
  object: CASTELLO_TO_BISHOP_LETTER
  reported_date: SEPTEMBER_1990
  date_basis: LATER_BRANTON_CHAPTER_HEADER
  original_letter_recovered: false
  relationship_to_QA: UNKNOWN
  full_linked_wording: UNKNOWN
  status: SEPARATE_ARTIFACT_LEAD
```

The date cannot be transferred to the Q&A.

## 6. Textual continuity lead

The comparison:

```text
Bishop witness:
Greys and Reptoids are `in league with each other`

Q&A:
some Greys `work for, and are controlled by the Draco`;
other Grey beings are `not in league with the Draco`
```

is a valuable lexical and conceptual continuity lead.

Current classification:

```text
SUPPORTED_LEXICAL_CONTINUITY_CANDIDATE
        ≠ DIRECT_DERIVATION
        ≠ KNOWN_COPY
        ≠ SAME_AUTHORSHIP
```

Promotion requires version order, shared rare errors, direct citation, manuscript evidence or another transmission fingerprint.

## 7. Current chronology

```text
reported 1989:
Bishop III witness
alliance/tension + opposition

1991 inspected Matrix II third edition:
opposition + separate Grey-creator model

undated surviving Q&A layer:
Draco-master / Grey-worker-caste FULL linked hierarchy

reported 1990 letter:
separate Castello-to-Bishop object; contents and relation unresolved

claimed 1991 Dulce Book state:
not item-level authenticated

attested 1996 Dulce Book carrier:
soft retailer/catalogue date; first edition not inspected

later print and web circulation:
mature hierarchy widely reproduced
```

## 8. Curator decision

```yaml
SESSION_044:
  full_linked_chain_content: CONFIRMED
  full_linked_chain_source_layer: Q_AND_A_ANSWER_LAYER
  attributed_speaker_identity: UNVERIFIED_DOCUMENT_PERSONA
  questioner_identity: UNKNOWN
  branton_as_interviewer: INFERENCE_ONLY

  first_composition_date: UNKNOWN
  first_carrier: UNKNOWN
  earliest_securely_dated_carrier: UNRESOLVED
  soft_carrier_lead: THE_DULCE_BOOK_1996
  separate_dated_lead: SEPTEMBER_1990_CASTELLO_TO_BISHOP_LETTER

  exact_text_locus: DULCE-CAND-012
  canonical_transmission_edge: false
  seed_modified: false
  next_session: SESSION_045
```
