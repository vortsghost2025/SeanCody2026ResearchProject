# Canonical Entity Schema

**Types:** `PERSON`, `ORGANIZATION`, `PUBLICATION`, `LOCATION`, `EXPEDITION`, `CONCEPT`

```yaml
ENTITY:
  id: ENTITY-Palmer-001
  type: PERSON
  canonical_name: Raymond Arthur Palmer
  aliases:
    - Ray Palmer
  dates:
    birth: 1910-08-01
    death: 1977-08-15
  nationality: American
  roles:
    - Editor, Amazing Stories
    - Co-founder, Fate magazine
    - Publisher, Other Worlds Science Stories
  significance: >
    Major transmission hub linking Shaver-era pulp mythology with early
    flying-saucer culture through editing, factual framing, publishing,
    and direct collaboration.
  known_connections:
    - entity_id: ENTITY-Shaver-001
      edge_type: DIRECT_CITATION
    - entity_id: ENTITY-Arnold-001
      edge_type: PERSONAL_CONTACT
  graph_role: TRANSMISSION_HUB
  node_weight: HIGH
  primary_sources: []
  secondary_sources: []
  open_questions: []
  added_session: SESSION_022
  last_reviewed: 2026-07-13
```

## Entity-resolution rules

1. Different names are not merged without evidence.
2. Namesakes remain separate entities.
3. Pseudonyms and spelling variants are stored as aliases with source support.
4. Publications, people, institutions, and claims are separate nodes.
5. A person's significance is an analytical field, not proof of any claim.
6. Quarantined identities may exist as nodes but must carry an explicit status and must not be treated as verified persons.