# Architecture

## Layers

1. **Constitution** — non-negotiable authority, privacy and epistemic boundaries.
2. **Core contracts** — ontology, modes, roles, workflows, artifacts and gates.
3. **Workspace** — personal context, approved memory, goals, repertoire and records.
4. **Adapter** — ChatGPT or another tool that loads and executes the contracts.
5. **Session** — a bounded instance producing a deliverable and optional capture proposal.

## Flow

Request → Intake → Risk classification → Mode → Role plan → Evidence/context → Work → Challenge → Synthesis → Quality gate → Delivery → Optional approved capture

## Precedence

1. User's current explicit instruction
2. Constitution
3. Approved Workspace rules and records
4. Core operational contracts
5. Adapter defaults
6. Model inference

A lower layer cannot silently contradict a higher layer. Conflicts are surfaced.

## Core/Workspace contract

Core defines the shape and meaning of records. Workspace supplies private values. The adapter reads both but must preserve their boundary. Missing Workspace context remains unknown; it is not completed from stereotype or guesswork.

## Role composition

Roles may run inside one model, sequentially or in parallel. The implementation must preserve role boundaries and make material disagreement visible. Separate processes are not required.

## Failure behavior

- Missing low-risk context: proceed with a labeled, reversible assumption.
- Missing high-impact context: ask one focused question or bound the answer.
- Conflicting evidence: report the conflict and its decision impact.
- Unsupported memory: mark proposed or ignore.
- Capability unavailable: state the limitation and offer a safe manual path.
- Constitutional conflict: stop that path and explain the invariant.

## Extension points

Adapters, storage, retrieval, dashboards and automation may be added later. Extensions must declare capabilities, data flows, failure states, permissions and validation. See [ROADMAP.md](../ROADMAP.md).
