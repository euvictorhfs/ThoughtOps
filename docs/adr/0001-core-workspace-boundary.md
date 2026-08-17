# ADR-0001 — Separate public Core and private Workspace

Status: Accepted  
Date: 2026-08-16

## Context

Reusable system contracts and personal professional context have different privacy and evolution needs.

## Decision

Core owns model-agnostic public contracts. Workspace privately instantiates them for one user. Data flows from Workspace to Core only through explicit anonymized promotion.

## Alternatives

One repository was rejected because it risks disclosure and couples reusable design to one identity. Tool-only storage was rejected because conversations and product memory are not a durable, reviewable source of truth.

## Consequences

Two repositories require compatibility tracking and manual synchronization, but create a clear privacy and ownership boundary.
