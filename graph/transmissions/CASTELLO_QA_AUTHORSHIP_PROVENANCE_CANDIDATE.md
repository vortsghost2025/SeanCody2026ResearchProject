# Castello Q&A Authorship and Provenance Candidate

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `ERR-036-010`, Session 045  
> **Status:** candidate transmission/authorship graph; exact confession artifacts not yet acquired

## Current document fact

The surviving Q&A family contains a mature linked hierarchy:

```text
Draco / white Draco authority
        ↓ controls or creates
Grey and other worker castes
        ↓ inside
Dulce levels, laboratories and secret programs
```

This establishes the content of the surviving document family. It does not authenticate the attributed speaker.

## Leading provenance model

```text
Cherry Hinkle / Ann or Anne West
claimed drawings, stories, answers or persona performance
        ↓
Tal LeVesque / Jason Bishop III
selection + correction + own research + narrative assembly
        ↓
Thomas Edwin Castello persona
presented Q&A answer voice
        ↓
Branton / Bruce Alan Walton
compiler + headings + sequence + signed notes
+ possible unsigned editing not yet proven
        ↓
BBS / early electronic circulation
exact first object unknown
        ↓
The Dulce Book compilation
1996 header softly attested; first edition unverified
        ↓
web mirrors
common-descent textual family
```

## Evidence table

| Proposed edge | Current evidence | Status |
|---|---|---|
| Hinkle → raw Dulce material | quotes attributed to LeVesque describing Ann West/Cherry Hinkle material | `DIRECT_QUOTE_LEAD_PENDING_SOURCE` |
| Hinkle → answers as TEC | quote attributed to LeVesque: she answered questions as if she were TEC | `DIRECT_QUOTE_LEAD_PENDING_SOURCE` |
| LeVesque → TEC persona | quote attributed to LeVesque: `TEC is a creation` | `DIRECT_QUOTE_LEAD_PENDING_SOURCE` |
| LeVesque → edited source synthesis | quote attributed to LeVesque describing corrections, additions and mixing | `DIRECT_QUOTE_LEAD_PENDING_SOURCE` |
| LeVesque → packet distribution | quote attributed to LeVesque describing roughly 100 packets | `MANUFACTURED_INDEPENDENCE_CANDIDATE` |
| Branton → compilation | explicit authorship/compiler framing and signed notes in surviving text family | `SUPPORTED_COMPILER_ROLE` |
| Branton → unsigned hierarchy sentences | absence of signature plus hostile later claims | `POSSIBLE_NOT_PROVEN` |
| later mirrors → apparent corroboration | near-identical wording across derivative hosts | `SUPPORTED_COMMON_DESCENT` |

## Persona boundary

Use:

```text
Thomas Castello
        = document persona / attributed speaker
```

until an authenticated historical person is independently established.

Do not use:

```text
Thomas Castello
        = confirmed security technician or eyewitness
```

The quoted confession leads strongly challenge the historical-person reading, but their exact original source must be acquired before a direct-confession edge is promoted.

## Manufactured independence hypothesis

The reported packet strategy would create:

```text
one assembled source package
        ↓ distributed to many recipients
recipient A talk
recipient B article
recipient C book
recipient D newsletter
        ↓ later copied again
appearance of independent convergence
```

This mechanism directly fits the project's independence-graph method.

Required fields for every downstream source:

```yaml
source_dependency:
  received_packet_from_levesque: YES | NO | UNKNOWN
  cited_jason_bishop: YES | NO | UNKNOWN
  repeated_rare_wording: list
  first_known_date:
  independently_observed_claim: YES | NO | UNKNOWN
  likely_derivative: YES | NO | UNKNOWN
```

## Exact source objects required

1. Original LeVesque email containing `TEC is a creation`.
2. Complete email thread or correspondence with headers and dates.
3. Exact source for `she answered the questions, as IF she was TEC`.
4. Exact source for the Ann West/Cherry Hinkle mixing statement.
5. Exact source for the one-hundred-packet distribution statement.
6. Adam Gorightly book edition, page numbers and quotation context.
7. Any surviving packet, recipient cover letter, envelope, mailing list or recipient acknowledgement.
8. Cherry Hinkle's response or version of events.
9. Branton correspondence showing what material he received and edited.

## Valid outcomes

- `TEC_PERSONA_CREATION_CONFIRMED`
- `HINKLE_QA_ANSWER_ROLE_CONFIRMED`
- `LEVESQUE_EDITOR_AUTHOR_ROLE_CONFIRMED`
- `PACKET_SEEDING_CONFIRMED`
- `BRANTON_UNSIGNED_EDITING_CONFIRMED`
- `MULTI_AUTHOR_CREATIVE_ASSEMBLY`
- `SECONDARY_QUOTE_MISATTRIBUTED`
- `CONFLICTING_PARTICIPANT_ACCOUNTS`
- `UNKNOWN`

## Current decision

```yaml
persona_historical_status: NOT_ESTABLISHED
persona_creation_quote_lead: STRONG
hinkle_answer_role: STRONG_QUOTE_LEAD
levesque_editor_role: STRONG_QUOTE_LEAD
branton_compiler_role: SUPPORTED
packet_seeding: HIGH_VALUE_UNVERIFIED_DIRECT_QUOTE_LEAD
first_carrier: UNKNOWN
canonical_authorship_edge: false
canonical_transmission_edge: false
```
