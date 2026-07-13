# NEG-032-001 — Reynolds 1836 Explicit Doctrinal Carryover

```yaml
NEGATIVE_RECORD:
  id: NEG-032-001
  claim_tested: >
    Jeremiah N. Reynolds's published 1836 institutional case for a Pacific,
    South-Seas, and South-Pole expedition explicitly cites or presents Symmes's
    Hollow Earth or polar-opening doctrine as a reason for the expedition.
  verdict: CONTRADICTED_BY_AVAILABLE_EVIDENCE
  confidence: MEDIUM

  search_conducted:
    - source: "J. N. Reynolds, Address on the Subject of a Surveying and Exploring Expedition... (1836)"
      corpus: "Internet Archive OCR, addressonsubjec00reyngoog"
      query: "Symmes"
      result: "No match"
    - source: "J. N. Reynolds, Address... (1836)"
      corpus: "Internet Archive OCR, addressonsubjec00reyngoog"
      query: "hollow"
      result: "No match"
    - source: "Reynolds, Address... South-Pole section"
      result: >
        The visible argument invokes science, national honor, navigation,
        commerce, whaling, surveying, knowledge, and high-latitude achievement.
        No polar opening or habitable interior is presented in the inspected passage.
    - source: "John Quincy Adams diary entry, 1826-11-04, published in Memoirs vol. VII"
      result: >
        Adams describes Reynolds as having lectured for Symmes's theory and then
        having varied his purpose toward a Southern Ocean circumnavigation proposal.
    - source: "Library of Congress catalogue acquisition for Reynolds's 1827 Remarks pamphlet"
      result: >
        The 1827 pamphlet is authenticated bibliographically and explicitly responds
        to a review of Symmes's theory. Its text was not acquired, so its doctrinal
        position remains unknown.

  search_not_yet_conducted:
    - exhaustive synonym and concept search across the entire 1836 Address
    - exact page-image verification of every OCR absence
    - full-text acquisition and analysis of Reynolds's 1827 pamphlet
    - full-text acquisition of the 1827 American Quarterly Review counterpart article
    - Reynolds's earlier lecture texts, newspaper reports, and private correspondence
    - full comparison with Voyage of the United States Frigate Potomac (1835)

  important_caveat: >
    This record rejects a narrow claim of explicit doctrinal presentation in the
    1836 Address. The authenticated 1827 catalogue record proves continued public
    engagement with the Symmes controversy after Adams described a pivot, but it
    does not yet reveal Reynolds's position. The 1827 artifact therefore complicates
    a clean immediate-abandonment chronology without contradicting the 1836 text-level
    negative result. Absence of two keywords in OCR is meaningful but not exhaustive.

  related_research_question: RQ-032
  related_bridge: BRIDGE-032-003
  added_session: SESSION_029
  updated_session: SESSION_030
  last_reviewed: 2026-07-13
```

## Source locators

- Reynolds 1836 item: `https://archive.org/details/addressonsubjec00reyngoog`
- Reynolds 1836 OCR: `https://archive.org/stream/addressonsubjec00reyngoog/addressonsubjec00reyngoog_djvu.txt`
- Reynolds 1827 catalogue item: `https://www.loc.gov/item/06040937/`
- 1827 artifact record: `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`
- Bridge finding: `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`

## Reuse rule

Future syntheses may say:

> Reynolds's 1836 published institutional case does not explicitly invoke Symmes or a hollow Earth in the available OCR, and its visible rationale is commercial, scientific, navigational, and national. A separate 1827 Reynolds pamphlet responding to a review of Symmes's theory is authenticated at catalogue level, showing continued public engagement but not yet revealing his doctrinal position.

They may not convert that into:

> Symmes had no influence whatsoever on Reynolds.

or:

> The 1827 pamphlet proves Reynolds remained fully committed to Symmes's theory.

Both stronger claims exceed the acquired text.
