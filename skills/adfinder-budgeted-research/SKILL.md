---
name: adfinder-budgeted-research
description: Plan and carry out multi-step AdFinder research and pagination within one explicit maximum credit budget.
---

Read [the tool-use guide](../../TOOL-CONTRACT.md) before using AdFinder tools.

Establish the question, source priority, stopping point and maximum credits. A displayed wallet is not a spending budget. Discover and describe only relevant registered capabilities, then estimate every planned dependent step/page, in batches of at most 20. Unknown or unbounded costs block execution. Reuse an existing approval covering the plan rather than requesting it again.

Use one UUID budgetId and fixed integer maxCredits (1–1,000) across the entire approved research. Give each new logical request/page a new UUID requestId; an uncertain retry preserves all original arguments and identity. An alternate execution entry point is still the same request. Do not split budgets or create a fresh identity to evade limits or recover a response.

Track server-reported charges and remaining allowance. Stop at sufficient coverage, agreed cap, exhausted or repeated/missing cursors, insufficient funds or unresolved state. Report partial results and uncertain charges honestly. Saved-result display is free and uses the original request once for an entire ad result; it does not authorize another paid page. Finish with sources, completed/incomplete coverage and actual charges, without initiating checkout or promoting purchases.
