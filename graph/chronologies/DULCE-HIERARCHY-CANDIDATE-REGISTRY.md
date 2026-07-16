# Dulce Grey/Reptilian Hierarchy Candidate Registry

> **Related question:** `RQ-036`  
> **Related bridge:** `BRIDGE-036-001`  
> **Status:** candidate registry only; no origin or canonical transmission edge

## Decisive linked-chain test

```text
A = identified reptilian / Draconian authority
        ↓ same-referent relationship
B = Greys controlled, created, commanded, used or serving that A
        ↓ same-system relationship
C = underground base, treaty, genetic experiment or secret program
```

`FULL_LINKED_CHAIN` requires the relationship, not mere A+B+C co-presence.

Required relationship fields:

```yaml
relationship_linkage:
  A_entity:
  B_grey_group:
  A_to_B_wording:
  A_to_B_status: EXPLICIT | IMPLIED | ABSENT | CONTRADICTED | UNKNOWN
  C_system:
  AB_to_C_wording:
  AB_to_C_status: EXPLICIT | IMPLIED | ABSENT | UNKNOWN
  co_presence_only: true | false
```

## Candidate table

| ID | Exact candidate | Reported date | Source status | Relationship result | Current hierarchy result | Main barrier |
|---|---|---:|---|---|---|---|
| `DULCE-CAND-001` | McCampbell–Bennewitz conversation transcript | 1984-07-13 | `CONTEMPORARY_TRANSCRIPT_LEAD` | C only | `PARTIAL-C_CANDIDATE` | clean transcript/audio chain not acquired |
| `DULCE-CAND-002` | George C. Andrews, *Extra-Terrestrials Among Us* | 1986 | `PRIMARY_ITEM_METADATA_ONLY` | unknown | `UNKNOWN` | primary text not inspected |
| `DULCE-CAND-003` | John Lear transmittal letter to `Steven` | 1987-12-13 | `DATED_MIRROR_SCAN_PENDING_CUSTODY` | C only | `PARTIAL-C_CANDIDATE` | original custody and enclosure set unresolved |
| `DULCE-CAND-004` | John Lear public statement / `The UFO Cover-Up` | 1987-12-29; revisions 1988 | `VERSIONED_PRIMARY_TEXT_PENDING_ALIGNMENT` | C only | `PARTIAL-C` | original and revisions must be aligned |
| `DULCE-CAND-005` | `The Dulce Papers` physical photo/drawing set | reported 1987 | `PRIMARY_ITEM_METADATA_ONLY` | C reported; A→B unknown | `PARTIAL-C_OR_UNKNOWN` | original set not recovered; later expansions conflated |
| `DULCE-CAND-006` | Paul Bennewitz, *Project Beta* | reported 1986–1988 | `PRIMARY_TEXT_CONTAMINATED_BY_LATER_INSERTIONS` | C only in recoverable source layer | `PARTIAL-C` | clean typescript and exact date unavailable |
| `DULCE-CAND-007` | Bill Cooper ParaNet statements | 1988 | `UNVERIFIED_BBS_TEXT` | unknown | `UNKNOWN` | exact posts not acquired |
| `DULCE-CAND-008` | Bill Cooper, *Behold a Pale Horse* | 1991 | `PRIMARY_ITEM_AVAILABLE_PAGE_AUDIT_OPEN` | C; no linked Draco→Grey chain located | `PARTIAL-C` | page-level hierarchy audit incomplete |
| `DULCE-CAND-009` | Valdamar Valerian, *Matrix II* | first edition reported 1990; inspected third edition 1991 | `CONFIRMED_PRIMARY_FOR_1991_THIRD_EDITION` | reptilian elite present; Greys created by different higher culture; Reptilians described as enemies of Greys | `PARTIAL-AC_OPPOSITIONAL` | 1990 first edition unavailable; later Draco-workforce citation unresolved |
| `DULCE-CAND-010` | Bill Hamilton + TAL LeVesque, `The Deep Dark Secret at Dulce`, *UFO Universe* | reported Feb–Mar 1991 | `SECONDARY_TRANSCRIPTION_PENDING_MAGAZINE_SCAN` | reptilian presence + C; B not established | `PARTIAL-C_WITH_REPTILIAN_PRESENCE` | exact issue, pages and unabridged text not acquired |
| `DULCE-CAND-011` | TAL LeVesque, `The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base`, Patrick O'Connell mailer | unknown; one model reports July 1990 Vol. 6 No. 2 without primary proof | `LATE_TRANSCRIPTION_OF_UNRECOVERED_MAILER` | Grey mercenary use implied in reptilian context | `FULL_LINKED_CANDIDATE_UNDATED_UNVERIFIED` | original mailer, date, byline page and full text absent |
| `DULCE-CAND-012` | `Thomas Castello Declaration` / Branton Q&A | surviving 1990s forms; claimed earlier | `LATE_COMPILATION_OR_UNVERIFIED_CLAIM` | explicit mature Draco→Grey→Dulce wording in later forms | `FULL_CONTENT_UNDATED` | identity, interview date, earliest text and authorship unresolved |
| `DULCE-CAND-013` | Branton, *The Dulce Book* | early-1990s reported | `FULL_CONTENT_DATE_UNRESOLVED` | explicit mature linked chain in surviving compilations | `FULL_CONTENT_UNDATED_OR_BOUNDED` | first BBS/manuscript state not located |
| `DULCE-CAND-014` | `Galactic Races` hosted text | unknown | `UNVERIFIED_CLAIM` | near-linked hierarchy language; date/authorship unknown | `UNKNOWN` | originating file and date unknown |
| `DULCE-CAND-015` | Branton, *The Dulce Wars* | reported 1999; later editions conflict | `PRIMARY_ITEM_METADATA_ONLY` | mature linked chain reported | `FULL_CONTENT_LATE_PRINT` | first-edition pages and exact passage not acquired |
| `DULCE-CAND-016` | TAL / Jason Bishop III, `The Dulce Base` | reported 1989 | `SECONDARY_SUMMARY` | C confirmed in quoted passage; A→B not located | `PARTIAL-C_CANDIDATE` | original manuscript/BBS file and date absent |
| `DULCE-CAND-017` | Bill Hamilton, *Alien Magic* | reported 1989 | `UNVERIFIED_CLAIM` | unknown | `UNKNOWN_HIGH_PRIORITY` | no copy, catalogue record, publisher or pages acquired |
| `DULCE-CAND-018` | Bill Hamilton, *Cosmic Top Secret* | reported 1991 | `UNVERIFIED_CLAIM` | unknown | `UNKNOWN` | exact artifact and pages not acquired |
| `DULCE-CAND-019` | Penny Harper / *Whole Life Times* item | reported 1990 | `UNVERIFIED_CLAIM` | C reported; A→B unknown | `UNKNOWN_DEPRIORITIZED` | no title, issue, byline, page or scan found |

## Session 042 corrections

### Matrix II

The accessible scan is explicitly a third edition with added material and copyright 1990, 1991.

It contains multiple separate models:

```text
non-reptilian "very high" culture
        ↓ creates cloned Greys

Reptilian humanoids
        ↔ described by editor as enemies of Greys
```

It also contains reptilian elite language and extensive underground-base material. These ingredients are not a connected Draco→Grey chain.

```yaml
DULCE-CAND-009:
  A_entity: reptilian species / Draco elite
  B_grey_group: cloned Greys
  A_to_B_status: CONTRADICTED_OR_ABSENT
  C_system: PRESENT
  co_presence_only: true
  result: PARTIAL-AC_OPPOSITIONAL
```

Read:

- `data/error_fingerprints/ERR-036-002-ABC-CO-PRESENCE-LINKAGE-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-004-MATRIX-II-DRACO-WORKFORCE-CITATION-CONFLATION.md`

### Two TAL articles

```text
DULCE-CAND-010
The Deep Dark Secret at Dulce
Bill Hamilton + TAL LeVesque
UFO Universe, reported Feb–Mar 1991

DULCE-CAND-011
The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base
TAL LeVesque
Patrick O'Connell mailer/newsletter, date unknown
```

Do not combine title, byline, date or wording between them.

Read:

- `data/error_fingerprints/ERR-036-003-TAL-ARTICLE-CARRIER-COLLAPSE.md`

### O'Connell mailer language

The surviving Branton-hosted transcription quotes TAL as describing:

- a returning Reptilian race;
- Greys as mercenaries being used to interface with and manipulate humans;
- a Dulce / underground / genetic and secret-program setting.

The connected hierarchy is plausible in the quoted wording, but not securely promotable because:

- the original mailer is absent;
- the date is absent;
- the user of the Greys is partly grammatically implicit;
- Branton notes are interleaved;
- one model's `July 1990, Vol. 6 No. 2` claim lacks primary support.

### UFO Universe article

The accessible transcription establishes a joint biogenetic facility and mentions both Greys and reptilian humanoids. It does not establish that the reptilian group commands the Greys.

## Current chronology finding

```text
1984–1988:
C-bearing proto-Dulce sources
no secure linked reptilian→Grey hierarchy located

1989:
TAL The Dulce Base and Bill Hamilton Alien Magic reported
primary copies and linked wording not acquired

1990/1991:
Matrix II preserves reptilian/Grey opposition and separate higher-culture creation model
not the mature Draco-over-Grey hierarchy

unknown date, reported pre/parallel 1991:
O'Connell-carried TAL article contains strongest linked wording
but source object is unrecovered

Feb–Mar 1991:
UFO Universe article contains C plus reptilian presence
B remains unlocated

later early/mid-1990s:
Castello/Branton compilations circulate mature linked hierarchy
```

## Current decision

```yaml
earliest_reported_partial_c: DULCE-CAND-001
earliest_public_partial_c: DULCE-CAND-004
earliest_full_linked_chain: UNRESOLVED
highest_value_undated_linked_candidate: DULCE-CAND-011
highest_value_1989_artifact_lead: DULCE-CAND-017
matrix_ii: NOT_FULL_LINKED_CHAIN
ufo_universe_1991: NOT_FULL_ON_ACQUIRED_TEXT
canonical_edge: false
```
