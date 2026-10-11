---
name: design-audit
description: "Use to audit an existing website, app, dashboard, landing page, or screenshot for usability, visual hierarchy, consistency, task friction, edge states, and design quality. Produce prioritized findings with evidence, concrete fixes, and retest instructions."
---

# Design audit

Apply the [work policy](../design/references/work-policy.md). Use the [audit rubric](references/audit-rubric.md). For detailed accessibility checks, read [accessibility-review](../accessibility-review/SKILL.md).

1. Define the product, task, screens, devices, evidence available, and scope. Static screenshots support visible observations only; mark hidden interaction behavior untested.
2. Walk the primary journey from entry to successful result. Inspect navigation, hierarchy, affordances, content clarity, form effort, loading, empty, error, and recovery states.
3. Compare components and tokens across the supplied screens. Inspect typography, spacing, alignment, visual density, contrast, action prominence, and real content fit. Distinctive visual choices must support the task.
4. Inspect responsive behavior and keyboard use when an interactive product is available. Record viewport/device and test method. Do not invent measured defects from a visual guess.
5. Write findings with location, evidence, user consequence, severity, confidence, concrete fix, and retest. Separate blockers from polish. Avoid a numerical overall score unless the user requests one and the rubric is explicit.
6. Suggest the smallest useful repair order. If fixing is requested, implement the authorized scope, batch related defects, and retest affected behavior. Do not repeatedly redesign unaffected screens.

Deliver `audit.md` with prioritized findings and coverage limitations. State the main task risk first. Link actual screenshots or files where available and keep observed, inferred, and untested findings distinct.
