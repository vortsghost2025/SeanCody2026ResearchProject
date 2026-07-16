# SESSION 056 — Matrix II Physical Diff and COSCON Provenance Brief

**Targets:** `DULCE-CAND-009`, `012`, `013`, `015`, `041`, COSCON34  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** edition-level physical acquisition, BBS provenance and title-identity audit  
**Status:** OPEN — no first-carrier, work-identity or chronology declaration

## Objective

Session 055 closed COSCON34 as an unedited pre-Branton ancestor and established the first useful item metadata for the 1990 first edition of *Matrix II*. The next acquisition must determine:

1. whether `Pasturing and Use of Surface Earth Humans` appears in the 458-page first edition;
2. when and where COSCON34 first circulated;
3. whether *The Dulce Book* and *The Dulce Wars* are the same work, retitled editions, or distinct compilations.

## Default continuation

Continue without asking permission until every in-scope target is acquired, falsified, blocked with a documented access barrier or the search/tool budget is exhausted.

## Priority 1 — Matrix II 1990 first edition

Acquire or inspect a numbered 458-page first edition described as:

```text
Valdamar Valerian
Matrix II
Las Vegas: Arcturus Book Service
1990
first edition
limited to 500 numbered copies
```

Return:

- front cover;
- spine and back cover;
- title page;
- copyright page;
- edition statement;
- colophon and copy number;
- complete contents;
- index;
- pages containing `Pasturing`, `Draco`, `Greys`, `Dulce`, `Bishop` and `LeVesque`;
- page count confirmation;
- provenance and holder;
- unprocessed page images.

Allowed outcomes:

- `PASTURING_PRESENT_IN_1990_FIRST`
- `PASTURING_ABSENT_FROM_1990_FIRST`
- `PASTURING_PRESENT_DIFFERENT_WORDING`
- `FIRST_EDITION_NOT_INSPECTED`

## Priority 2 — First-to-third edition diff

Compare the 458-page first edition with the inspected 1991 third edition.

Produce:

| Section | 1990 first pages | 1991 third pages | Added | Deleted | Revised | Hierarchy effect |
|---|---:|---:|---|---|---|---|

Prioritize:

- `Pasturing and Use of Surface Earth Humans`;
- Grey/Reptoid alliance and opposition passages;
- Draco leader-elite wording;
- Dulce base and genetic-program passages;
- contents/index changes;
- source acknowledgements.

Do not transfer third-edition wording into the first edition.

## Priority 3 — Dealer and collector provenance

For the reported numbered copy #152, return:

- dealer name;
- listing URL or archived catalogue;
- listing date;
- photographs;
- condition description;
- source of bibliographic claims;
- seller contact/archive;
- current disposition if known.

Treat dealer prose as item metadata unless the pages themselves are acquired.

## Priority 4 — COSCON34 original provenance

Search BBS and text-file archives for:

```text
COSCON34.TXT
COSCON34
COSCON 34
A Dulce Base Security Officer Speaks Out
Thomas Edwin Castello approximately a year before his death
```

Target:

- textfiles.com;
- cdrom and Walnut Creek archive indices;
- Internet Archive software/text collections;
- Simtel mirrors;
- old FTP file lists;
- BBS lists and conference catalogues;
- Usenet archives;
- FidoNet/QWK packet archives;
- private UFO text collections.

Return:

```yaml
filename:
byte_length:
file_timestamp:
archive_path:
archive_date:
BBS_or_collection:
conference_or_directory:
uploader_or_sysop:
header:
footer:
sequence_context:
neighboring_files:
```

The filename alone is not a date.

## Priority 5 — COSCON34 text-state diff

Compare COSCON34 with:

- whale.to;
- Bibliotecapleyades;
- earliest surviving Branton Chapter 11 state;
- October 1996 compilation state;
- *The Dulce Wars* states.

Track:

- Branton parentheticals;
- Q/A labels;
- chapter heading;
- answer order;
- spelling and punctuation;
- omissions/additions;
- control sentence label;
- copied errors;
- file headers and footers.

Possible results:

- `COSCON34_EXPORT_OF_DULCE_BOOK`
- `COSCON34_SHARED_BRANTON_WORKING_FILE`
- `COSCON34_LATER_DERIVATIVE`
- `COSCON34_MIXED_STATE`
- `UNKNOWN`

## Priority 6 — Dulce Book / Dulce Wars item identity

Acquire at least one complete dated state of each title.

Return:

- exact title page;
- subtitle;
- attributed author;
- copyright page;
- publisher;
- date;
- ISBN/catalogue record;
- page count;
- contents;
- introduction/sign-off;
- Chapter 11 equivalent;
- cover and file metadata.

Test:

```text
H1 one work under two titles
H2 Dulce Wars retitles Dulce Book
H3 expansion/abridgement relation
H4 two compilations sharing chapters
```

Do not count the titles as independent sources until identity is resolved.

## Priority 7 — October 1996 self-date

Acquire the complete carrier containing `Branton -- October, 1996` and preserve:

- exact heading;
- preceding and following text;
- title associated with the sign-off;
- file/page location;
- carrier provenance;
- whether it appears in both title traditions;
- whether it is present in COSCON34.

Use `COMPILATION_SELF_DATE` unless a physical publication record is also acquired.

## Priority 8 — Remaining first-carrier question

Continue to search for an earlier mature Q&A carrier independent of Branton editorial content:

- standalone interview transcript;
- dated BBS file without Branton notes;
- newsletter printing;
- manuscript;
- correspondence attachment;
- conference handout.

A Branton-edited carrier can date distribution after editorial intervention but cannot establish the unedited source composition date.

## Stop rules

Do not:

- call COSCON34 pre-Branton because of its filename;
- infer a BBS upload date from current web hosting;
- assign `Pasturing and Use` to 1990 without first-edition pages;
- treat dealer metadata as project physical inspection;
- count *The Dulce Book* and *The Dulce Wars* as independent witnesses;
- convert an internal source date into compilation date;
- stop to ask whether more data is wanted.

## Deliverables

1. Matrix II 1990 first-edition object record.
2. First-to-third edition page-level diff.
3. Dealer/collector provenance record.
4. COSCON34 BBS provenance record.
5. COSCON34 text-state diff.
6. Dulce Book / Dulce Wars identity matrix.
7. October 1996 self-date record.
8. First-carrier recommendation only; curator promotion required.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/AGENT_CONTINUATION_POLICY.md`, `docs/METHODOLOGY.md`, `reports/SESSION_055_COSCON34_MATRIXII_TITLE_QC.md`, `graph/chronologies/MATRIX_II_EDITION_MATRIX.md`, `graph/textual_stemma/COSCON34_BRANTON_CARRIER.md`, `graph/artifact_families/DULCE_BOOK_VS_DULCE_WARS.md`, and error fingerprints `ERR-036-033` through `ERR-036-036`. Execute `research_inbox/SESSION_056_MATRIXII_PHYSICAL_DIFF_AND_COSCON_PROVENANCE_BRIEF.md`. Continue without asking permission. First inspect the numbered 458-page 1990 first edition of Matrix II and determine whether Pasturing and Use appears there. Then recover original COSCON34 BBS metadata and compare it against Branton carriers. Finally resolve The Dulce Book versus The Dulce Wars at item level. Do not backdate later-edition text, date a file from its name, or count title variants as independent sources.
