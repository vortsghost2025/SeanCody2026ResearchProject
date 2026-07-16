# ERR-036-031 — Thread Search Completeness Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-031
  name: THREAD_SEARCH_COMPLETENESS_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A search-engine result, archive rendering, one username search or one paginated
    thread view is treated as a complete acquisition of every post, attachment and
    deleted state in a long forum thread.

  session_050_instance: >
    Competing agents concluded both that Thread 8393 contains no Q&A and that it
    contains a full Q&A posted by Hinkle or W. None preserved the decisive raw post.

  correct_boundary: >
    Absence from snippets or one view is bounded non-retrieval. Presence claimed
    without a raw post is an acquisition lead. Neither resolves thread completeness.

  promotion_test:
    - enumerate every page and post ID
    - capture print, archive, mobile and Wayback states
    - preserve deleted-link and attachment records
    - commit raw HTML and hashes
    - map every extracted quotation to a post

  generated_session: SESSION_050
  last_reviewed: 2026-07-16
```
