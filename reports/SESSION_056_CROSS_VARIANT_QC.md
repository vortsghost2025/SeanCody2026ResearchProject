# SESSION 056 — Cross-Variant QC

> ## TOP-LEVEL RESULT
>
> ```text
> Matrix II 1991 Pasturing section: CONFIRMED AT PAGE 95
> Matrix II 1990 first-edition presence: UNRESOLVED
> COSCON34 March 18, 1994 internal reference: SUPPORTED
> COSCON34 state terminus post quem: MARCH 18, 1994
> Mature Q&A composition before March 18, 1994: NOT ESTABLISHED
> COSCON34 = Cosmic Conflict chapter 34: HIGH-VALUE CARRIER-IDENTITY CANDIDATE
> COSCON34 = standalone BBS sequence file: NOT ESTABLISHED
> Dulce Book / Dulce Wars distinct title traditions: SUPPORTED
> Exact work/edition relation: OPEN
> Independent hierarchy witnesses represented: ONE BRANTON EDITORIAL FAMILY
> First mature carrier: UNRESOLVED
> Canonical edges created: NO
> ```

## 1. Matrix II result

The inspected 1991 third-edition scan places:

```text
PASTURING AND USE OF SURFACE EARTH HUMANS — The Reptilians
```

at page 95 in the table of contents, within the early Grey/Reptilian block. The inspected edition also acknowledges Jason Bishop III as a contributor.

This establishes:

```yaml
MATRIX_II_1991_THIRD:
  Pasturing_section_present: true
  table_of_contents_page: 95
  Bishop_acknowledgement: SUPPORTED
  hierarchy_stage: INTERMEDIATE_AND_CONTRADICTORY
```

It does not establish that the same section appears in the 458-page first edition.

### Early-page placement is not edition proof

The argument that a page-95 section is likely to have been part of the shorter first edition is plausible but non-dispositive. A later edition can insert or reorganize material near the front while expanding the total work by more than 200 pages.

Use:

```text
FIRST_EDITION_PRESENCE_PLAUSIBLE_INFERENCE
```

not:

```text
PASTURING_CONFIRMED_IN_1990_FIRST
```

The intermediate hierarchy therefore remains bounded to `1990_OR_1991`.

## 2. COSCON34 internal date

The surviving COSCON34 text reportedly cites a March 18, 1994 *Plain Dealer* article.

That creates a hard internal lower bound for the editorialized state containing that reference:

```yaml
COSCON34_EDITORIALIZED_STATE:
  terminus_post_quem: 1994-03-18
  basis: INTERNAL_CONTEMPORARY_NEWS_REFERENCE
```

### Critical chronology boundary

```text
March 18, 1994 reference inside a carrier
        ↓
carrier state cannot have been assembled before March 18, 1994
```

It does **not** establish:

```text
underlying Q&A already existed before March 18, 1994
```

The Q&A could have been written, edited or inserted on any date after the cited article and before the surviving carrier state. A terminus post quem for the composite carrier cannot be converted into a terminus ante quem for one embedded source layer.

Therefore these claims are rejected:

- `mature Q&A must have existed by March 1994`;
- `mature Q&A composition window closes before March 18, 1994`;
- `COSCON34 proves a 1990–March 1994 composition window`.

Safe result:

```yaml
COSCON34:
  surviving_editorialized_state: POST_1994_03_18
  underlying_QA_date: UNKNOWN
  October_1996_relation: UNRESOLVED
```

The October 1996 Branton self-date cannot function as a COSCON34 terminus ante quem until the exact work/carrier relationship is proved.

## 3. COSCON34 carrier identity

One variant proposes:

```text
COSCON34 = COSmic CONflict, chapter 34
```

This is a coherent and potentially important explanation, especially if the geocities or suddenlink carrier is presented within a *Cosmic Conflict* chapter index or title frame.

However, filename expansion alone does not prove carrier identity. The current evidence supplied to the curator did not include:

- an explicit *Cosmic Conflict* title header on the file;
- a complete contents page listing chapter 34;
- a publisher edition mapping chapter 34 to this exact Q&A;
- neighboring chapter files demonstrating the same naming convention;
- original archive directory context.

Current classification:

```yaml
COSCON34_IDENTITY:
  Cosmic_Conflict_chapter_34: HIGH_VALUE_CANDIDATE
  standalone_BBS_file_34: NOT_ESTABLISHED
  generic_BBS_provenance_search: DEPRIORITIZED_PENDING_IDENTITY_TEST
```

The Session 055 claim that COSCON34 may be a BBS-era file remains only a filename/format lead. The Session 056 claim that it definitely is not a BBS file also outruns the supplied item-level evidence.

## 4. Branton editorial status remains secure

Whatever the title or distribution carrier, the surviving COSCON34 state contains:

- the mature Q&A;
- Branton-style or Branton-attributed parentheticals;
- extended compiler commentary.

Therefore:

```text
COSCON34 surviving state
        = BRANTON_EDITED_OR_BRANTON_DERIVED
        ≠ UNEDITED_PRE_BRANTON_SOURCE
```

This remains the strongest secure COSCON result.

## 5. The Dulce Book versus The Dulce Wars

The variants agree that the titles are associated with Branton and overlap heavily in subject and source material. They differ on whether they are one work under two titles or distinct commercial works.

One variant reports commercial-edition leads such as:

- *The Dulce Book*, Global Communications, 2003;
- *The Dulce Wars*, Inner Light Publications, 2011, 168 pages.

These metadata leads support distinct title/edition records if verified item by item. They do not make the works independent witnesses, because both remain products of the same compiler and publishing ecosystem using the same underlying Q&A tradition.

Current result:

```yaml
BRANTON_TITLE_FAMILY:
  distinct_title_names: CONFIRMED
  distinct_commercial_edition_leads: SUPPORTED
  identical_work: NOT_PROVED
  retitled_or_abridged_relation: PLAUSIBLE
  two_distinct_compilations: NOT_EXCLUDED
  independent_source_count: ONE_EDITORIAL_FAMILY
```

Hayakawa calling them `two major books` is secondary naming evidence, not a chapter-level work-identity proof.

## 6. Rejected carryovers from one variant

The following claims are not promoted because they conflict with earlier raw-evidence controls or are unsupported in the supplied result:

- `1994 Hinkle composition date` as settled chronology;
- `2010 Hinkle Avalon post contains the mature Q&A` as settled;
- `earliest hard-dated mature carrier is 2003` without exact first-edition inspection;
- `COSCON34 definitely equals Cosmic Conflict chapter 34` from filename alone;
- `The Dulce Book and The Dulce Wars are confirmed distinct works` without item-level title/copyright/contents comparison;
- `Branton 1991 family` as a secure compilation date.

The Avalon rollback remains in force: testimony and thread date are secure; Q&A presence is disputed.

## 7. Current chronology

```text
1987-12-13:
Lear distributes drawings and related enclosures
no mature hierarchy located
        ↓
reported 1989:
LeVesque/Bishop proto-hierarchy
item-level date open
        ↓
1990 or 1991:
Matrix II intermediate hierarchy
confirmed in 1991 third edition;
1990 first-edition presence unresolved
        ↓
unknown date:
mature Q&A source composition
        ↓
after 1994-03-18:
COSCON34 surviving editorialized state
contains mature Q&A + Branton commentary
        ↓
October 1996:
Branton compilation self-date in a related carrier tradition
exact relation to COSCON34 open
        ↓
later commercial and web title family
```

## 8. Curator decision

```yaml
SESSION_056:
  Matrix_II_Pasturing_1991_page: 95
  Matrix_II_Pasturing_1990: UNKNOWN
  intermediate_hierarchy_year: 1990_OR_1991

  COSCON34_editorialized_state_TPQ: 1994-03-18
  COSCON34_underlying_QA_date: UNKNOWN
  COSCON34_Cosmic_Conflict_identity: CANDIDATE_NOT_CONFIRMED
  COSCON34_unedited_pre_Branton: false

  Dulce_Book_Wars_distinct_titles: true
  Dulce_Book_Wars_exact_work_relation: OPEN
  Branton_family_independent_count: 1

  mature_QA_composition_window: UNRESOLVED
  first_mature_carrier: UNRESOLVED
  canonical_authorship_edge: false
  canonical_first_carrier_edge: false
  canonical_work_identity_edge: false
  next_session: SESSION_057
```
