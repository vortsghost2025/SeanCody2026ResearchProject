# BRIDGE-EDGE-002 — *American Quarterly Review* → Reynolds 1827 Response

```yaml
TRANSMISSION_EDGE_CANDIDATE:
  id: BRIDGE-EDGE-002
  status: PARTIAL
  canonical: false

  from:
    type: PERIODICAL_ARTICLE
    label: "Symmes's theory"
    publication: "The American Quarterly Review"
    volume: 1
    year: 1827
    start_page: 235
    author: UNKNOWN_OR_ANONYMOUS
    verification: PARTIAL_FROM_ACQUISITION

  to:
    type: PAMPHLET
    label: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    creator: "J. N. Reynolds"
    year: 1827
    place: Washington
    printer: "Gales & Seaton"
    loc_item: "06040937"
    verification: CATALOGUE_AUTHENTICATED_FROM_ACQUISITION

  proposed_edge_type:
    - DIRECT_RESPONSE
    - DIRECT_CITATION

  evidence_class: B
  confidence: MEDIUM

  missing_for_promotion:
    - exact institutional scan of the AQR article
    - full issue/date and page range
    - scan or transcription of Reynolds's pamphlet
    - direct textual evidence tying the pamphlet to that exact article
    - comparison showing whether Reynolds defends, modifies, or rejects the reviewed theory

  generated_session: SESSION_030
  last_reviewed: 2026-07-13
```

## Current support

The LOC-catalogued title of Reynolds's pamphlet explicitly names a review of Symmes's theory in *The American Quarterly Review*. The acquisition identifies a matching article in volume 1 beginning at page 235.

This is sufficient to preserve a response-edge candidate. It is not yet sufficient for a canonical transmission edge because neither side's page images were inspected during curator review.

## Promotion rule

Promote only after the source article and pamphlet are both acquired and matched at item level. The exact response mechanism must then be classified as one or more of:

- rebuttal;
- defense;
- qualification;
- correction;
- adaptation;
- strategic reframing;
- or rejection.
