# SESSION 030 — Reynolds 1827 *Remarks of Symmes' Theory* Verification Brief

**Target:** `BRIDGE-032-003`  
**Related question:** `RQ-032`  
**Mode:** one-artifact continuity test  
**Status:** OPEN — acquisition only

## Objective

Verify or falsify the repeatedly cited claim that Jeremiah N. Reynolds published a separate 1827 work titled approximately:

> *Remarks of Symmes' Theory Which Appeared in the American Quarterly Review*

This artifact is decisive because it may show that Reynolds continued publicly defending Symmes after the reported personal and practical break, complicating a simple `Hollow Earth abandoned → exploration adopted` chronology.

## Required first step

Do not begin with a general biography. Locate one exact bibliographic object.

Return:

```text
exact title from title page or catalogue
creator exactly as printed
publication date
city
printer / publisher
edition / issue / offprint status
page extent
institution / archive
catalogue ID / call number / shelfmark
stable item page
stable scan or image sequence
source from which it was reprinted, if applicable
```

## Identity and authenticity tests

1. Confirm that the creator is Jeremiah N. Reynolds, not another Reynolds.
2. Determine whether the object is:
   - an independently printed pamphlet;
   - an offprint;
   - a newspaper or journal article;
   - a later bibliographic ghost repeated without a surviving copy;
   - or a title variant of another work.
3. Locate the relevant *American Quarterly Review* article and identify:
   - volume;
   - issue;
   - date;
   - pages;
   - author, if known;
   - whether Reynolds is replying to, reprinting, or reviewing it.
4. Record every catalogue-title variation and do not merge them without evidence.

## Content tests

Transcribe the passages that establish Reynolds's position on:

- the Earth being hollow;
- polar openings;
- interior habitability;
- Symmes as an authority;
- an expedition as a test;
- Antarctic or Southern Ocean exploration;
- whether Reynolds accepts, modifies, doubts, or rejects the theory.

Provide page/image locators for every quotation.

## Chronology test

Place the artifact against:

```text
1823–1826 reported Reynolds/Symmes lecture collaboration and break
1826-11-04 John Quincy Adams "varied his purpose" diary description
1827 alleged Remarks pamphlet
1828 South-Pole lobbying and congressional records
1836 institutional Address
```

The key question is whether the 1827 artifact shows:

- continued belief after a personal break;
- strategic use of Symmes while shifting toward exploration;
- partial doubt or modification;
- a clean bibliographic misattribution;
- or no surviving artifact at all.

## Phrase-comparison test

Compare verified 1827 wording with the 1836 *Address* for:

- pole / poles;
- opening / openings;
- hollow;
- habitable / habitability;
- interior;
- warm and rich land;
- South Pole / Southern Ocean;
- expedition as proof;
- distinctive numerical claims;
- distinctive metaphors or mottos.

Do not infer continuity from broad words such as `exploration` or `pole` alone.

## Parallel primary-contact search

While locating the pamphlet, search only closely related archival contexts for one primary artifact naming both Reynolds and Symmes:

- lecture advertisement;
- newspaper report;
- ticket or handbill;
- correspondence;
- diary entry;
- publisher notice;
- public dispute report.

This is secondary to the pamphlet and must not expand into another general search.

## Disproof requirements

Actively test whether:

- no library catalogue contains the alleged object;
- all references descend from one later bibliography;
- the title is a mistaken paraphrase;
- Reynolds did not write it;
- the item predates or postdates the claimed break differently than summaries state;
- the text argues against Symmes rather than for him.

## Deliverable

Return:

1. one `SOURCE_RECORD` for the exact 1827 object, or a documented failed-source record;
2. title/author/edition conflict table;
3. exact quotations with page/image numbers;
4. comparison against the 1826 Adams entry and 1836 *Address*;
5. one recommendation:
   - `CONTINUITY_SUPPORTED`;
   - `PARTIAL_CONTINUITY`;
   - `DISCONTINUITY_SUPPORTED`;
   - `MISATTRIBUTED`;
   - `BIBLIOGRAPHIC_GHOST`;
   - `UNKNOWN`;
6. failed searches and inaccessible collections;
7. no canonical promotion.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `CROSS_DOMAIN_BRIDGE_ATLAS.md`, `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`, `reports/SESSION_029_REYNOLDS_CROSS_VARIANT_QC.md`, and `data/negative_evidence/NEG-032-001-REYNOLDS-1836-DOCTRINAL-CARRYOVER.md`. Execute `research_inbox/SESSION_030_REYNOLDS_1827_REMARKS_VERIFICATION_BRIEF.md`. Work only on the alleged 1827 Reynolds artifact titled approximately *Remarks of Symmes' Theory Which Appeared in the American Quarterly Review*. Locate one exact institutional record and scan, verify title and authorship, transcribe Reynolds's position with page/image locators, identify the underlying *American Quarterly Review* item, and compare distinctive language with the 1826 Adams entry and Reynolds's 1836 *Address*. Search for one closely related primary notice naming Reynolds and Symmes together, but do not broaden into a general biography. Return `UNKNOWN` or a documented bibliographic ghost if the object cannot be authenticated. Do not create canonical edges.
