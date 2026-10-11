---
name: responsive-design
description: "Use to adapt websites or apps across phone, tablet, desktop, long content, enlarged text, and RTL layouts. Specify content-driven layout changes that preserve essential actions, data, navigation, and recovery behavior."
---

# Responsive adaptation

Apply the [work policy](../design/references/work-policy.md). Inspect actual content, task priority, existing breakpoints, and supported devices. Use the [accessibility reference](../accessibility-review/references/wcag-checks.md) for reflow and interaction requirements.

1. Rank content and actions by the user's task. Preserve essential functionality across sizes; avoid removing an action merely to simplify the appearance.
2. Choose breakpoints where content/layout stops working. Define behavior for navigation, grids, form groups, tables, charts, dialogs, and fixed/sticky controls.
3. For dense data, choose an understandable narrow-screen representation: prioritized columns, accessible horizontal scroll with cues, stacked records, or a detail view. Preserve selection, filtering, sorting, and actions.
4. Handle long translated labels, enlarged text, safe areas, virtual keyboards, reduced motion, landscape, and RTL. Use logical layout properties where supported; mirror navigation deliberately rather than indiscriminately reversing everything.
5. Check a representative narrow, intermediate, and wide viewport and a long-content/zoom scenario. Test actual overflow, target sizes, and content order when implementing. Label untested rules as proposed.

Deliver a layout transition table with viewport/content trigger, component change, retained actions, rationale, and verification. Include specific fixes for observed overflow and focus/keyboard issues. Do not claim device coverage beyond the actual checks.
