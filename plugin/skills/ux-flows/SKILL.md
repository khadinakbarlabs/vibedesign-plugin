---
name: ux-flows
description: "Use to design user journeys, navigation, information architecture, onboarding, forms, checkout, task flows, and interaction states. Create editable flows and screen-state tables covering success, empty, loading, error, cancellation, and returning users."
---

# UX flows

Apply the [work policy](../design/references/work-policy.md). Read the brief and research that exist. Use the [flow template](references/flow-template.md).

1. State the user's task, entry condition, successful end condition, and non-goals. Explain the first useful result and how users reach it.
2. Inventory necessary actions and information. Organize navigation around familiar user concepts. Keep primary actions visible and related choices together.
3. Map the shortest understandable happy path. Reduce unnecessary input and decisions without concealing price, consent, requirements, or consequences.
4. Add realistic branches: permission denied, offline, invalid input, no results, partial completion, stale data, returning user, back navigation, abandonment, and cancellation.
5. Specify state transitions: trigger, visible response, what persists, what is reversible, and the next recovery action. Destructive actions need clear consequences and an appropriate recovery or confirmation pattern.
6. Define accessibility behavior: focus movement, keyboard order, labels, status announcements, and alternatives to drag-only interactions.
7. Walk through the flow with sample tasks. Label these walkthroughs as design checks, not user research. Record friction and revise before visual polish.

Deliver `flows.md` with a Mermaid diagram when it clarifies the journey, a screen-state table, navigation model, and testable acceptance criteria. Add exact screen IDs for links into the screen specification. Distinguish proposed behavior from observed product behavior.
