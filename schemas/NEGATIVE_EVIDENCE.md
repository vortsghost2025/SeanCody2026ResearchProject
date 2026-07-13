# Canonical Negative Evidence Schema

Negative evidence records document what was searched, what was not found, how broad the search was, and what remains unsearched.

```yaml
NEGATIVE_RECORD:
  id: NEG-001
  claim_tested: >
    Paul Bennewitz read or was directly influenced by the Shaver Mystery
    before developing Dulce Base theories.
  verdict: NOT_FOUND
  confidence: MEDIUM
  search_conducted:
    - source: Greg Bishop, Project Beta
      result: No Shaver reference located in current pass
    - source: available Bennewitz and Dulce summaries
      result: No direct Shaver citation located
  search_not_yet_conducted:
    - Bennewitz personal correspondence
    - AFOSI files and FOIA releases
    - Kirtland investigation records
  important_caveat: >
    Not found does not mean nonexistent. Direct influence remains unproven;
    current relationship is UNKNOWN or SHARED_MOTIF depending on the specific claim.
  related_research_question: RQ-017
  added_session: SESSION_022
  last_reviewed: 2026-07-13
```

## Verdict values

- `NOT_FOUND`
- `CONTRADICTED_BY_AVAILABLE_EVIDENCE`
- `UNVERIFIABLE`
- `LIKELY_FABRICATED`
- `SEARCH_INCOMPLETE`

## Rules

1. Record the exact search scope.
2. Record spelling, language, date, archive, and catalogue limits.
3. Never convert a limited unsuccessful search into a universal claim.
4. Reuse negative records to prevent repeated duplicate searches.
5. Update the record when new archives or sources become available.