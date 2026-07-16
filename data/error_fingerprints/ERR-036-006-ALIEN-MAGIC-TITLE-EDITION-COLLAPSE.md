# ERR-036-006 — *Alien Magic* Title / Edition Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-006
  related_question: RQ-036
  related_candidate: DULCE-CAND-017

  name: ALIEN_MAGIC_TITLE_EDITION_COLLAPSE
  status: SUPPORTED_BIBLIOGRAPHIC_SPLIT_PENDING_PRIMARY_OBJECTS

  error_pattern: >
    Wording, date, publisher and contents from later William F. Hamilton editions
    are projected backward onto a reported 1989 item because they share the short
    title Alien Magic.

  objects_to_keep_separate:
    - object: ALIEN_MAGIC_1989_UFORCES
      reported_title: "Alien Magic — Behind the Cloak of Secrecy Hides an Alien Power!"
      creator: William F. Hamilton
      reported_publisher: UFORCES
      reported_date: 1989
      source_status: UNACQUIRED_BIBLIOGRAPHIC_LEAD

    - object: ALIEN_MAGIC_1996_INNER_LIGHT
      reported_title: "Alien Magic: UFO Crashes, Abductions & Underground Bases"
      creator: William F. Hamilton III
      publisher: Inner Light / Global Communications
      date: 1996
      source_status: LATER_PHYSICAL_EDITION_LEAD

  prohibited_inference: >
    A passage appearing in the 1996 book was necessarily present in the reported
    1989 UFORCES object.

  required_evidence:
    - title page
    - copyright page
    - publisher and address
    - contents
    - pagination
    - edition statement
    - exact TAL / Bishop / Dulce passages
    - physical or archival provenance

  generated_session: SESSION_043
  last_reviewed: 2026-07-16
```

## Current boundary

The reported 1989 object is a high-value candidate because it may carry Hamilton/TAL material before *Matrix II* and *UFO Universe*. It remains unverified because no title page, copyright page or full scan has been acquired.

The 1996 object is historically useful as a later carrier, but it cannot date the wording it contains to 1989 without edition comparison.

```text
same short title
        ≠
same subtitle
        ≠
same publisher
        ≠
same edition
        ≠
same wording
```

## Date caution

Retailer dates such as `January 1, 1989` may be database defaults. They are leads, not title-page evidence.
