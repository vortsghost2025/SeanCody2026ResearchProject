# BRIDGE-032-003 — Jeremiah N. Reynolds Pivot

```yaml
BRIDGE_CANDIDATE:
  id: BRIDGE-032-003
  title: "Jeremiah N. Reynolds: Symmes advocate → Antarctic and South-Seas expedition lobbyist"
  status: SUPPORTED_SPLIT_WITH_1827_BIBLIOGRAPHIC_CONTINUITY
  related_question: RQ-032

  endpoints:
    - object_type: CONCEPT_AND_PUBLIC_ADVOCACY
      object_id: SYMMES-HOLLOW-EARTH-LECTURE-PERIOD
      role: SOURCE_SIDE
    - object_type: INSTITUTIONAL_EXPLORATION_PROGRAM
      object_id: REYNOLDS-SOUTHERN-OCEAN-ADVOCACY
      role: DESTINATION_SIDE

  supported_mechanisms:
    - SAME_PERSON_CARRIER
    - EXPOSURE_PATH
    - INSTITUTIONAL_CARRIER
    - RHETORICAL_REFRAMING
    - BIBLIOGRAPHIC_CONTINUITY_IN_1827

  not_established:
    - PERSONAL_CONTACT_WITH_SYMMES_FROM_PRIMARY_ARTIFACT
    - DOCUMENTED_CAUSAL_INFLUENCE_OF_HOLLOW_EARTH_DOCTRINE
    - CONTINUOUS_LEXICAL_MIGRATION_INTO_1836_ADDRESS
    - DOCTRINAL_POSITION_INSIDE_1827_PAMPHLET
    - COMPLETE_REPUDIATION_OF_ALL_EARLIER_IDEAS

  current_assessment:
    evidence_class: B
    confidence: MEDIUM_HIGH
    curator_note: >
      Primary and near-primary records document Reynolds moving from public support
      of Symmes's theory into formal Southern Ocean and South-Pole advocacy. A Library
      of Congress catalogue record authenticates an 1827 Reynolds pamphlet responding
      to a review of Symmes's theory, proving continued public engagement after Adams's
      1826 description of a pivot. The pamphlet text has not been acquired, so continued
      doctrinal loyalty remains unknown. Reynolds's mature 1836 public case uses
      commercial, scientific, navigational, and national rationales and contains no
      explicit Symmes/hollow terminology in the available OCR.

  generated_session: SESSION_029
  updated_session: SESSION_030
  last_reviewed: 2026-07-13
```

## Supported chronology

### November 4, 1826 — transition described by John Quincy Adams

The published Adams diary describes Reynolds as a man who had lectured in support of Captain John Cleves Symmes's theory and says that, after ridicule of the theory, Reynolds had `varied his purpose` toward a voyage of circumnavigation to the Southern Ocean.

```yaml
source:
  creator: John Quincy Adams
  publication: "Memoirs of John Quincy Adams, comprising portions of his diary from 1795 to 1848"
  volume: VII
  diary_entry_date: 1826-11-04
  published_volume_date: 1875
  publisher: J. B. Lippincott & Co.
  ia_identifier: memoirsofjohnqui07adam
  ark: ark:/13960/t5j963k68
  source_status: PRIMARY_DIARY_IN_PUBLISHED_EDITION
```

**Supported:** one identifiable person occupied both roles, and a contemporary observer described a pivot.

**Not supported:** that Symmes's doctrine materially caused the later exploration program.

### 1827 — catalogue-authenticated response concerning Symmes's theory

```yaml
source:
  creator: "Reynolds, J. N. (Jeremiah N.), 1799-1858"
  title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
  place: Washington
  printer: "Gales & Seaton"
  year: 1827
  institution: "Library of Congress"
  loc_item: "06040937"
  catalogue_url: "https://www.loc.gov/item/06040937/"
  call_numbers:
    - "AC901 .M5 vol. 797, no. 14"
    - "YA 25425"
  verification: CATALOGUE_AUTHENTICATED_FROM_ACQUISITION
  text_access: NOT_ACQUIRED
```

This artifact postdates both the reported 1825 personal break and Adams's November 1826 transition description.

**Supported:** Reynolds remained publicly engaged with the printed Symmes controversy in 1827.

**Not supported without text:** that Reynolds defended, endorsed, modified, or rejected the theory.

Read: `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`.

### February 22, 1828 — South-Pole identity

Adams later described Reynolds as `the projector of an expedition to the South Pole`. This confirms that Reynolds had become publicly legible in Washington as an expedition advocate rather than only a Hollow Earth lecturer.

### November–December 1834 — state and congressional circulation

A December 16, 1834 congressional printing of the East India Marine Society memorial reproduces the Rhode Island legislature's reference to:

> `the memorial of J. N. Reynolds and others, dated November, 1834`

and recommends the proposed South-Seas voyage to Congress.

```yaml
source:
  issuing_body: "23d Congress, 2d Session"
  title: "Memorial of the East India Marine Society of Salem, Mass."
  document_date: 1834-12-16
  archive: GovInfo
  stable_pdf: "https://www.govinfo.gov/content/pkg/SERIALSET-00268_00_00-038-0075-0000/pdf/SERIALSET-00268_00_00-038-0075-0000.pdf"
```

This supports institutional circulation of an exploration proposal, not institutional endorsement of Hollow Earth theory.

### 1836 — mature public advocacy dossier

```yaml
source:
  creator: J. N. Reynolds
  title: "Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas"
  delivery_date: 1836-04-03
  publication_year: 1836
  preface_date: 1836-10-10
  publisher: Harper & Brothers
  ia_identifier: addressonsubjec00reyngoog
  ark: ark:/13960/t6b282459
  lccn: "04033154"
  stable_item: "https://archive.org/details/addressonsubjec00reyngoog"
  stable_ocr: "https://archive.org/stream/addressonsubjec00reyngoog/addressonsubjec00reyngoog_djvu.txt"
```

The South-Pole section begins:

> `What ! extend our researches to regions surrounding the South Pole ! And wherefore not ?`

The surrounding rationale concerns science, national honor, navigation, commerce, whaling, surveying, and knowledge.

## Transformation record

| Element | Result |
|---|---|
| Polar extremities as meaningful frontier | RETAINED |
| Expedition as a way to test or acquire knowledge | RETAINED |
| Public engagement with Symmes controversy in 1827 | SUPPORTED AT BIBLIOGRAPHIC LEVEL |
| Reynolds's exact 1827 doctrinal position | UNKNOWN — TEXT NOT ACQUIRED |
| Commercial protection and fisheries | ADDED / EMPHASIZED BY 1836 |
| Navigation, charts, hydrography, natural history | ADDED / EMPHASIZED BY 1836 |
| National prestige and state sponsorship | ADDED / EMPHASIZED BY 1836 |
| Explicit hollow and habitable Earth in 1836 | NOT LOCATED |
| `Symmes` as source or authority in 1836 | NOT LOCATED |
| Polar opening as destination in 1836 | NOT LOCATED |
| Mature public rationale | REFRAMED AS INSTITUTIONAL EXPLORATION |

## Negative evidence boundary

A reproducible OCR search of the 1836 *Address* returned:

```text
Symmes: no match
hollow: no match
```

This supports a narrow conclusion about the 1836 publication. It does not establish:

- that the 1827 pamphlet rejected Symmes;
- that no synonyms or indirect remnants survive;
- that earlier correspondence used no Hollow Earth language;
- or that Reynolds's reframing was immediate, total, or purely intellectual rather than strategic.

See `data/negative_evidence/NEG-032-001-REYNOLDS-1836-DOCTRINAL-CARRYOVER.md`.

## Title-error fingerprint

The LOC catalogue title differs materially from the widely repeated shortened title. This is tracked as `ERR-032-001`, an open copied-error candidate, not yet a proven website-to-website copying chain.

## Unresolved high-value evidence

1. A scan or transcription of Reynolds's 1827 pamphlet.
2. The exact 1827 *American Quarterly Review* article and complete page range.
3. A primary lecture notice, pamphlet, newspaper report, or letter naming Reynolds and Symmes together.
4. Reynolds correspondence explaining the break or transition in his own words.
5. A broader phrase comparison across the 1827 pamphlet, 1836 *Address*, 1835 *Voyage of the Potomac*, and lecture-era material.
6. Evidence distinguishing intellectual abandonment from strategic rhetorical suppression.

## Curator decision

```text
Same-person bridge: supported
Exposure path: supported
Institutional carrier: supported
Rhetorical reframing: supported
1827 bibliographic continuity: supported
1827 doctrinal continuity: unknown
Personal contact: not yet promoted
Doctrinal transmission into mature program: not established
Complete abandonment: not established
Candidate status: SUPPORTED_SPLIT_WITH_1827_BIBLIOGRAPHIC_CONTINUITY
```
