# SESSION 029 — Reynolds Verification Variant Manifest

> **Mode:** provenance preservation before curator promotion  
> **Target:** `BRIDGE-032-003` and `BRIDGE-032-004`  
> **Document revision observed:** `ALtnJHzNiabaL8WErC3EzvVTw0mkar4jgEazBTUE1QKwfGb50FUoAwQGFc9ToaHEGldYAXHuv0nfgm0-mT4V-HnGV6a4n3GNAG6dBXkMjE8`

## Input A — Claude Sonnet 5 Search

```yaml
source_document_id: 1bRjBuxtBOj0xa9HjhqjGGnY6GKbktzATO4tlGMskh_Y
tab_id: t.qj184r5du29x
source_label: claude-sonnet-5-search
record_type: REYNOLDS_VERIFICATION_VARIANT
```

### Strong contributions

- broad chronology from the Symmes lecture period through Reynolds's expedition advocacy;
- flags a possible 1827 Reynolds defense of Symmes after the personal break;
- recognizes that John Quincy Adams's wording supports conscious reframing or repudiation;
- identifies Poe's review, the Reynolds-to-Poe textual-reuse claim, and the contested deathbed anecdote;
- notices that institutional stigma may persist even after doctrinal abandonment.

### QC weaknesses

- several locators come from mirrors, blogs, Wikipedia, or secondary summaries rather than opened primary artifacts;
- the source table dates the Adams entry as 1828 while the quoted transition belongs to the November 4, 1826 entry;
- it lists Poe's January 1837 review at page 65, while the reviewed transcript gives pages 68–72;
- it recommends `KNOWN_COPY` before supplying aligned passages with page locators;
- the 1827 pamphlet, 1842 bankruptcy-petition identity, and Reynolds/Symmes joint lecture relationship remain unverified at item level;
- the claim that the 1829 private expedition reached the Antarctic shore requires independent primary verification.

## Input B — GPT-5.2 Search

```yaml
source_document_id: 1bRjBuxtBOj0xa9HjhqjGGnY6GKbktzATO4tlGMskh_Y
tab_id: t.wiq40t5dc34n
source_label: gpt-5.2-search
record_type: REYNOLDS_VERIFICATION_VARIANT
```

### Strong contributions

- exact Internet Archive identifiers for the published John Quincy Adams diary and Reynolds's 1836 *Address*;
- exact GovInfo PDF for the December 16, 1834 East India Marine Society memorial;
- exact Poe Society transcript for the January 1837 review;
- issue-level evidence that the January 1837 *Southern Literary Messenger* contains both the Reynolds review and the first *Pym* installment;
- a reproducible negative OCR search for `Symmes` and `hollow` in the 1836 *Address*;
- careful separation of `DIRECT_CITATION` from the still-unverified `KNOWN_COPY` claim.

### QC limitations

- the John Quincy Adams diary quotation was supplied with a stable scan identifier but was not independently page-image checked by the curator in this pass;
- the `convert to Captain Symmes` quotation is contextual evidence of political stigma, not direct evidence about Reynolds unless its full diary context names him;
- a two-keyword OCR search supports lexical absence but cannot prove total conceptual abandonment;
- issue-level co-location creates an exposure opportunity, not proof that the review caused or shaped the *Pym* installment;
- model-created local IDs are acquisition labels, not canonical repository entity IDs.

## Curator spot checks completed

1. Reynolds's *Address* item metadata was confirmed from the Internet Archive item page:
   - author: Jeremiah N. Reynolds;
   - publication year: 1836;
   - publisher: Harper & Brothers;
   - IA identifier: `addressonsubjec00reyngoog`;
   - ARK: `ark:/13960/t6b282459`;
   - LCCN: `04033154`.
2. The primary OCR text contains the South-Pole passage beginning `What ! extend our researches to regions surrounding the South Pole !`.
3. OCR searches returned no matches for `Symmes` or `hollow` in that transcription.
4. Poe's January 1837 review explicitly names and reviews Reynolds's 1836 *Address* on pages 68–72.
5. The January 1837 *Southern Literary Messenger* issue index lists both `Arthur Gordon Pym, No. I` and the Reynolds review.
6. The December 16, 1834 GovInfo memorial names `the memorial of J. N. Reynolds and others, dated November, 1834` and routes it toward Congress.

## Separate uploaded attachment

```yaml
uploaded_name: "Pasted text(4).txt"
sha256: 8c7b7297064092e997f5a4d4e4405bd5af6f6c05c7a0b3ada785c2ad5febe7bc
content_title: SESSION_022_SHAVER_MYSTERY_ACQUISITION.md
status: INCOMPLETE_RAW_RECOVERY
relation_to_session_029: NONE
```

The attachment concerns Shaver/Palmer and ends mid-sentence during `SHAVER-004`. It is preserved separately and must not be treated as a Reynolds verification variant.

## Curator disposition

```text
Verification variants preserved: 2
Separate incomplete attachment preserved: 1
Reynolds bridge fully promoted: no
Supported split finding: yes
Direct-citation edge eligible: yes
Known-copy edge eligible: no
RQ-032 status change: none
```
