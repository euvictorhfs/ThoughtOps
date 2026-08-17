# ADR-0002 — Model cognitive specialists as composable roles

Status: Accepted  
Date: 2026-08-16

## Context

Different tasks need technical, communication, critical, historical and metacognitive perspectives. Requiring one autonomous agent per perspective would couple the framework to a runtime.

## Decision

Define roles as contracts. An adapter may execute them in one model, sequentially or in parallel. Material dissent must remain visible to synthesis.

## Consequences

ThoughtOps remains portable. Adapters must not pretend independent review occurred when it did not.
