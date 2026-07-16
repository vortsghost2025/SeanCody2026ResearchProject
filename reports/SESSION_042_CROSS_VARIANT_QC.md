# SESSION 042 — Cross-Variant QC

> ## TOP-LEVEL RESULT
>
> ```text
> Model variants reviewed: 3
> Exact physical primary issues acquired: 0
> Direct primary text inspected by curator: Matrix II, 1991 third-edition OCR
> Secure FULL linked hierarchy artifacts: 0
> Matrix II FULL claim: REJECTED
> UFO Universe FULL claim: NOT ESTABLISHED
> O'Connell mailer date: UNRESOLVED
> Candidate-title collapse corrected: YES
> A+B+C test revised to require linkage: YES
> RQ-036: SEARCHING
> ```

## 1. Main correction: co-presence is not a hierarchy chain

Session 042 exposed a flaw in the earlier A+B+C shorthand.

An artifact may contain:

- reptilian or Draconian entities somewhere;
- Greys described as created or controlled somewhere else;
- underground bases or treaties elsewhere;

without asserting that the reptilian group is the authority controlling those Greys inside that base system.

The decisive test is now:

```text
A = an identified reptilian / Draconian authority
        ↓ explicit or securely implied same-referent relationship
B = Greys controlled, created, commanded, used or serving that A
        ↓ explicit or securely implied same-system relationship
C = that A→B relationship occurs inside an underground-base,
    treaty, genetic-experiment or secret-program system
```

`FULL_LINKED_CHAIN` requires the connected relationship, not merely all three ingredients in one long compilation.

## 2. Matrix II result

The accessible Internet Archive text identifies itself as:

```text
MATRIX II
Third Edition Printing
With Added New Material
Leading Edge Research Group
Copyright 1990, 1991 Valdamar Valerian
```

It is not automatically identical to the reported 1990 first edition.

### What the text contains

The scan contains:

- a table-of-contents entry titled `RELATIONSHIPS BETWEEN NEGATIVE GREYS AND REPTILIANS`;
- reptilian species and an internal reptilian elite;
- extensive Grey material;
- underground-base and secret-program claims;
- a passage in which a `very high` culture creates cloned Greys;
- an editor note explicitly calling Reptilian humanoids enemies of Greys.

### What it does not establish

The acquired wording does not link the reptilian elite to creation or command of the Greys.

Instead it preserves at least two separate relationship models:

```text
very high non-reptilian culture
        ↓ creates / controls Greys

Reptilian humanoids
        ↔ enemies of Greys
```

Therefore:

```yaml
MATRIX_II_1991_SCAN:
  A_reptilian_authority: PRESENT_WITHIN_REPTILIAN_SPECIES
  B_greys_subordinate_to_same_A: ABSENT
  C_secret_program_base_context: PRESENT
  A_to_B_link: CONTRADICTED_OR_ABSENT
  hierarchy_status: PARTIAL_AC_OPPOSITIONAL
  source_status: CONFIRMED_PRIMARY_FOR_1991_THIRD_EDITION
```

It is not `FULL` for the Draco-over-Grey chain.

### Edition boundary

The first edition is reported as 1990, but Session 042 did not acquire its full pages. No claim about wording in the 1990 first edition may be made from the 1991 third-edition scan without a version comparison.

## 3. Matrix II citation-conflation warning

Later lists attribute wording such as `Greys were the work force of the Draco` to *Matrix II*.

The inspected scan did not yield that phrase. It instead contains the enemies-of-Greys framing and separate higher-culture creation narrative.

Current classification:

```text
MATRIX_II_DRACO_WORKFORCE_ATTRIBUTION
        = UNVERIFIED_LATER_CITATION
        + POSSIBLE_SOURCE_TAG_MISALIGNMENT
        + REQUIRES_EXACT_PAGE
```

No later writer's parenthetical source tag can override the primary text.

## 4. TAL article-title and carrier correction

Session 041 had collapsed two artifacts.

### Artifact 1

```yaml
title: "The Deep Dark Secret at Dulce"
creators:
  - Bill Hamilton
  - TAL LeVesque
carrier: "UFO Universe"
reported_issue: "Feb–Mar 1991"
```

The accessible transcription attributes the article to both Hamilton and LeVesque.

Recovered content establishes:

- Dulce base and biogenetic-laboratory claims;
- Greys and tall reptilian humanoids as present;
- TAL's claimed Reptoid encounter.

It does not, in the recovered passages, explicitly place Greys beneath reptilian authority.

```yaml
UFO_UNIVERSE_ARTICLE:
  A: REPTILIAN_PRESENCE_NOT_SECURE_AUTHORITY
  B: NOT_ESTABLISHED
  C: ESTABLISHED_IN_TRANSCRIPTION
  status: PARTIAL_C_WITH_REPTILIAN_PRESENCE
  source_status: SECONDARY_TRANSCRIPTION_PENDING_MAGAZINE_SCAN
```

### Artifact 2

```yaml
title: "The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base"
creator: TAL LeVesque
carrier: "Patrick O'Connell mailer/newsletter"
date: UNKNOWN
```

The Branton-hosted transcription contains quoted TAL language stating that the reptilian race was returning and that Greys, described as mercenaries, were being used to interface with and manipulate humans.

That language may imply an A→B relationship, but:

- the agent doing the using is partly implicit;
- the original mailer has not been recovered;
- the date is unverified;
- Branton editorial notes are interleaved with TAL quotations;
- an explicit hierarchy note placing Winged Draco above Lizard Men and Greys is Branton's note, not part of the quoted TAL wording.

Current classification:

```yaml
OCONNELL_TAL_ARTICLE:
  A: PRESENT_IN_REPRINTED_TAL_TEXT
  B: IMPLIED_GREY_MERCENARY_USE
  C: PRESENT
  A_to_B_link: IMPLIED_NOT_SECURE
  source_status: LATE_TRANSCRIPTION_OF_UNRECOVERED_MAILER
  date_status: UNKNOWN
  hierarchy_status: FULL_LINKED_CANDIDATE_UNDATED_UNVERIFIED
```

## 5. Variant evaluation

### Variant A

Useful contributions:

- correctly separated the two TAL article titles;
- identified the 1991 *Matrix II* scan and first-edition problem;
- surfaced *Alien Magic*, *Cosmic Top Secret* and 1989 `The Dulce Base` leads;
- retained failed searches.

Problems:

- used `PARTIAL-AC / PARTIAL-BC` language too loosely for the *UFO Universe* article;
- treated a table-of-contents heading as evidence of hierarchy content;
- suggested `dominant reptilian species` could satisfy Grey subordination without a same-referent link;
- relied on secondary mirrors for magazine wording.

### Variant B

Useful contribution:

- proposed a specific bibliographic lead: `Trends and Predictions Analyst`, Vol. 6 No. 2, July 1990.

Rejected or quarantined claims:

- no primary scan, masthead, contents, page or independent catalogue record was supplied;
- the report called the July 1990 carrier securely dated despite admitting the physical item was not recovered;
- it assigned `FULL` from later reprinted wording;
- it stated repository synchronization that the model did not actually perform.

The issue/date claim remains a search lead only:

```text
PATRICK_O_CONNELL_JULY_1990_VOL_6_NO_2
        = UNVERIFIED_BIBLIOGRAPHIC_LEAD
```

### Variant C

Strongest methodological contribution:

- correctly rejected *Matrix II* as the Draco-over-Grey hierarchy source;
- identified the enemies-of-Greys wording;
- corrected *UFO Universe* co-authorship;
- distinguished article title and carrier;
- kept the exact-first-FULL question open.

Remaining corrections:

- Branton and other mirrors are not primary-source evidence for the magazine issue;
- the 1991 third edition cannot establish the exact wording of a 1990 first edition;
- *Matrix II* contains reptilian authority language internally, so `PARTIAL-AC_OPPOSITIONAL` is more precise than saying A is wholly absent.

## 6. LeVesque / Castello claim boundary

Secondary historical sources report that LeVesque later acknowledged Thomas Castello as creative writing or fabrication.

The project may record this as evidence about authorship and claimed eyewitness status, but it must keep separate:

```text
artifact existed and circulated
        ≠
claimed witness existed
        ≠
claims inside artifact were factual
```

The report of a later admission requires its own exact book page, interview or recording before promotion to a direct-confession edge.

## 7. Revised candidate order

```text
1989 reported candidates:
- TAL / Jason Bishop III, The Dulce Base
- Bill Hamilton, Alien Magic
        = exact physical copies and hierarchy wording not acquired

1990 reported candidate:
- Matrix II first edition
        = pages not acquired; 1991 third edition is oppositional, not linked hierarchy

undated / reported pre-1991:
- O'Connell-carried TAL article
        = strongest linked-language candidate, but original and date absent

Feb–Mar 1991:
- Hamilton + LeVesque, The Deep Dark Secret at Dulce
        = C plus reptilian presence; B not recovered

later early-1990s:
- Castello Q&A / Branton compilations
        = mature FULL wording, exact earliest state unresolved
```

## 8. Curator decision

```yaml
SESSION_042:
  matrix_ii_1991:
    status: PARTIAL_AC_OPPOSITIONAL
    full_chain: false

  ufo_universe_1991:
    title: "The Deep Dark Secret at Dulce"
    authors: "Bill Hamilton and TAL LeVesque"
    status: PARTIAL_C_WITH_REPTILIAN_PRESENCE

  oconnell_tal_article:
    title: "The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base"
    date: UNKNOWN
    status: FULL_LINKED_CANDIDATE_UNDATED_UNVERIFIED

  july_1990_newsletter_claim:
    status: UNVERIFIED_BIBLIOGRAPHIC_LEAD

  alien_magic_1989:
    status: UNVERIFIED_HIGH_PRIORITY

  exact_first_full_linked_chain: UNRESOLVED
  canonical_edge_created: false
  seed_modified: false
  next_session: SESSION_043
```
