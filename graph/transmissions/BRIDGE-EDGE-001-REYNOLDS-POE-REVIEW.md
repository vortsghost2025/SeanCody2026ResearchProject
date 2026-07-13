# BRIDGE-EDGE-001 — Reynolds 1836 *Address* → Poe 1837 Review

```yaml
TRANSMISSION_EDGE:
  id: BRIDGE-EDGE-001
  from:
    type: PUBLICATION
    label: "J. N. Reynolds, Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas"
    date: 1836
  to:
    type: PUBLICATION
    label: "Edgar Allan Poe, South-Sea Expedition"
    date: 1837-01

  edge_type: DIRECT_CITATION
  evidence_class: A
  confidence: HIGH

  mechanism:
    - NAMED_REVIEW
    - QUOTATION_AND_SUMMARY
    - PERIODICAL_AMPLIFICATION

  scope: >
    Poe's January 1837 review explicitly names Reynolds, reproduces the complete
    bibliographic heading of the 1836 Address, summarizes its institutional case,
    quotes or excerpts from the volume, and directs readers to examine it.

  exclusions:
    - This edge does not yet establish exact copied passages from Reynolds into Pym.
    - It does not establish Poe as a source for later Hollow Earth or Antarctic-base claims.
    - It does not prove Reynolds carried Symmes's Hollow Earth doctrine into the Address.

  generated_session: SESSION_029
  last_reviewed: 2026-07-13
```

## Source publication

```yaml
creator: J. N. Reynolds
title: "Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas"
delivery_date: 1836-04-03
publication_year: 1836
publisher: Harper & Brothers
ia_identifier: addressonsubjec00reyngoog
ark: ark:/13960/t6b282459
lccn: "04033154"
stable_item: "https://archive.org/details/addressonsubjec00reyngoog"
```

## Receiving publication

```yaml
creator: Edgar Allan Poe
title: "South-Sea Expedition"
publication: Southern Literary Messenger
volume: III
issue: 1
date: 1837-01
pages: 68-72
stable_transcript: "https://www.eapoe.org/works/criticsm/slm37r01.htm"
```

The review opens by identifying the book:

> `Address on the subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas. Delivered in the Hall of Representatives on the Evening of April 3, 1836. By J. N. Reynolds. With Correspondence and Documents. New York: Published by Harper and Brothers.`

Poe then tells readers that Reynolds has embodied a full account of the project in the reviewed volume and summarizes the expedition's commercial, navigational, scientific, legislative, and institutional history.

## Issue-level context

The January 1837 *Southern Literary Messenger*, vol. 3, no. 1, also contains `Arthur Gordon Pym, No. I`.

```yaml
issue_index: "https://literati.github.io/apc-jekyll/issues/slm/3/1/"
relationship_to_edge: ISSUE_LEVEL_EXPOSURE_PATH
```

This proximity is recorded as editorial context only. It is not proof that the first installment copied Reynolds.

## Open downstream test

A separate `KNOWN_COPY` edge may be created only after exact alignment of:

- Reynolds page/image number;
- Poe review or *Pym* chapter/page;
- exact overlapping wording;
- reliable scholarly discussion of the reuse;
- whether the overlap concerns Antarctic exploration specifically.

Current result:

```text
Reynolds Address → Poe review: DIRECT_CITATION — VERIFIED
Reynolds Address → Pym: KNOWN_COPY — NOT YET VERIFIED
Poe → later Antarctic/Hollow-Earth narratives: UNKNOWN
```
