# ERR-036-026 — Poster-Layer Omission Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-026
  name: POSTER_LAYER_OMISSION_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A search limited to posts authored under Cherry Hinkle's reported username
    `Mystery` is treated as a search of the entire Project Avalon thread, causing
    a relay-posted Q&A attributed to Hinkle to be incorrectly declared absent.

  session_049_example: >
    One acquisition found no Q&A hierarchy body in Hinkle/Mystery posts. Two other
    acquisitions report that an unidentified poster `W` relayed the Q&A text with
    a Hinkle/Cherry attribution header.

  correct_boundary: >
    Thread-level content, poster-level content, quoted material, moderator framing
    and relay-posted material are separate source layers. Negative results from one
    username cannot be generalized to the whole thread.

  safe_labels:
    - HINKLE_DIRECT_POSTS_NO_QA_LOCATED
    - W_RELAY_QA_REPORTED
    - THREAD_LEVEL_QA_PRESENT
    - RELAY_IDENTITY_UNRESOLVED

  unsafe_labels:
    - AVALON_THREAD_CONTAINS_NO_QA
    - HINKLE_DIRECTLY_POSTED_EVERY_QA_SENTENCE
    - RELAY_POST_EQUALS_HINKLE_ORIGINAL_FILE

  promotion_test:
    - complete raw thread capture
    - post IDs and timestamps
    - quote ancestry
    - poster profile and identity basis
    - attachment provenance

  generated_session: SESSION_049
  last_reviewed: 2026-07-16
```
