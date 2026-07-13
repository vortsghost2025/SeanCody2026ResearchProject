# Canonical Schema: Chronology Object

**Version:** 1.0  
**Status:** Frozen with Repository Architecture v2.0  
**Purpose:** Represent the dated evolution of a claim, motif, entity, or system without conflating the date claimed by a source with the date the source appeared.

## Core rule

A chronology is not a list of dates copied from entity records. It records the sequence by which material appears, is transmitted, translated, revived, amplified, suppressed, or transformed.

The following dates must remain distinct:

- `CLAIMED_DATE`: when a source says an event occurred.
- `SOURCE_COMPOSITION_DATE`: when a text or account was composed.
- `MANUSCRIPT_DATE`: date of the surviving manuscript or physical witness.
- `PUBLICATION_DATE`: first known publication.
- `TRANSLATION_DATE`: entry into another language.
- `REDISCOVERY_DATE`: revival after dormancy.
- `AMPLIFICATION_DATE`: substantial audience expansion.
- `MEDIA_EXPLOSION`: broad mass-media adoption.
- `INTERNET_EXPLOSION`: networked circulation without earlier gatekeepers.
- `SUPPRESSION_EVENT`: removal, ban, discontinuation, or institutional rejection.
- `EXTERNAL_EVENT`: outside event that changes interpretation.
- `TRANSFORMATION_EVENT`: point where the content or framing materially changes.
- `GAP`: interval for which the carrying mechanism is unknown.

## Object schema

```yaml
CHRONOLOGY:
  id: CHRON-001
  canonical_name: "Underground Civilization System — Master Timeline"

  scope:
    object_type: SYSTEM          # SYSTEM | MOTIF | CLAIM | ENTITY | PUBLICATION
    object_id: SYS-001

  events:
    - id: CHRON-001-E001
      event_type: PUBLICATION_DATE

      date:
        value: "1871"
        precision: YEAR          # DAY | MONTH | YEAR | DECADE | CENTURY | RANGE | UNKNOWN
        calendar: GREGORIAN
        circa: false

      description: "A source is published."

      source_support:
        - source_id: SRC-TBD
          locator: TBD
          source_verified: false

      truth_separation:
        source_exists: UNKNOWN
        source_contains_claim: UNKNOWN
        historical_event_true: UNKNOWN

      related_objects:
        - ENTITY-TBD
        - PUB-TBD

      confidence: UNKNOWN        # HIGH | MEDIUM | LOW | UNKNOWN
      research_status: OPEN      # OPEN | PARTIAL | VERIFIED | DISPUTED | QUARANTINED
      notes: "Do not promote until the cited source and locator are verified."

  gaps:
    - start: "1948"
      end: "1979"
      description: "Carrying mechanism not yet documented."
      priority: HIGH
      related_question: RQ-023

  generated_session: SESSION_022
  last_reviewed: 2026-07-13
```

## Validation rules

1. Never substitute `CLAIMED_DATE` for publication or manuscript date.
2. Every event presented as verified requires a source locator.
3. Approximate dates must carry `circa: true` or a non-exact precision value.
4. A `GAP` is an explicit research object, not an invitation to fill the interval by inference.
5. Chronological proximity does not prove transmission.
6. The chronology may contain competing dates when sources conflict; preserve both and link the discrepancy record.
7. Truth about publication, truth about what a publication claims, and truth about the underlying event must remain separate.
