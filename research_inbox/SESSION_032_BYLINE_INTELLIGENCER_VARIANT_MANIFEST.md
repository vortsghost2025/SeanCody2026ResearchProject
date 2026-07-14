# SESSION 032 — Byline / *National Intelligencer* Variant Manifest

> **Mode:** cross-variant acquisition preservation  
> **Related:** `ERR-032-002`, `BRIDGE-032-003`, `BRIDGE-EDGE-003`, `RQ-032`  
> **Curator status:** variants preserved; continuation closed at archive-access boundary

## Variant A — Google Doc tab `t.ysg11pvim3rq`

**Strengths**

- Provides exact Internet Archive identifiers for McBride 1826 and Reynolds 1827.
- Reports primary title-page forms for both `Citizen of the United States` attributions.
- Confirms from Reynolds's preface that three response numbers first appeared in the *National Intelligencer*.
- Distinguishes McBride's Cincinnati printer from Reynolds's Washington printer.
- Preserves failed searches for exact newspaper dates/pages/columns.

**Weaknesses / overreach**

- Calls deliberate echo and shared-circle signaling `strongly supported` despite incomplete frequency controls and no direct statement of authorial intent.
- Describes the byline reuse as `highly non-random` without a completed bounded comparison set.
- Mentions earlier Gales & Seaton / Symmes links and official-printing roles without item-level source records inside the result.
- Recommends promotion before exact newspaper issues are located.

## Variant B — Google Doc tab `t.xh9nfq60pca7`

**Strengths**

- Separates primary-confirmed facts from inference.
- Gives title-page scan location as PDF page 6 for both items.
- Treats the byline as low-distinctiveness after finding unrelated uses.
- Correctly distinguishes the Reynolds newspaper carrier from a McBride-to-Reynolds copying claim.
- Keeps exact *National Intelligencer* dates/pages/columns open.

**Weaknesses / remaining gaps**

- The bounded phrase control supplies only a few examples, not the requested five-to-fifteen item table.
- The unrelated comparison titles need exact dates, editions, institutions, and title-page images.
- It does not recover the three serialized newspaper issues.

## Continuation report

A follow-up targeted pass reconfirmed the primary pamphlet statement and repeated the issue-level failure.

Searches included:

- exact and distinctive phrases from the Reynolds pamphlet;
- `To the Editor of the American Quarterly Review`;
- Reynolds/Symmes/*National Intelligencer* combinations;
- Virginia newspaper reprint leads;
- McBride scrapbook references;
- Symmes bibliographies;
- free LOC, HathiTrust, Google Books, and commercial-archive snippets.

### Closest leads

- *Genius of Liberty*, November 10, 1827, reportedly reprinting material from the *National Intelligencer* of approximately October 31, 1827;
- McBride scrapbook clippings containing Symmes/Reynolds/*Intelligencer* material but unusable OCR;
- bibliographic references to other Symmes pieces in the *Intelligencer* during 1827.

None identifies the three Reynolds installments by date, page, column, heading, or byline.

### Continuation boundary

```yaml
exact_installments: NOT_ACQUIRED
free_source_search: EXHAUSTED_FOR_CURRENT_PASS
next_access:
  - PAID_NEWSPAPER_ARCHIVE
  - LOC_MICROFILM_OR_ISSUE_ACCESS
  - INSTITUTIONAL_RESEARCH_REQUEST
  - EXACT_REPRINT_LEAD
```

Read: `research_inbox/SESSION_032_CONTINUATION_CLOSEOUT.md`.

## Separate attached input — observability / Wilkes leads

Uploaded file:

```yaml
filename: "Pasted text(5).txt"
sha256: "041a6a6333e14c08733edc4f54ae18af9fb50de61e1e4ae02c1061020ee3c1f7"
size_bytes: 17792
```

This is **not** a Session 032 byline variant. It is a broad lead package concerning:

- sea-ice drift and high-latitude navigation error;
- nineteenth-century observational and sounding limits;
- what Reynolds-era expeditions could and could not test;
- Wilkes Expedition land-sighting verification;
- comparison of Symmes claims with nineteenth-century expedition logs.

It is preserved separately under Session 033 and does not alter the Session 032 byline verdict.

## Entity-resolution correction

The attached observability lead package risked merging:

```text
Jeremiah N. Reynolds — advocate / writer / lobbyist
William Reynolds — Wilkes Expedition naval officer
```

The namesake guardrail is preserved as `ENTITY-RESOLUTION-001`.

## Final curator baseline

```text
Primary title-page match: verified
Awareness of reviewed work: supported
Awareness of attribution phrase: supported from Reynolds text
Awareness of exact McBride title-page source: plausible, not proven
Reynolds prior National Intelligencer publication: verified
Exact newspaper issue records: not acquired
Byline copying: not established
Deliberate rhetorical echo: plausible, not proven
Generic anonymity convention: viable
Shared Reynolds publishing carrier: verified
Session 032 free-source lane: closed
Next active lane: RQ-033
```
