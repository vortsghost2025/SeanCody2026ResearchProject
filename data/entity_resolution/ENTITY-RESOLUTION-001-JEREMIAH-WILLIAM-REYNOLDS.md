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
      - lecturer and writer associated with Symmes controversy
      - advocate for polar and South-Seas exploration
      - organizer/participant in the private 1829 South-Seas expedition
      - author of the 1827 Remarks pamphlet
      - later expedition lobbyist and writer

  entity_b:
    name: "William Reynolds"
    roles:
      - United States Navy passed midshipman
      - officer aboard the Peacock during the United States Exploring Expedition
      - associated with 1840 Antarctic sightings and later expedition journal

  conflation_rule: >
    A reference to Midshipman Reynolds, Reynolds Peak, Cape Hudson sightings,
    or the Peacock during the 1838-1842 Wilkes Expedition must not be assigned
    to Jeremiah N. Reynolds without an explicit primary source naming Jeremiah.

  generated_session: SESSION_033
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

The two men belong to related historical systems but occupy different roles.

## Allowed relationships

Potentially valid:

- Jeremiah N. Reynolds helped create political and cultural momentum for a U.S. exploring expedition.
- William Reynolds later served in the U.S. Exploring Expedition that actually sailed under Charles Wilkes.
- Later historical writing may place both within one institutional lineage.

Not valid without new evidence:

- Jeremiah personally made William's 1840 Antarctic sightings.
- Jeremiah was the passed midshipman aboard the *Peacock*.
- William's journal directly expresses Jeremiah's Hollow Earth beliefs.
- A shared surname proves family, contact, or doctrinal continuity.

## Promotion test for any relationship

Require one of:

- official crew or officer lists;
- Navy service records;
- expedition journals with full names;
- correspondence;
- direct citation or acknowledgement;
- institutional records linking Jeremiah's advocacy to William's appointment or observations.

## Reuse rule

Future synthesis must use full names whenever both men are in scope:

```text
Jeremiah N. Reynolds — advocate / organizer / writer
William Reynolds — naval officer / Wilkes Expedition observer
```
