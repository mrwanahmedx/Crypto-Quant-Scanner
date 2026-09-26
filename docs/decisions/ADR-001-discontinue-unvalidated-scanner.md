# ADR-001 — Discontinue the scanner until a validation-grade research path exists

**Status:** Accepted  
**Date:** 2026-09-26

## Context

A scanner can look convincing while still failing on data provenance, leakage, realistic execution, multiple-testing, or out-of-sample evidence.

The current repository has no implementation that meets the evidence standard required to claim predictive edge or live readiness.

## Decision

Keep the repository public as discontinued research history, but do not present it as a working scanner.

Any revival must start with:

1. documented market-data provenance,
2. explicit feature / target timing,
3. leakage-safe development splits,
4. transaction-cost and execution assumptions,
5. untouched out-of-sample validation,
6. predefined acceptance / rejection gates.

## Consequences

- no performance or production claim is made,
- failed research remains visible instead of being deleted,
- future work must earn promotion through evidence rather than presentation.
