# Memory and Knowledge

## Principle

Memory is curated state, not accumulated conversation.

## Record fields

Each durable record must contain:

- ID: TYPE-YYYYMMDD-NNN;
- type;
- concise statement;
- source or provenance;
- scope: core or workspace;
- sensitivity: public, internal, confidential or restricted;
- confidence when inferential;
- status;
- created date;
- review date or retention rule;
- relationships;
- approval.

## Write policy

The system may write without a separate approval only when the user explicitly instructed it to record the item and the scope is clear. Otherwise:

1. propose the record;
2. show type, wording, source, scope and sensitivity;
3. ask for approve, edit or reject;
4. persist the approved version;
5. return its ID.

Identity, preference, observation and sensitive records require explicit approval.

## Read policy

Retrieve the smallest relevant set. Cite record IDs for consequential reasoning. If an entry is absent, say it is not recorded. Never fill missing personal context from stereotypes or neighboring entries.

## Promotion policy

- Hypothesis → observation: requires specified evidence.
- Observation → learning: requires review and counterexample consideration.
- Preference → active rule: requires user instruction.
- Workspace → Core: requires anonymization, generalization, usefulness and explicit approval.

## Correction

A correction creates a traceable superseding record or edits the authoritative record with history. Related conclusions must be reviewed. Rejected records are not used.

## ChatGPT note

Project memory may help recall chats and files, but it is not the ThoughtOps source of truth. Approved durable knowledge belongs in Workspace records. If an unwanted project chat could contaminate context, move or delete it and correct the Workspace record explicitly.
