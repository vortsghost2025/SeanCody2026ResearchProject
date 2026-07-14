# ERR-032-002 — `Citizen of the United States` Shared Byline

```yaml
ERROR_OR_PHRASE_FINGERPRINT:
  id: ERR-032-002
  status: SUPPORTED_NONDIAGNOSTIC_FINGERPRINT
  related_bridge: BRIDGE-032-003

  normalized_phrase: "Citizen of the United States"

  occurrence_a:
    work: "Symmes's Theory of Concentric Spheres"
    associated_creator: "James McBride"
    year: 1826
    printed_form: "By a Citizen of the United States"
    place: Cincinnati
    printer_publisher: "Morgan, Lodge and Fisher"
    ia_identifier: symmesstheoryofc00mcbr
    ark: ark:/13960/t9j392z40
    verification: PRIMARY_TITLE_PAGE_CONFIRMED

  occurrence_b:
    work: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    associated_creator: "Jeremiah N. Reynolds"
    year: 1827
    printed_form: "By a Citizen of the United States"
    place: Washington
    printer_publisher: "Gales & Seaton"
    ia_identifier: remarksonreviewo00reyn
    ark: ark:/13960/t1tf1gd11
    lccn: "06040937"
    verification: PRIMARY_TITLE_PAGE_CONFIRMED

  awareness_layers:
    awareness_of_reviewed_work: SUPPORTED
    awareness_of_McBride_attribution_phrase: SUPPORTED_FROM_REYNOLDS_TEXT
    awareness_of_exact_McBride_title_page_as_visual_source: INFERRED_PLAUSIBLE_NOT_PROVEN

  suspected_mechanisms:
    - DELIBERATE_RHETORICAL_ECHO
    - SHARED_GROUP_IDENTITY
    - GENERIC_PERIOD_ANONYMITY
    - INDEPENDENT_PARALLEL_USE

  current_assessment:
    shared_phrase_occurrence: VERIFIED
    phrase_uniqueness: LOW_OR_UNRESOLVED
    deliberate_echo: PLAUSIBLE_NOT_PROVEN
    shared_circle_signal: PLAUSIBLE_NOT_PROVEN
    catalogue_normalization: CONTRADICTED_FOR_THESE_TWO_ITEMS
    copying_or_coordination_edge: NOT_ESTABLISHED
    newspaper_stage_byline: UNKNOWN

  search_state:
    exact_National_Intelligencer_installments: NOT_ACQUIRED
    free_source_search: CLOSED_AFTER_EXHAUSTIVE_PASS
    next_access_required: PAID_ARCHIVE_OR_LOC_ISSUE_BROWSING

  generated_session: SESSION_031
  updated_session: SESSION_032_CONTINUATION
  last_reviewed: 2026-07-13
```

## What is primary-confirmed

Both title pages use the same civic anonymity formula. This removes catalogue normalization as the explanation for the phrase appearing on these two artifacts.

Reynolds also refers inside his response to the reviewed work as written by a `Citizen of the United States`. That supports awareness of the attribution phrase. It does **not** prove that he consciously copied the visual wording from McBride's title page or intended a coded signal.

## Correct awareness boundary

```text
Reynolds knew the McBride/Symmes work under review
        = supported

Reynolds knew the work was attributed to a Citizen of the United States
        = supported from Reynolds's own wording

Reynolds deliberately copied the exact McBride title-page byline
        = plausible, not proved
```

## Why the context remains interesting

The match has more contextual value than two unrelated anonymous works because Reynolds:

1. directly discusses the McBride/Symmes work;
2. repeats its civic attribution in the body of his response;
3. uses the same formula on his own adjacent response artifact;
4. participates in the same controversy one year later.

This makes rhetorical echo and shared-circle alignment plausible. It does not reveal Reynolds's intent.

## Distinctiveness boundary

```text
phrase match alone
        = low diagnostic value

phrase match + textual awareness + same controversy + one-year proximity
        = historically meaningful contextual fingerprint

copying, coordination, or secret code
        = not established
```

A bounded control confirmed that similar civic anonymity formulas existed outside the Symmes material. It did not produce a sufficiently complete item table to calculate rarity or network concentration.

## Blocked remaining test

The decisive remaining question is whether the byline appeared in Reynolds's three *National Intelligencer* numbers or was added when Gales & Seaton collected them as a pamphlet.

Free/public searches did not recover the issue-level originals. Continue only with:

- paid newspaper archives;
- Library of Congress issue or microfilm access;
- exact reprint leads;
- or a new institutional index.

Read: `research_inbox/SESSION_032_CONTINUATION_CLOSEOUT.md`.

## Allowed synthesis language

Allowed:

> McBride's 1826 Symmes treatise and Reynolds's 1827 response use the same primary-confirmed civic byline. Reynolds knew the earlier attribution phrase, making rhetorical echo plausible, but the phrase was not distinctive enough to prove copying or coordinated signaling.

Not allowed:

> Reynolds's byline is a proven secret Symmes-circle code copied from McBride.
