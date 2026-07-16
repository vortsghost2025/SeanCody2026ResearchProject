# SESSION 046 — LeVesque Confession and Provenance Cross-QC

> ## TOP-LEVEL RESULT
>
> ```text
> November 2015 confession email text: LOCATED THROUGH VERIFIED SECONDARY REPRODUCTION
> Original email facsimile and headers: NOT ACQUIRED
> TEC persona-creation self-attestation: STRONGLY SUPPORTED
> Hinkle answering as TEC: SELF-ATTESTED BY LEVESQUE; CONTESTED
> LeVesque mixing/editing: SELF-ATTESTED; EXACT DOCUMENT SCOPE PARTLY OPEN
> One-hundred-packet operation: SELF-ATTESTED; PHYSICALLY UNCORROBORATED
> Verified packet recipients: 0
> July 1990 newsletter issue: ITEM-LEVEL UNVERIFIED
> Castello Q&A hierarchy content: PREVIOUSLY CONFIRMED AT TEXT LEVEL
> Canonical authorship / first-source / coordinated-operation edge: NO
> RQ-036: SEARCHING
> ```

## 1. Confession-source result

The strongest surviving provenance object is a November 2015 private email from Tal LeVesque to Adam Gorightly, reproduced in Gorightly's later work and in a Hayakawa article drawing from that correspondence.

The reproduced email states, in one continuous source layer, that:

- `TEC (Thomas Edwin Castello) is a creation`;
- the interview did not happen and was creative writing;
- LeVesque solicited questions and sent them to Cherry Hinkle / Ann West twice;
- she answered as if she were TEC;
- LeVesque corrected, supplemented and mixed Hinkle material with his own research;
- that material became the basis of two original Dulce Base articles;
- he claimed to send roughly one hundred large packets to authors and lecturers to create apparent multiple-source confirmation.

The source class is:

```yaml
LEVESQUE_2015_EMAIL:
  original_medium: PRIVATE_EMAIL
  sender: TAL_LEVESQUE
  recipient: ADAM_GORIGHTLY
  reported_date: NOVEMBER_2015
  publicly_inspected_original: false
  reproduced_by_recipient: true
  later_reproduction: true
  source_status: DIRECT_QUOTE_IN_VERIFIED_SECONDARY
```

This is stronger than an anonymous web repetition, but weaker than an original email export, facsimile, full header set or archival deposit.

## 2. What the confession resolves

### Document persona

The confession strongly establishes that LeVesque represented `Thomas Edwin Castello` as a created document persona rather than a straightforward authenticated witness identity.

Safe result:

```text
LeVesque self-attested that TEC was a creation / myth
        +
no authenticated independent historical Castello witness has been established
        =
STRONGLY_SUPPORTED_DOCUMENT_PERSONA
```

This does not logically prove that no person of that name ever existed anywhere. It resolves the research use of the Q&A voice: it cannot be treated as authenticated whistleblower testimony.

### Hinkle role

LeVesque's reproduced email explicitly describes Cherry Hinkle / Ann West answering submitted questions as if she were TEC, twice.

Current classification:

```yaml
HINKLE_QA_ROLE:
  claim_source: LEVESQUE_2015_SELF_ATTESTATION
  role_claimed: ANSWERED_QUESTIONS_IN_TEC_PERSONA
  rounds_claimed: 2
  exact_question_sets_recovered: false
  original_answers_recovered: false
  hinkle_direct_confirmation: false
  participant_dispute: present
  status: SELF_ATTESTED_BY_LEVESQUE_CONTESTED
```

Do not assign every unsigned Q&A sentence to Hinkle. The original question sheets, answers and version diffs are absent.

### LeVesque mixing and editing

The confession says LeVesque corrected material, added research and mixed it together as the basis of `the two original DULCE BASE articles`.

The two articles are not named inside the reproduced paragraph. Candidate referents include:

1. *The Dulce Base*;
2. *The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base*;
3. possibly another LeVesque item, but not automatically the Hamilton collaboration or the entire Castello Q&A.

Current status:

```text
LEVESQUE_EDITOR_AUTHOR_ROLE
        = SELF_ATTESTED

EXACT_DOCUMENT_SCOPE
        = PARTLY_AMBIGUOUS
```

## 3. Packet operation

The reproduced statement is explicit about claimed intent:

```text
one hundred large packets
        ↓ sent to authors and lecturers
recipients mix material into talks, articles and books
        ↓
appearance of more than one source
```

This is a direct self-attestation of **manufactured independence as an intended strategy**.

But Session 046 recovered none of the following:

- a packet;
- envelope;
- postmark;
- cover letter;
- manifest;
- mailing list;
- named-recipient statement in the confession;
- recipient acknowledgement;
- correspondence confirming receipt;
- item-level downstream dependency demonstration.

Therefore:

```yaml
PACKET_OPERATION:
  intent_self_attested: true
  packet_count_self_attested: approximately_100
  physical_packet_recovered: false
  verified_recipient_count: 0
  recipient_acknowledgement_count: 0
  operation_status: SELF_ATTESTED_UNCORROBORATED
  independence_status: MANUFACTURED_INDEPENDENCE_CANDIDATE
```

## 4. Proposed recipients are not documented packet recipients

The supplied synthesis names:

- John Lear;
- Bill Cooper;
- Val Valerian;
- Bill Hamilton;
- Branton.

The current evidence supports network proximity or downstream use, but not packet receipt:

| Person | Current link | Packet receipt proved? |
|---|---|---|
| John Lear | related Dulce material and public briefings | No |
| Bill Cooper | acknowledged LeVesque in later publication | No |
| Val Valerian | parallel/derivative source environment | No |
| Bill Hamilton | collaboration with LeVesque | No |
| Branton | compiler of LeVesque-adjacent material | No |

Use `PROPOSED_PACKET_RECIPIENT` or `NETWORK_NEXUS`, not `DOCUMENTED_PACKET_RECIPIENT`.

## 5. July 1990 newsletter claim

The proposed record is:

```yaml
artifact: Trends and Predictions Analyst
publisher: Patrick O'Connell
issue: Vol. 6, No. 2
reported_date: July 1990
article: The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base
attribution: TAL LeVesque
```

Session 046 did not acquire:

- cover;
- masthead;
- contents;
- article pages;
- library or collector record;
- issue scan;
- original wording in page context.

It therefore remains `ITEM_LEVEL_UNVERIFIED`.

The supplied wording may show:

```text
reptilian heritage beings named together
+
Greys described as mercenaries being used
+
Dulce context
```

But the grammatical controller of `being used` must be identified. Unless the same passage explicitly makes Draco or a reptilian authority the user/controller, classify it as `LINKED_CHAIN_IMPLIED` rather than `FULL_LINKED_CHAIN`.

## 6. Participant and hostile-source contradictions

### Hinkle

Hinkle reportedly maintained a factual Castello account and described LeVesque as a friend. This contests parts of LeVesque's retrospective story, but no direct Hinkle response to the exact November 2015 claims was acquired.

### Hamilton

Hamilton was reported to claim biographical identifiers for Castello. The records themselves were not acquired.

### Tilton

A secondary report says Christa Tilton's 1987 *Bennewitz Papers* manuscript called the Castello story fabricated. The manuscript remains unacquired. If verified, it would establish an early hostile/fabrication claim, not by itself prove who wrote the later Q&A.

### 2009 forum claimant

A forum participant claimed Branton fabricated or edited portions of the Q&A. Identity, custody and evidence remain unverified. Preserve as `HOSTILE_PARTICIPANT_CLAIM` only.

## 7. Correct provenance graph

```text
Hinkle / Ann-West material and persona performance
        ↓ claimed by LeVesque
LeVesque selection, correction, additions and narrative assembly
        ↓
Castello document persona / Q&A answer layer
        ↓
Branton compilation, sequencing, signed notes and possible unproven edits
        ↓
Dulce Book carrier family
        ↓
derivative mirrors
```

Alongside:

```text
LeVesque packet strategy self-attestation
        ↓
possible distribution to authors and lecturers
        ↓
possible dependent talks / articles / books
        ↓
apparent convergence
```

The first graph is strongly narrowed but still lacks original working documents. The second lacks physical and recipient corroboration.

## 8. Curator decision

```yaml
SESSION_046:
  confession_source: DIRECT_QUOTE_IN_VERIFIED_SECONDARY
  original_email: NOT_ACQUIRED
  tec_persona: STRONGLY_SUPPORTED_SELF_ATTESTED_CREATION
  authenticated_castello_testimony: REJECTED_AS_CURRENT_SOURCE_CLASS
  hinkle_answer_role: SELF_ATTESTED_CONTESTED
  levesque_editor_role: SELF_ATTESTED_SCOPE_PARTLY_OPEN
  branton_compiler_role: SUPPORTED
  branton_unsigned_editing: POSSIBLE_NOT_PROVEN
  packet_strategy_intent: SELF_ATTESTED
  packet_operation_physical_status: UNCORROBORATED
  verified_packet_recipients: 0
  july_1990_issue: ITEM_LEVEL_UNVERIFIED
  earliest_full_carrier: UNRESOLVED
  canonical_authorship_edge: false
  canonical_packet_operation_edge: false
  canonical_first_carrier_edge: false
  next_session: SESSION_047
```
