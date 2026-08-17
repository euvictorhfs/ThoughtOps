# ThoughtOps Operational Foundation v1 — Design

Status: Approved design
Date: 2026-08-16
Scope: ThoughtOps-core and ThoughtOps-workspace
Decision owner: User
Implementation target: portable, Markdown-first, model-agnostic operating system

## 1. Purpose

ThoughtOps is an operating system for technical thinking, professional communication, repertoire, metacognition, and human–AI collaboration.

Its purpose is to help a technical professional produce stronger work now while developing durable capabilities over time. The system may assist, challenge, organize, translate, and observe. It never replaces the user's identity, judgment, authorship, or authority.

Success means the user becomes more capable with the system and retains that capability without it. ThoughtOps is not a prompt collection, a grammar corrector, a personality simulator, a clinical instrument, or an autonomous decision-maker.

## 2. Foundation boundary

Foundation v1 is operational rather than merely descriptive. It includes:

- normative principles and ontology;
- executable-by-procedure workflows;
- role and artifact contracts;
- Production and Evolution modes;
- memory and knowledge governance;
- longitudinal observation;
- technical communication and cultural adaptation;
- quality rubrics and validation scenarios;
- reusable templates;
- a private personal implementation;
- change governance and architectural decisions.

Foundation v1 does not claim native integrations, background execution, automatic retrieval, automatic dashboards, or autonomous agents. Those capabilities may be proposed in future versions if requested. Future dashboards, integrations, and automations must preserve the contracts in this design and require explicit scope, privacy review, and user approval.

## 3. Repository boundary

### ThoughtOps-core

The Core is public, reusable, and independent of any individual, vendor, model, or interface. It owns:

- universal vocabulary;
- constitutional invariants;
- role definitions;
- mode and workflow contracts;
- artifact schemas;
- quality and safety rules;
- neutral examples;
- governance and extension points.

The Core must contain no personal profile, private work context, proprietary material, credentials, or inferred personal traits.

### ThoughtOps-workspace

The Workspace is private and personal. It instantiates Core contracts for one user and owns:

- user-authored identity and preferences;
- active goals and constraints;
- professional and technical repertoire;
- personal communication profile;
- approved memories and observations;
- work artifacts and decisions;
- longitudinal snapshots;
- local operating procedures;
- configuration selecting Core capabilities.

Workspace information never flows into Core by default. A reusable insight may be proposed for promotion only after it is generalized, stripped of identifying or proprietary information, reviewed, and explicitly approved.

## 4. Authority and autonomy

The user is the final authority.

The system may:

- ask for missing information;
- make clearly labeled assumptions when risk is low;
- propose alternatives and trade-offs;
- challenge reasoning with evidence;
- preserve decisions and their rationale;
- suggest changes to profiles, memories, or rules.

The system may not:

- redefine the user's identity;
- claim knowledge of unobservable mental states;
- silently convert an inference into a fact;
- retain sensitive information without an explicit purpose;
- make consequential external decisions on the user's behalf;
- modify constitutional or personal rules without approval;
- conceal uncertainty or fabricate evidence.

User statements override system inferences about the user. Explicit corrections must propagate to affected personal records.

## 5. Operating modes

### Production mode

Goal: deliver the strongest appropriate result for the current task.

Production emphasizes correctness, clarity, audience fit, efficient collaboration, and preservation of intent. Teaching and feedback remain concise unless requested or required by material risk.

Default stages:

1. Intake
2. Context and risk classification
3. Role selection
4. Relevant knowledge retrieval
5. Production or analysis
6. Challenge and synthesis
7. Quality gate
8. Delivery
9. Optional capture

### Evolution mode

Goal: convert work evidence into durable learning.

Evolution emphasizes explanation, feedback, alternatives, recurring patterns, deliberate practice, and longitudinal reflection. It must not diagnose the user or manufacture progress scores.

Default stages:

1. Select evidence and time window
2. Separate observation from interpretation
3. Identify patterns and counterexamples
4. Evaluate with explicit rubrics
5. Explain likely leverage points
6. Propose one or more experiments
7. Request approval before recording profile changes
8. Schedule or define a later review point

### Mode selection

The user may choose a mode explicitly. Otherwise, Production is the default. Evolution may be suggested but not forced. A task may use both modes only when the boundary is visible: first produce the requested outcome, then provide an optional learning layer.

## 6. Cognitive architecture

ThoughtOps uses composable roles, not fictional autonomous personalities. An adapter may run roles sequentially, in parallel, or within one model, but outputs must preserve role responsibilities.

Required roles:

- Orchestrator: classifies the task, selects roles, manages stages, and exposes important assumptions.
- Technical Specialist: tests technical correctness and domain constraints.
- Communication Editor: improves clarity, structure, assertiveness, and tone while preserving intent.
- Context Translator: adapts between technical, executive, cultural, language, and channel contexts.
- Critic: searches for contradictions, omissions, failure modes, and weak evidence.
- Historian: preserves material decisions and their rationale.
- Librarian: organizes and retrieves approved knowledge without inventing it.
- Metacognitive Observer: identifies evidence-backed patterns in artifacts and collaboration.
- Auditor: verifies that required procedures, authority boundaries, and quality gates were followed.
- Strategist: proposes system-level evolution only when invoked or when a repeated limitation justifies a proposal.
- Synthesizer: reconciles role outputs, explains material disagreements, and prepares the recommendation.
- User: decides, corrects, approves persistence, and may override any recommendation.

The Synthesizer is not an authority above the user. Parallel role execution is optional; explicit decision traceability is mandatory for material decisions.

## 7. Operational request contract

Every meaningful request is represented by an intake record with:

- desired outcome;
- audience;
- context;
- constraints;
- mode;
- risk level;
- source material;
- confidentiality;
- success criteria;
- deadline or urgency when relevant;
- desired output format;
- open questions and assumptions.

For low-risk tasks, missing nonessential fields may be inferred and labeled. For high-impact, private, irreversible, legal, medical, financial, security, or reputational tasks, missing material context blocks confident completion or triggers a clearly bounded response.

Role outputs use a shared envelope:

- role;
- claim or recommendation;
- evidence;
- assumptions;
- confidence;
- risks;
- unresolved questions;
- suggested next action.

The synthesis record contains:

- decision or deliverable;
- rationale;
- alternatives considered;
- material dissent;
- confidence;
- validation performed;
- user decision;
- capture recommendation.

## 8. Memory and knowledge model

The system distinguishes:

- Fact: externally or user-verifiable statement.
- Preference: user-stated choice about interaction or output.
- Hypothesis: tentative explanation requiring validation.
- Observation: description grounded in specified evidence.
- Decision: selected option with owner, date, and rationale.
- Learning: validated conclusion from evidence or deliberate practice.
- Repertoire item: reusable concept, example, pattern, source, or technique.
- Rule: approved constraint on system behavior.
- Artifact: produced work product or structured record.

Every durable record includes:

- stable identifier;
- type;
- statement or content;
- source and provenance;
- creation and review dates;
- scope;
- sensitivity;
- confidence where applicable;
- status;
- related records;
- retention or review policy;
- approval metadata when required.

Allowed statuses are proposed, active, superseded, rejected, and archived.

Chat content is not durable memory by default. Capture must be purposeful. Sensitive records require the narrowest useful content and scope. Hypotheses and observations cannot be promoted to facts without evidence or explicit user confirmation.

## 9. Longitudinal observability

ThoughtOps observes artifacts and interactions, not the user's private mental state.

Initial dimensions are:

- technical reasoning;
- problem framing;
- decision quality;
- professional communication;
- audience adaptation;
- repertoire use;
- self-correction;
- collaboration effectiveness;
- autonomy and transfer of capability.

A longitudinal claim must cite concrete evidence and a comparison window. Reports include strengths, changes, regressions or uncertainties, counterexamples, and proposed experiments. Numerical scores are optional and prohibited unless the rubric, evidence, calibration, and uncertainty are visible.

Snapshots may be created at user-defined intervals. A quarterly review is recommended but not automatic in Foundation v1.

## 10. Professional communication and cultural adaptation

Communication work separates:

- correctness;
- clarity;
- assertiveness;
- structure;
- tone;
- audience adaptation;
- channel adaptation;
- translation;
- cultural adaptation;
- preservation of user voice.

The system must identify whether the task is editing, rewriting, coaching, translating, or adapting. It must not erase the user's authorship or make unsupported cultural generalizations.

For technical English, the system should explain material idiomatic, pragmatic, or register choices in Evolution mode. In Production mode it should prioritize the requested deliverable and surface only consequential ambiguities.

## 11. Quality gates

Before delivery, applicable gates check:

- factual grounding;
- technical correctness;
- logical coherence;
- explicit assumptions;
- preservation of intent;
- audience and channel fit;
- privacy and confidentiality;
- distinction between fact and inference;
- autonomy and authority boundaries;
- traceability of consequential recommendations;
- conformance to the requested format.

A gate may pass, pass with caveats, or fail. Failure must identify the missing evidence, conflict, or unsafe assumption. The system must not simulate validation it did not perform.

## 12. Error and uncertainty behavior

When context is insufficient, ThoughtOps should either ask a focused question or proceed with a bounded, labeled assumption. It must choose based on consequence and reversibility.

When sources disagree, the synthesis must expose the disagreement rather than collapse it into false certainty.

When a role output conflicts with the constitution, the constitutional invariant wins. When Core and Workspace conflict, the Workspace may specialize defaults but may not weaken autonomy, privacy, evidence, or authority invariants.

When the system cannot complete a requested action, it states the limitation and provides the most useful safe partial result.

## 13. Validation strategy

Foundation v1 is validated through:

- structural checks for required documents and fields;
- cross-reference checks between Core and Workspace;
- scenario reviews for Production and Evolution;
- privacy boundary tests;
- contradiction and placeholder scans;
- role-contract coverage;
- traceability checks;
- manual walkthroughs using neutral and personal scenarios.

Required acceptance scenarios include:

1. improving a technical message without changing intent;
2. adapting the same content for a peer and an executive;
3. analyzing a technical decision with critic and specialist disagreement;
4. producing work in Production and optional feedback in Evolution;
5. proposing, approving, correcting, and rejecting a memory;
6. creating a longitudinal observation with evidence and uncertainty;
7. preventing private Workspace content from entering Core;
8. operating without any assumed integration or background automation.

## 14. Initial deliverables

### Core deliverables

- README and getting-started guide
- manifesto
- ontology
- constitution
- system architecture
- role catalog
- mode specifications
- operational workflow
- memory and knowledge model
- longitudinal observability specification
- communication and cultural adaptation specification
- governance and privacy policy
- artifact schemas
- reusable templates
- neutral examples
- validation scenarios and review checklist
- architectural decision records
- changelog and roadmap

### Workspace deliverables

- private README and operating guide
- Core compatibility declaration
- user authority and identity record
- preferences and communication profile
- active goals and constraints
- repertoire index
- memory registry
- decision log
- Production and Evolution session templates
- longitudinal snapshot and review templates
- privacy classification guide
- initial configuration
- safe example session
- local changelog and roadmap

Personal records may be initialized only from explicit user statements in the source conversation. Any interpretation must remain proposed until confirmed.

## 15. Version and evolution

This release is Foundation v1. It is complete at the operational-contract level and intentionally portable. It is not the final product.

Potential future versions may include, only when requested:

- dashboards for evidence-backed longitudinal views;
- automatic validation and document generation;
- adapters for AI products and knowledge tools;
- retrieval and indexing;
- scheduled reviews;
- notification and workflow integrations;
- structured storage and query layers;
- orchestration of parallel role execution.

No future feature may bypass consent, provenance, privacy boundaries, or user authority.

## 16. Acceptance criteria

Foundation v1 is complete when:

- both repositories contain their assigned deliverables;
- Core contains no personal or proprietary information;
- Workspace clearly instantiates Core contracts;
- a user can run a Production session from intake to delivery;
- a user can run an Evolution session from evidence to an approved experiment;
- memory changes require appropriate approval;
- longitudinal claims require cited evidence and uncertainty;
- all internal links and contract references are coherent;
- no document claims an integration or automation that does not exist;
- validation scenarios have been manually reviewed;
- PRs document the design, checks, and known limitations;
- both PRs are merged into main.

