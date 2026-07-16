# SESSION 051 — Raw Avalon and Early-Hierarchy Object Audit

**Targets:** `DULCE-CAND-003`, `005`, `012`, `016`, `028`, `039`–`043`  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** reproducible web capture, exact early-object acquisition and artifact-family separation  
**Status:** OPEN — no first-carrier, authorship or stemma declaration

## Objective

Session 050 produced mutually exclusive claims about Project Avalon Thread 8393. Resolve the contradiction with preserved bytes, not search-result prose.

At the same time, harden the 1987–1990 progression while keeping the 1987 drawing packet separate from the later Castello Q&A.

## Default continuation

Do not stop to ask whether more data is wanted. Continue until each target is acquired, falsified, blocked with a documented access barrier or the tool/search budget is exhausted.

## Priority 1 — Complete Thread 8393 acquisition

Acquire every retrievable state:

```text
showthread page 1 through final page
printthread
archive/index
mobile/text view
Wayback wildcard captures
quoted-post copies in other threads
attachments and deleted-link records
```

For every raw file return:

```yaml
source_URL:
capture_timestamp:
HTTP_status:
byte_length:
SHA256:
page_number:
post_ID_range:
extraction_tool_and_version:
```

Commit or attach the exact raw files. Do not report a hash without the bytes.

## Priority 2 — Resolve the Q&A body and poster layer

Search the complete raw corpus for:

```text
The Draco is the undisputed master
The Draco are the undisputed masters
They work for, and are controlled by the Draco
Khaarshfashst
working caste
Leader Castello
ORIGINAL questions and answers
It is quite long - W
```

For every match return:

```yaml
raw_text:
post_ID:
poster_display_name:
poster_profile_URL:
timestamp:
edit_marker:
HTML_offset_or_selector:
preceding_500_characters:
following_500_characters:
```

Valid outcomes:

- `DIRECT_HINKLE_QA_POST_CONFIRMED`
- `W_RELAY_QA_CONFIRMED`
- `OTHER_POSTER_QA_CONFIRMED`
- `INTRODUCTORY_CLAIM_ONLY_TRANSCRIPT_MISSING`
- `DELETED_POST_OR_ATTACHMENT_LEAD`
- `THREAD_STATE_CHANGED_BETWEEN_CAPTURES`
- `UNKNOWN`

Do not infer W from a stray initial or from `SPIRIT WOLF` without exact post evidence.

## Priority 3 — Avalon/Branton raw corpus and diff

Acquire the exact Avalon Q&A only if found. Acquire separately:

- earliest available Branton Chapter 11 state;
- soft-1996 header state;
- claimed 1991 state;
- whale.to;
- Bibliotecapleyades;
- Auricmedia;
- Stillness in the Storm;
- Archive.org text/PDF.

Produce raw and normalized diffs. Track:

- `is/master` vs `are/masters`;
- signed Branton parenthetical;
- uppercase emphasis;
- bracket and quotation styles;
- `Q—` vs `A—` label on the control sentence;
- copied errors and paragraph order.

No direction-of-descent conclusion without raw chronology and reproducible output.

## Priority 4 — December 13, 1987 Lear letter

Acquire the complete PDF and preserve it locally.

Return:

```text
all pages
letterhead/address
exact date
recipient
full enclosure list
exact Dulce Papers description
exact Project Beta/McCampbell references
page images
PDF metadata
SHA-256
host and provenance
```

Determine whether any enclosure survives and whether any item contains the mature hierarchy.

Do not backdate the Q&A from a letter describing drawings.

## Priority 5 — 1987 Dulce Papers packet inventory

Inventory every item called `Dulce Papers` in 1987–1991 sources:

| Date | Carrier | Item type | Drawings | Photos | Transcript | Q&A | Hierarchy wording | Provenance |
|---|---|---|---|---|---|---|---|---|

Test when drawings, letters, interview answers and later Branton chapters first became bundled.

## Priority 6 — LeVesque/Bishop 1989 exact state

Acquire the earliest exact carrier of *The Dulce Base*.

Return:

- title/byline;
- carrier and issue;
- date basis;
- complete text;
- exact mercenary/DRACO and `in league` passages;
- differences across mirrors;
- evidence for or against 1989 dating.

Use later mirrors as text witnesses, not date proof.

## Priority 7 — `Pasturing and Use of Surface Earth Humans`

Acquire the complete earliest section, not a later Dulce Book excerpt.

Return:

- exact *Matrix II* edition;
- title/copyright pages;
- section page range;
- complete text;
- Draco caste and Grey mercenary wording;
- citations;
- relation to 1989 text and mature Q&A;
- 1990 versus 1991 edition differences.

## Priority 8 — Earliest Branton carrier

Test separately:

- alleged BBS file;
- alleged 1991 compilation;
- soft 1996 state;
- later mirrors.

Required:

```text
raw filename
BBS header
upload/post date
file metadata
copyright/title page
catalogue advertisement
collector provenance
complete Chapter 11 text
```

An internal sentence saying something was written in 1991 is not automatically the carrier date.

## Priority 9 — Tilton first edition

Acquire or inspect the reported object:

```text
Christa Tilton
The Bennewitz Papers
Crux Publications, Tulsa
1991
85 pages
Tom Benson collection / OCLC lead
```

Return the title page, copyright page, contents and exact Castello-fabrication passage. Compare with later 96-page Inner Light editions.

Do not transfer later wording into the 1991 state.

## Priority 10 — Nippon Television lead

Acquire the reported March 24, 1990 program featuring LeVesque:

- network and Japanese title;
- broadcast schedule;
- production credits;
- Hayakawa role;
- LeVesque transcript;
- recording or archive holding;
- distinction from Hinkle's claimed program.

## Priority 11 — Source-status discipline

Use:

- `CONFIRMED_PRIMARY`
- `RAW_WEB_CARRIER`
- `PRIMARY_DOCUMENT_REPORTED_AND_QUOTED_NOT_ARCHIVED`
- `TEXT_WITNESS_DATE_OPEN`
- `SECONDARY_ARCHIVAL_LEAD`
- `PARTICIPANT_SELF_ATTESTATION`
- `DERIVATIVE_MIRROR`
- `UNVERIFIED_CLAIM`
- `UNKNOWN`

## Stop rules

Do not:

- claim complete thread acquisition from snippets;
- report a hash without the bytes;
- treat the empty-string SHA-256 as a full-thread hash;
- treat the November 2010 thread as a confirmed Q&A carrier until the exact post is stored;
- call W, Mystery, Witchy or SPIRIT WOLF the relay without post-level proof;
- use the 1987 drawing packet to date the mature Q&A;
- use a later mirror to establish a 1989, 1990, 1991 or 1996 carrier date;
- use a mental-health allegation as historical evidence;
- count network proximity as packet receipt;
- stop to ask whether more data is wanted.

## Deliverables

1. Raw complete Thread 8393 corpus with hashes.
2. Exact Q&A/poster-layer verdict.
3. Raw Avalon/Branton/mirror diff and Q/A-label map.
4. Complete Lear 1987 letter record and enclosure inventory.
5. Dulce Papers vs. Q&A artifact-family chronology.
6. Exact 1989 text record.
7. Complete 1990 section record.
8. Earliest Branton carrier audit.
9. Tilton first-edition record.
10. Nippon program record.
11. Recommendation only; curator promotion required.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/AGENT_CONTINUATION_POLICY.md`, `docs/METHODOLOGY.md`, `reports/SESSION_050_AVALON_CONTRADICTION_AND_EARLY_ARTIFACT_QC.md`, `graph/artifact_families/DULCE_PAPERS_VS_CASTELLO_QA.md`, `graph/textual_stemma/CASTELLO_QA_AVALON_BRANTON_STEMMA.md`, and error fingerprints `ERR-036-029` through `ERR-036-032`. Execute `research_inbox/SESSION_051_RAW_AVALON_AND_EARLY_HIERARCHY_OBJECT_AUDIT.md`. Continue without asking permission. First acquire every page and archive state of Project Avalon Thread 8393 as raw files, store byte lengths and recomputed SHA-256 hashes, and map every hierarchy quotation to an exact post ID, poster and timestamp. Then preserve the complete December 13, 1987 Lear letter and distinguish its drawing/enclosure packet from the later interview Q&A. Acquire the earliest exact 1989 LeVesque/Bishop carrier, the complete earliest `Pasturing and Use...` section, and the earliest Branton Chapter 11 carrier. Do not promote snippets, unattached hashes, internal date claims or later mirrors into primary carrier evidence.
