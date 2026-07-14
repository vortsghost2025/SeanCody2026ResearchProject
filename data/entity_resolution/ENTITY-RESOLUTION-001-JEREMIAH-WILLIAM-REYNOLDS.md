# ENTITY-RESOLUTION-001 — Jeremiah N. Reynolds vs. William Reynolds

```yaml
ENTITY_RESOLUTION:
  id: ENTITY-RESOLUTION-001
  status: HIGH_CONFIDENCE_DISTINCT_PERSONS
  risk_type: NAMESAKE_CONFLATION

  entity_a:
    name: "Jeremiah N. Reynolds"
    life_dates: "1799-1858"
    roles:
      - lecturer and writer associated with the Symmes controversy
      - author of the 1827 Remarks pamphlet
      - advocate for polar and South-Seas exploration
      - organizer/participant in the private 1829 South-Seas expedition
      - later expedition lobbyist and writer

  entity_b:
    name: "William Reynolds"
    reported_life_dates: "1815-1879"
    roles:
      - United States Navy midshipman / passed midshipman
      - officer aboard Peacock during the United States Exploring Expedition
      - associated with 1840 Antarctic observations
      - author of an expedition journal

  conflation_rule: >
    A reference to Midshipman Reynolds, Reynolds Peak, Eld Peak, Cape Hudson,
    Peacock, or 1840 Wilkes Expedition observations must not be assigned to
    Jeremiah N. Reynolds without an explicit primary source naming Jeremiah.

  source_state:
    distinction: HIGH_CONFIDENCE
    permanent_guardrail: ACTIVE
    primary_roster_and_service_record_anchor: REQUIRED_FOR_FINAL_ENTITY_DOSSIER
    current_secondary_leads: NONCANONICAL_SUPPORT_ONLY

  generated_session: SESSION_033
  updated_session: SESSION_032_CONTINUATION
  last_reviewed: 2026-07-13
```

## Why this matters

A model-generated lead package proposed using `Midshipman Reynolds` sightings during the Wilkes Expedition to evaluate Jeremiah N. Reynolds's observational credibility.

That would create a false bridge:

```text
Jeremiah N. Reynolds, Hollow Earth / expedition advocate
        ↓ false identity merge
William Reynolds, Wilkes Expedition officer and Antarctic observer
```

The two men belong to related institutional history but occupy different roles.

## Allowed relationships

Potentially valid:

- Jeremiah N. Reynolds helped create political and cultural momentum for a United States exploring expedition.
- William Reynolds later served in the U.S. Exploring Expedition under Charles Wilkes.
- Later historical writing may place both inside one institutional lineage.

Not valid without new evidence:

- Jeremiah personally made William's 1840 Antarctic observations.
- Jeremiah was the passed midshipman aboard the *Peacock*.
- William's journal directly expresses Jeremiah's Hollow Earth views.
- A shared surname proves family, contact, appointment influence, or doctrinal continuity.

## Source boundary

The namesake block is strong enough to enforce immediately because the roles, timeframes, and attributed publications are different. However, the permanent entity dossiers should replace encyclopedic or model-generated summaries with item-level anchors.

Required anchors:

1. official Wilkes Expedition officer or crew list naming William Reynolds;
2. William Reynolds's journal title page or manuscript catalogue record;
3. U.S. Navy service or appointment record;
4. Jeremiah N. Reynolds catalogue-authority and expedition records;
5. full-name references in contemporary logs, correspondence, or congressional documents.

Wikipedia or modern summaries may remain discovery leads only, not the final basis for the guardrail.

## Promotion test for any cross-person relationship

Require one of:

- correspondence between the two men;
- appointment or patronage records;
- direct citation or acknowledgement;
- official records linking Jeremiah's lobbying to William's appointment or observations;
- reliable evidence of family relationship.

## Reuse rule

Future synthesis must use full names whenever both men are in scope:

```text
Jeremiah N. Reynolds — advocate / organizer / writer
William Reynolds — naval officer / Wilkes Expedition observer
```

A source that says only `Reynolds` must remain unresolved until ship, rank, date, publication, or full name identifies the person.
