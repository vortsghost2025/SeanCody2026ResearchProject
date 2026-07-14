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

  contextual_link:
    evidence: >
      Reynolds explicitly identifies the reviewed Symmes work as written by a
      Citizen of the United States and uses the same civic anonymity formula on
      his own response pamphlet.
    status: EXPLICIT_AWARENESS_SUPPORTED

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

  generated_session: SESSION_031
  updated_session: SESSION_032
  last_reviewed: 2026-07-13
```

## What changed

Both title pages are now primary-confirmed. This removes `catalogue normalization` as an explanation for why the phrase appears on these two artifacts.

The phrase is nevertheless not unique. A limited control found unrelated period uses, so the wording cannot function as a copying fingerprint by itself.

## Why the context remains interesting

The match is more meaningful than two unrelated anonymous books sharing a generic byline because Reynolds:

1. directly discusses the McBride/Symmes work;
2. identifies its civic attribution;
3. reuses the same formula in an adjacent response artifact;
4. operates inside the same controversy one year later.

That supports a plausible rhetorical echo or public alignment. It does not reveal whether the reuse was intentional signaling, ordinary patriotic anonymity, or both.

## Distinctiveness boundary

```text
phrase match alone
        = low diagnostic value

phrase match + direct awareness + same controversy + one-year proximity
        = historically meaningful contextual candidate

copying or coordinated code
        = not established
```

## Promotion test still outstanding

1. Recover the three *National Intelligencer* versions and determine their signatures/bylines.
2. Complete a bounded 1820–1830 control with at least five exact non-Symmes title-page occurrences.
3. Compare subject, city, printer, and format across the controls.
4. Search correspondence, advertisements, and notices for an explanation of Reynolds's attribution.
5. Determine whether the byline was added for the collected pamphlet or present in the newspaper series.

## Allowed synthesis language

Allowed:

> McBride's 1826 Symmes treatise and Reynolds's 1827 response use the same primary-confirmed civic byline. Reynolds knew the earlier attribution, making rhetorical echo plausible, but the phrase was not unique enough to prove copying or coordinated signaling.

Not allowed:

> Reynolds's byline is a proven secret Symmes-circle code copied from McBride.
