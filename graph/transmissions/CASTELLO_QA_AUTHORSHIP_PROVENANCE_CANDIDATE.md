# Castello Q&A Authorship and Provenance Candidate

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `DULCE-CAND-023`, `DULCE-CAND-024`  
> **Status:** strongly narrowed candidate graph; original working documents, first carrier and packet artifacts remain open

## Current document fact

The surviving Q&A family contains a mature linked hierarchy:

```text
Draco / white Draco authority
        ↓ controls or creates
Grey and other worker castes
        ↓ inside
Dulce levels, laboratories and secret programs
```

This establishes the text content. It does not authenticate the attributed speaker.

## November 2015 provenance source

A private email from Tal LeVesque to Adam Gorightly, reported as November 2015 and reproduced by Gorightly and later writers, contains the following linked self-attestations:

```text
TEC is a creation / myth
        ↓
interview did not happen; creative writing
        ↓
questions solicited from several people
        ↓ sent to Cherry twice
Cherry answered as if she were TEC
        ↓
LeVesque corrected material, added research and mixed it
        ↓
basis of two original Dulce Base articles
```

It also claims:

```text
about 100 large packets
        ↓ sent to authors and lecturers
material incorporated into talks, articles and books
        ↓
appearance of more than one source
```

Source classification:

```yaml
LEVESQUE_2015_EMAIL:
  original_email_facsimile: NOT_ACQUIRED
  recipient_reproduction: REPORTED
  later_verified_secondary_reproduction: ACQUIRED
  source_status: DIRECT_QUOTE_IN_VERIFIED_SECONDARY
```

## Leading provenance model

```text
Cherry Hinkle / Ann or Anne West
claimed source material + answer performance in TEC persona
        ↓
Tal LeVesque / Jason Bishop III
question routing + corrections + additions + own research + narrative assembly
        ↓
Thomas Edwin Castello document persona
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

This is now the leading source-layer reconstruction. It is not a complete sentence-level authorship allocation.

## Evidence table

| Proposed edge | Current evidence | Status |
|---|---|---|
| LeVesque → TEC persona | reproduced November 2015 email: `TEC is a creation` | `STRONGLY_SUPPORTED_SELF_ATTESTED_CREATION` |
| Hinkle → answers as TEC | reproduced email says questions were sent to Cherry twice and she answered as TEC | `SELF_ATTESTED_BY_LEVESQUE_CONTESTED` |
| Hinkle → raw Dulce material | reproduced email describes Ann West/Cherry Hinkle material | `SELF_ATTESTED_SCOPE_OPEN` |
| LeVesque → edited source synthesis | reproduced email describes corrections, additions and mixing | `SELF_ATTESTED_EXACT_DOCUMENT_SCOPE_PARTLY_AMBIGUOUS` |
| LeVesque → two original articles | reproduced email uses that phrase but does not name the two items | `SUPPORTED_REFERENTS_UNRESOLVED` |
| LeVesque → packet distribution intent | reproduced email describes approximately 100 packets and apparent source multiplicity | `SELF_ATTESTED_OPERATION_UNCORROBORATED` |
| named people → packet receipt | network proximity, acknowledgements, co-authorship or later use only | `ZERO_VERIFIED_RECIPIENTS` |
| Branton → compilation | explicit compiler framing and signed notes in surviving text family | `SUPPORTED_COMPILER_ROLE` |
| Branton → unsigned hierarchy sentences | absence of signature plus hostile later claims | `POSSIBLE_NOT_PROVEN` |
| later mirrors → apparent corroboration | near-identical wording across derivative hosts | `SUPPORTED_COMMON_DESCENT` |

## Persona boundary

Use:

```text
Thomas Edwin Castello
        = document persona / attributed Q&A speaker
```

The source record now strongly supports a created-persona reading.

Do not use:

```text
Thomas Edwin Castello
        = authenticated Dulce security technician
```

unless independent historical records and a custody chain are acquired.

## Hinkle-role boundary

```text
LeVesque says Hinkle answered as TEC
        ≠
every unsigned answer demonstrably written by Hinkle
```

Required:

- original question lists;
- Hinkle answer sheets or correspondence;
- handwriting or file provenance;
- version diff against the compiled Q&A;
- Hinkle's direct response to the exact claim.

## LeVesque editing-scope boundary

The reproduced email says his mixing formed the basis of `two original DULCE BASE articles`.

Do not automatically project that statement onto:

- every Castello Q&A sentence;
- every Branton chapter;
- the Hamilton collaboration;
- all later Dulce literature.

The unnamed article referents must be resolved separately.

## Manufactured-independence hypothesis

The self-attested mechanism is:

```text
one assembled packet family
        ↓ distributed to many recipients
recipient A talk
recipient B article
recipient C book
recipient D newsletter
        ↓ later copied again
appearance of independent convergence
```

Current status:

```yaml
PACKET_OPERATION:
  claimed_packet_count: approximately_100
  intent: CREATE_APPEARANCE_OF_MULTIPLE_SOURCES
  physical_packet_recovered: false
  cover_letter_recovered: false
  recipient_list_recovered: false
  verified_recipient_count: 0
  classification: SELF_ATTESTED_UNCORROBORATED
```

## Proposed recipient nexus

The following people are network or downstream candidates, not documented packet recipients:

| Person | Existing relation | Packet receipt |
|---|---|---|
| John Lear | Dulce briefings and related material | `UNKNOWN` |
| Bill Cooper | acknowledged LeVesque | `UNKNOWN` |
| Val Valerian | related compilation environment | `UNKNOWN` |
| Bill Hamilton | collaborator | `UNKNOWN` |
| Branton | downstream compiler | `UNKNOWN` |

Required for promotion:

- packet or envelope;
- cover letter;
- recipient acknowledgement;
- correspondence explicitly referencing receipt;
- diagnostic rare wording or shared error linked to one packet state.

## Participant and hostile-source disagreements

- Hinkle reportedly maintained a factual Castello narrative and contested parts of LeVesque's retrospective account.
- Hamilton reportedly claimed Castello biographical identifiers, but the records are unrecovered.
- Christa Tilton reportedly called the Castello story fabricated in a 1987 manuscript; the manuscript is unrecovered.
- A 2009 forum claimant alleged Branton altered or fabricated Q&A sections; identity and evidence are unverified.

Use `CONFLICTING_PARTICIPANT_ACCOUNTS`, not consensus.

## July 1990 carrier boundary

A reported *Trends and Predictions Analyst*, Vol. 6 No. 2, July 1990 item remains unverified at issue level.

Required:

- cover and masthead;
- contents;
- article pages;
- exact hierarchy passage;
- grammar identifying the agent using Grey mercenaries;
- archive or collector provenance.

Until then:

```text
reported July 1990 carrier
        = ITEM_LEVEL_UNVERIFIED
```

## Current decision

```yaml
persona_historical_status: NOT_ESTABLISHED
persona_creation_self_attestation: STRONGLY_SUPPORTED
hinkle_answer_role: SELF_ATTESTED_CONTESTED
levesque_editor_role: SELF_ATTESTED_SCOPE_PARTLY_AMBIGUOUS
branton_compiler_role: SUPPORTED
branton_unsigned_editing: POSSIBLE_NOT_PROVEN
packet_seeding_intent: SELF_ATTESTED
packet_operation_physical_status: UNCORROBORATED
verified_packet_recipients: 0
first_carrier: UNKNOWN
july_1990_issue: ITEM_LEVEL_UNVERIFIED
canonical_authorship_edge: false
canonical_transmission_edge: false
canonical_manufactured_independence_edge: false
```
