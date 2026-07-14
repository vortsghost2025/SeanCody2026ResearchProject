# SESSION 031 — Reynolds / AQR Text-Pair Curator QC

> ## TOP-LEVEL STATUS
>
> ```text
> Session 031 raw variants: 1 multi-agent package
> Reynolds pamphlet scan: ACQUIRED
> Reynolds pamphlet OCR: AVAILABLE
> AQR counterpart metadata/page range: SUPPORTED FROM ACQUISITION
> AQR page-image inspection by curator: INCOMPLETE
> Direct review-response relation: VERIFIED
> Reynolds 1827 doctrinal position: PARTIAL CONTINUITY + STRATEGIC REFRAMING
> 1836 explicit-doctrine negative record: RETAINED
> Shared-byline fingerprint: OPEN CANDIDATE
> RQ-032 status: SEARCHING
> ```

## 1. Source-access correction

Session 030 recorded the Reynolds pamphlet text as unacquired. That boundary is now obsolete.

The Internet Archive item `remarksonreviewo00reyn` provides:

```yaml
title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
creator: "[Reynolds, Jeremiah N.], 1799-1858"
publication_year: 1827
publisher: "Washington, Printed by Gales & Seaton"
ia_identifier: remarksonreviewo00reyn
ark: ark:/13960/t1tf1gd11
lccn: "06040937"
physical_description: "75 p. ; 20 x 11 cm"
source_collection: "Library of Congress"
```

The item exposes full-text OCR and PDF downloads. OCR quality is imperfect, but the access barrier is resolved for the pamphlet.

## 2. Title-page and publication infrastructure

The OCR title page reads, allowing for OCR defects:

```text
REMARKS ON A REVIEW OF SYMMES' THEORY
WHICH APPEARED IN THE
AMERICAN QUARTERLY REVIEW,
A CITIZEN OF THE UNITED STATES.
WASHINGTON:
PRINTED BY GALES & SEATON.
1827.
```

The prefatory note says the three numbers were:

- written in reply to a review of Captain Symmes's theory in the *American Quarterly*;
- first published in the *National Intelligencer*;
- divided into physical theory, polar-sea evidence, and expedition rationale.

This identifies a carrier system beyond the individual author:

```text
American Quarterly Review criticism
        ↓
National Intelligencer serialized response
        ↓
Gales & Seaton pamphlet reprint
        ↓
institutional and public circulation
```

The exact *National Intelligencer* dates remain unverified.

## 3. What Reynolds actually argued

The pamphlet does not support either extreme of total loyalty or total abandonment.

### A. Detailed claims explicitly not defended

Reynolds says he will not defend:

- five concentric spheres;
- the `mid plain space` structure;
- every associated cosmological detail;
- the idea that speculation alone justifies an expedition.

### B. Narrower doctrine retained

He nevertheless maintains that Earth may be:

- a hollow sphere;
- widely open at the poles;
- compatible with known measurements and Newtonian principles;
- worth treating as rational inquiry rather than impossible ridicule.

### C. Expedition separated from doctrine

The preface says the theory was not sufficiently clear to justify an expedition predicated upon it. The later numbers instead argue that polar inquiry has independent scientific value and that expedition advocacy rests on broader principles.

This produces the supported interpretation:

```text
specific Symmes machinery: partly rejected or bracketed
hollow/open-pole possibility: retained and defended as possible
theory as expedition foundation: rejected
polar expedition as independent scientific/national project: defended
```

## 4. Curator classification

```yaml
BRIDGE-032-003:
  previous: SUPPORTED_SPLIT_WITH_1827_BIBLIOGRAPHIC_CONTINUITY
  current: SUPPORTED_PARTIAL_CONTINUITY_AND_STRATEGIC_REFRAMING
  supported:
    - SAME_PERSON_CARRIER
    - EXPOSURE_PATH
    - INSTITUTIONAL_CARRIER
    - PARTIAL_DOCTRINAL_CONTINUITY_IN_1827
    - STRATEGIC_AND_ARGUMENTATIVE_REFRAMING
  not_established:
    - FULL_LOYALTY_TO_ALL_SYMMES_CLAIMS
    - SYMMES_DOCTRINE_AS_CAUSE_OF_1836_PROGRAM
    - COMPLETE_AQR_PARAGRAPH_ALIGNMENT
    - PRIMARY_REYNOLDS_SYMMES_PERSONAL_CONTACT_ARTIFACT
```

## 5. AQR → Reynolds response edge

The relationship itself is verified from Reynolds's title and prefatory statement. The raw acquisition also identifies the counterpart as:

```yaml
title: "Symmes's theory"
publication: "American Quarterly Review"
volume: 1
issue: 1
issue_date: March 1827
pages: 235-253
creator: anonymous_or_unresolved
```

The edge can be promoted as `DIRECT_RESPONSE` and `DIRECT_CITATION` even though complete page-by-page alignment remains unfinished.

Allowed:

> Reynolds's pamphlet directly responds to an 1827 *American Quarterly Review* treatment of Symmes's theory and separates speculative cosmology from the independent case for polar exploration.

Not yet allowed:

> Every Reynolds argument has been matched to the exact AQR paragraph and page image.

## 6. Relationship to the 1836 negative record

The 1827 pamphlet and 1836 *Address* are not contradictory records.

```text
1827: partial defense of hollow/open-pole possibility
      + explicit separation of theory from expedition rationale

1836: institutional expedition dossier
      + no Symmes/hollow terminology located in available OCR
```

The later absence is therefore better classified as the result of a documented rhetorical trajectory, not evidence that Reynolds had already discarded every Symmes-related idea by November 1826.

## 7. Shared-byline candidate

The title page attributes the pamphlet to `A Citizen of the United States`. James McBride's 1826 Symmes treatise is reported with the same attribution.

This is registered separately as `ERR-032-002`, with competing explanations:

- common anonymous-pamphleteer convention;
- deliberate echo of McBride;
- shared Symmes-circle identity signal;
- publisher or catalogue normalization;
- independent parallel usage.

No direct McBride → Reynolds copying edge is created.

## 8. Remaining gaps

1. Complete curator inspection of AQR pp. 235–253.
2. Exact *National Intelligencer* publication dates for Reynolds's three numbers.
3. Page-image confirmation of key Reynolds quotations and page numbers.
4. Exact title page and byline of McBride's 1826 edition.
5. Earliest evidence explaining Reynolds's adoption of `A Citizen of the United States`.
6. Full 1827-to-1836 phrase matrix beyond headline terms.

## 9. Curator decision

```text
Pamphlet content access: resolved
Direct response relation: verified
1827 doctrinal continuity: partial, not total
Strategic separation of theory and expedition: verified
1836 negative evidence: retained and clarified
Shared-byline relation: candidate only
Full cross-domain lineage: not resolved
```
