# HackerRank Orchestrate — September 2026

Competition workspace for the September 2026 HackerRank Orchestrate challenge.

## Status
The September problem statement and dataset are intentionally not committed until the competition release. This repository is prepared for rapid, evidence-driven implementation once the official challenge arrives.

## Default working strategy

```text
Input
  ↓
Deterministic normalization
  ↓
Bounded agent
  ↓
Narrow tools
  ↓
Structured evidence / facts
  ↓
Deterministic policy
  ↓
Schema validation
  ↓
Safety gate
  ↓
Output
```

This is a starting hypothesis, not a commitment. Adapt it to the released task and measured evidence.

## Layout
- `AGENTS.md` — Codex/contributor operating rules
- `src/` — application and agent implementation
- `tests/` — unit, integration, adversarial, regression tests
- `eval/` — evaluation harness and metrics
- `scripts/` — repeatable commands
- `data/` — permitted fixtures/schema notes only
- `docs/architecture.md` — architecture notes
- `docs/decisions.md` — decision log
- `docs/failure-modes.md` — failures and mitigations
- `docs/judge-prep.md` — AI Judge preparation

## First action after challenge release
Do not immediately implement. Extract the problem contract, enumerate candidate architectures, identify failure modes, and build the smallest testable baseline.

## Integrity
Only original, rule-compliant work belongs here. Never fabricate evaluation results or capabilities.
