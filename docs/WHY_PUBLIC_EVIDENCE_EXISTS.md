# Why Public Evidence Exists

A common question is:

If the Protected Core remains protected, why publish evidence at all?

The answer is simple.

Claims are easy.

Evidence is harder.

---

## The Problem

Many technology projects ask observers to trust statements.

Trust the architecture.

Trust the implementation.

Trust the roadmap.

Trust the marketing.

Trust the claims.

VRP follows a different model.

---

## Observable Validation

The objective of public evidence is to allow external observers to evaluate observable behavior.

Public evidence may demonstrate:

- Recovery behavior
- Replay rejection
- Authority transitions
- Runtime continuity
- Partition recovery
- Transport migration
- Blackout recovery
- Execution preservation

The goal is to show what the system does.

Not necessarily how it does it.

---

## Evidence Over Explanation

A system should ultimately be judged by behavior.

Not presentation quality.

Not marketing quality.

Not slide decks.

Not promises.

Observable behavior is more valuable than explanation alone.

For this reason, validation artifacts are published whenever possible.

---

## What Public Evidence Provides

Public evidence allows independent observers to review:

- Validation reports
- Runtime logs
- Observable outcomes
- Rejection decisions
- Recovery results
- Evidence chains
- Validation summaries

This allows external review without requiring access to protected implementation details.

---

## What Public Evidence Does Not Provide

Public evidence is not intended to disclose:

- Protected algorithms
- Internal decision logic
- Proprietary implementation details
- Protected runtime mechanisms
- Protected architectural components

The purpose of evidence is verification.

The purpose of protection is preservation.

These objectives are not contradictory.

---

## The Boundary

VRP intentionally separates:

Observable Behavior

from

Protected Implementation

Observers should be able to evaluate outcomes without requiring disclosure of every internal mechanism.

This boundary is a deliberate design choice.

---

## Why Logs Matter

Logs are useful because they describe what happened.

They provide:

- Sequence
- Context
- Verdicts
- Outcomes

A replay rejection log demonstrates that a replay was rejected.

A recovery log demonstrates that recovery occurred.

A continuity log demonstrates that continuity was preserved.

The log does not need to expose every internal mechanism to be useful.

---

## Validation Philosophy

Public evidence exists to answer a specific question:

"Did the system behave correctly?"

It is not intended to answer every implementation question.

Some questions are answered through evidence.

Some questions remain inside the Protected Core boundary.

---

## Final Statement

Public evidence exists because behavior should be observable.

Protected Core exists because implementation should remain protected.

Both can exist simultaneously.

Public Evidence remains public.

Protected Core remains protected.