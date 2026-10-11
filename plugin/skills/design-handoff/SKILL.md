---
name: design-handoff
description: "Use to package a UI/UX design for implementation or continuation. Connect the brief, evidence, flows, tokens, screens, copy, decisions, accessibility findings, and acceptance criteria in a concise developer handoff with clear verified and unresolved states."
---

# Design handoff

Apply the [work policy](../design/references/work-policy.md). Read the actual artifacts and decisions. Do not create missing research or mark unrun checks complete.

1. State the user task, final scope, chosen direction, constraints, and current version.
2. Link existing files: brief, research, competitor matrix, flows, tokens, screens, copy, implementation, and audit. Omit artifacts that were not needed.
3. Connect screen IDs to component/token references, content, states, accessibility behavior, data contracts, responsive rules, and acceptance criteria.
4. Record decision rationale and source evidence. Preserve explicit human decisions and mark assumptions. Do not treat previous approval as approval of later material changes.
5. List verification by method and result: static validation, rendered inspection, keyboard checks, unit/integration/e2e behavior, and external-service checks as applicable. Separate proposed, implemented, tested, approved, deployed, and live.
6. Order unresolved work by impact and dependency. Name the next useful action and its concrete required input, if any.

Deliver `handoff.md` and update `decisions.md` only when a durable decision needs recording. Keep it concise enough that another developer or a later session can resume without reading the chat. Exclude secrets, personal reviewer data, private account identifiers, and raw logs.
