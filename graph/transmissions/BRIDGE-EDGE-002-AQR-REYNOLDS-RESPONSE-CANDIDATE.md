# BRIDGE-EDGE-002 — *American Quarterly Review* → Reynolds 1827 Response

```yaml
TRANSMISSION_EDGE:
  id: BRIDGE-EDGE-002
  status: VERIFIED_DIRECT_RESPONSE
  canonical: true

  from:
    type: PERIODICAL_ARTICLE
    label: "Symmes's theory"
    publication: "The American Quarterly Review"
    volume: 1
    issue: 1
    issue_date: 1827-03
    pages: 235-253
    author: UNKNOWN_OR_ANONYMOUS
    verification: ITEM_LEVEL_METADATA_AND_ACQUISITION

  to:
    type: PAMPHLET_AND_REPRINTED_RESPONSE_SERIES
    label: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    creator_catalogue: "J. N. Reynolds"
    printed_attribution: "A Citizen of the United States"
    year: 1827
    place: Washington
    printer: "Gales & Seaton"
    ia_identifier: remarksonreviewo00reyn
    ark: ark:/13960/t1tf1gd11
    lccn: "06040937"
    verification: TEXT_AND_SCAN_ACQUIRED

  edge_type:
    - DIRECT_RESPONSE
    - DIRECT_CITATION
    - ARGUMENTATIVE_QUALIFICATION
    - STRATEGIC_REFRAMING

  evidence_class: A_FOR_RESPONSE_RELATION
  content_alignment_class: B_PARTIAL
  confidence: HIGH

  scope: >
    Reynolds's title and prefatory note explicitly identify the pamphlet as a reply to
    a review of Captain Symmes's theory in The American Quarterly. The response addresses
    the review's physical, polar-navigation, and expedition arguments. Reynolds rejects
    or brackets parts of the detailed Symmes model, retains a narrower hollow/open-pole
    possibility as rational speculation, and separates the expedition case from the
    speculative doctrine.

  exclusions:
    - Complete paragraph-by-paragraph AQR alignment is not finished.
    - The edge does not establish that Reynolds accepted every Symmes claim.
    - The edge does not establish that Symmes doctrine caused the 1836 expedition program.
    - It does not establish a later Hollow-Earth or Antarctic-base lineage.

  generated_session: SESSION_030
  promoted_session: SESSION_031
  last_reviewed: 2026-07-13
```

## Source article

```yaml
title: "Symmes's theory"
publication: "The American Quarterly Review"
volume: 1
issue: 1
issue_date: March 1827
pages: 235-253
publisher: "Carey, Lea & Carey"
place: Philadelphia
creator: anonymous_or_unresolved
archive_lead: "HathiTrust nyp.33433081754644"
```

The raw acquisition provides the page range, scan locator, and major article claims. Complete curator page-image inspection remains open.

## Receiving publication

```yaml
title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
creator_catalogue: "Jeremiah N. Reynolds"
printed_attribution: "A Citizen of the United States"
publication_year: 1827
place: Washington
printer: "Gales & Seaton"
ia_identifier: remarksonreviewo00reyn
ark: ark:/13960/t1tf1gd11
lccn: "06040937"
item_url: "https://archive.org/details/remarksonreviewo00reyn"
ocr_url: "https://archive.org/stream/remarksonreviewo00reyn/remarksonreviewo00reyn_djvu.txt"
pdf_url: "https://archive.org/download/remarksonreviewo00reyn/remarksonreviewo00reyn.pdf"
```

The preface says the pieces were written in reply to the AQR review and first published in the *National Intelligencer*.

## Response mechanism

| Reviewed issue | Reynolds response | Classification |
|---|---|---|
| Symmes theory is recycled or visionary speculation | Treats inquiry as rational but concedes uncertainty | `QUALIFICATION` |
| Detailed concentric-sphere structure | Declines to defend several detailed claims | `CONCESSION / PARTIAL_REJECTION` |
| Earth cannot be hollow under accepted physics | Offers alternative physical reasoning and retains possibility | `COUNTERARGUMENT / PARTIAL_DEFENSE` |
| Polar seas are blocked by perpetual ice | Compiles navigation evidence for possible open polar water | `COUNTEREVIDENCE` |
| Expedition is tainted by speculative theory | Separates expedition from doctrine and argues independent value | `STRATEGIC_REFRAMING` |

## Exact boundary

Verified:

```text
AQR review → Reynolds response: DIRECT_RESPONSE
Reynolds response → partial defense plus qualification: SUPPORTED
Reynolds response → separation of theory and expedition: SUPPORTED
```

Still incomplete:

```text
every AQR paragraph → exact Reynolds page: PARTIAL
National Intelligencer serialization dates/pages: OPEN
shared citizen byline mechanism: OPEN
```

## Related records

- `reports/SESSION_031_REYNOLDS_AQR_QC.md`
- `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`
- `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`
- `data/error_fingerprints/ERR-032-002-CITIZEN-OF-US-BYLINE.md`
