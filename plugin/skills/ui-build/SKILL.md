---
name: ui-build
description: "Use to implement a requested or approved website/app UI, prototype, component, or redesign in the user's existing codebase. Reuse the stack and design tokens, implement real interaction states, and verify the affected user journey and responsive behavior."
---

# UI implementation

Apply the [work policy](../design/references/work-policy.md). Read repository instructions, existing components, package versions, tests, and the approved/requested screen specification. User authorization to implement does not authorize deployment or publishing.

1. Inspect relevant files and uncommitted edits. Reuse the existing architecture and components. Make the smallest coherent change; do not replace the stack for a visual request.
2. Identify behavioral risks and acceptance criteria before editing. For changed behavior, write meaningful tests first where the project's tooling supports them. Cosmetic changes need visual inspection, not tests that mirror CSS values.
3. Use semantic elements and established accessible primitives. Implement keyboard/focus behavior, status feedback, loading, errors, empty states, long content, and mobile adaptation.
4. Keep tokens and responsive rules consistent with the design system. Use actual licensed/authorized assets. Do not automatically install packages or fetch fonts because a table recommends them. Inspect installed dependency documentation before using unfamiliar APIs.
5. Protect inputs and authorization boundaries; escape untrusted content, avoid injecting HTML, and keep secrets out of browser code and errors. Preserve existing security controls and backend behavior.
6. If a backend is absent, implement an explicitly labeled fixture/demo state. A functional-looking button must either perform a real authorized action or clearly explain the missing connection. Do not claim an API integration works from a mock.
7. Run appropriate existing checks and the affected flow. Inspect narrow and wide layouts, keyboard operation, reduced motion, zoom/long content, and relevant accessibility checks. Batch findings, fix them, and confirm the affected behavior.

Deliver the changed files and a concise implementation note: behavior, verification evidence, missing integrations, and remaining risks. Use the project's required review process. Mark deployment and live verification as separate actions.
