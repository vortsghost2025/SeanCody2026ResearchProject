# NEG-032-001 — Reynolds 1836 Explicit Doctrinal Carryover

```yaml
NEGATIVE_RECORD:
  id: NEG-032-001
  claim_tested: >
    Jeremiah N. Reynolds's published 1836 institutional case for a Pacific,
    South-Seas, and South-Pole expedition explicitly cites or presents Symmes's
    Hollow Earth or polar-opening doctrine as a reason for the expedition.
  verdict: CONTRADICTED_BY_AVAILABLE_EVIDENCE
  confidence: MEDIUM_HIGH_FOR_EXPLICIT_1836_VOCABULARY

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
    - source: "John Quincy Adams diary entry, 1826-11-04"
      result: >
        Adams describes Reynolds as having lectured for Symmes's theory and then
        having varied his purpose toward a Southern Ocean circumnavigation proposal.
    - source: "Reynolds, Remarks on a review of Symmes' theory... (1827)"
      corpus: "Internet Archive LOC-derived scan and OCR, remarksonreviewo00reyn"
      result: >
        Reynolds declines to defend parts of the detailed Symmes system but retains
        the possibility that Earth may be hollow and widely open at the poles. He
        explicitly separates that speculative question from the independent rationale
        for a polar expedition.

  search_not_yet_conducted:
    - exhaustive synonym and concept search across the entire 1836 Address
    - exact page-image verification of every OCR absence
    - complete 1827-to-1836 phrase matrix
    - Reynolds's earlier lecture texts, newspaper reports, and private correspondence
    - full comparison with Voyage of the United States Frigate Potomac (1835)

  important_caveat: >
    This record rejects a narrow claim of explicit doctrinal presentation in the
    1836 Address. The acquired 1827 text shows partial doctrinal continuity and an
    already explicit effort to separate speculative Hollow Earth claims from the
    expedition program. The 1836 absence is therefore consistent with strategic and
    argumentative reframing. It does not prove that Symmes had no indirect,
    motivational, reputational, or historical effect on Reynolds.

  related_research_question: RQ-032
  related_bridge: BRIDGE-032-003
  added_session: SESSION_029
  updated_session: SESSION_031
  last_reviewed: 2026-07-13
```

## Source locators

- Reynolds 1836 item: `https://archive.org/details/addressonsubjec00reyngoog`
- Reynolds 1836 OCR: `https://archive.org/stream/addressonsubjec00reyngoog/addressonsubjec00reyngoog_djvu.txt`
- Reynolds 1827 item: `https://archive.org/details/remarksonreviewo00reyn`
- Reynolds 1827 OCR: `https://archive.org/stream/remarksonreviewo00reyn/remarksonreviewo00reyn_djvu.txt`
- 1827 artifact record: `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`
- Bridge finding: `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`

## Reuse rule

Future syntheses may say:

> Reynolds's 1827 pamphlet partially defends a hollow, open-pole Earth while separating that speculation from the independent case for exploration. His 1836 institutional *Address* does not explicitly invoke `Symmes` or `hollow` in the available OCR and instead uses commercial, scientific, navigational, and national rationales.

They may not convert that into:

> Symmes had no influence whatsoever on Reynolds.

or:

> Reynolds carried the complete Symmes system unchanged into the United States expedition program.

Both stronger claims exceed the evidence.
