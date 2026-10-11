---
name: ui-spec
description: "Use for wireframes, screen designs, page layouts, component specifications, visual hierarchy, or a focused UI redesign. Produce concrete editable screen specifications with realistic copy, component states, responsive behavior, and implementation acceptance criteria."
---

# UI specification

Apply the [work policy](../design/references/work-policy.md). Read the [screen template](references/screen-template.md) and relevant existing design tokens. Consult [frontend design craft](references/frontend-design.md) for visual direction; its example aesthetics do not override the user's brief.

1. Define the screen's user task, primary action, required content, constraints, and links into the task flow. Reuse the brief rather than restarting discovery.
2. Compose a clear information hierarchy. Choose grouping, alignment, width, type scale, spacing, and progressive disclosure based on the actual task. Use real domain language and content lengths.
3. Draw an editable wireframe using the host's available design tools, HTML/CSS, or a compact text layout. Label fidelity and behavior. A picture is a visual concept; a state specification defines interaction.
4. Specify actual components and token references, not vague adjectives. Include default, loading, empty, error, success, focus, disabled, overflow, and long-content behavior as relevant.
5. Define responsive rules and accessible semantics. Explain where navigation, tables, forms, and key actions move on narrow screens. Preserve essential functionality.
6. For a fresh direction, explain one distinctive choice tied to the product. Keep decorative additions subordinate to the task. When revising an existing screen, preserve brand and working behavior unless the user requests a broader change.
7. Review the primary path and meaningful edge cases. Record what was measured, visually inspected, or still proposed. Implement when the user requested implementation; do not insert a redundant approval gate.

Deliver `screens.md` or an editable visual artifact with screen IDs, layouts, content, component references, states, accessibility, responsive behavior, and acceptance criteria. If the user wants a working prototype, route to [ui-build](../ui-build/SKILL.md).
