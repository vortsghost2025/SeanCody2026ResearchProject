# Canonical Motif Schema

Motifs track recurring idea-complexes independently of whether transmission is proven.

```yaml
MOTIF:
  id: MOTIF-underground-hostile-tech-001
  canonical_name: Hostile Subterranean Beings with Advanced Technology
  motif_family: underground
  core_elements:
    - subterranean civilization
    - hostile or degenerate inhabitants
    - advanced inherited or non-human technology
    - harm or control directed at surface humans
    - surface population unaware of the threat
  optional_elements:
    - abduction
    - sexual or genetic exploitation
    - mind control
    - benevolent and hostile factions
    - ancient or extraterrestrial origin
    - government complicity
  attestations:
    - record_id: SHAVER-001
      date: 1945-03
      elements_present:
        - subterranean civilization
        - hostile inhabitants
        - advanced technology
        - abduction
        - mind control
      transmission_status: SOURCE_VERIFIED
    - record_id: DULCE-001
      date: 1987
      elements_present:
        - subterranean facility
        - hostile beings
        - advanced technology
        - experimentation
        - government secrecy
      transmission_from_prior: SHARED_MOTIF
  earliest_verified_attestation: SHAVER-001
  earlier_candidates:
    - The Coming Race, 1871
    - Journey to the Centre of the Earth, 1864
  motif_stability: HIGH
  added_session: SESSION_022
```

## Rules

- A shared motif does not establish common origin.
- Each attestation must identify which elements are present and absent.
- Later additions must be tracked as mutations rather than projected backward.
- Culture-specific meanings remain separate even when visual or structural similarities exist.
- `first_attestation` means earliest currently verified example, not guaranteed historical origin.