# Accessibility checks

Use current primary guidance when precision matters: [WCAG 2.2 quick reference](https://www.w3.org/WAI/WCAG22/quickref/), [target size minimum](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html), and [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/). These links were checked October 11, 2026. Native interfaces also need the target platform's current accessibility guidance.

For WCAG 2.2 AA, ordinary text contrast is generally at least 4.5:1; large text can use 3:1 under the criterion's defined size/weight conditions. Relevant controls and graphical objects generally need 3:1 against adjacent colors. Test actual rendered pairs, including important interactive states. Exceptions and scope matter.

SC 2.5.8 uses 24 by 24 CSS pixels or its stated spacing/equivalent/inline/user-agent/essential exceptions. Aiming for larger touch targets, often around 44–48 depending on the platform, is useful product guidance; it is not the WCAG AA minimum.

Check keyboard operation and logical focus; focus visibility and obscuration; semantic names/roles/values; labels and errors; status announcements; alternatives for non-text content; reflow and text resize; reduced motion; and alternatives to drag-only actions. Record the method, viewport, device, browser, theme, and relevant state for each result.

Do not infer CSS-pixel dimensions, semantic correctness, keyboard behavior, screen-reader usability, or full conformance from a screenshot. Automated scanners find only part of the issues. A heuristic finding is a useful hypothesis until the relevant behavior is tested.
