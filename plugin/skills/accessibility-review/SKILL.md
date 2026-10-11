---
name: accessibility-review
description: "Use to evaluate interface accessibility, WCAG 2.2 concerns, keyboard navigation, screen-reader semantics, focus, contrast, touch targets, forms, reduced motion, and zoom/RTL behavior. Report observed failures separately from checks that need an interactive product or assistive technology."
---

# Accessibility review

Apply the [work policy](../design/references/work-policy.md). Read the [WCAG checks](references/wcag-checks.md). Match the review to the requested platform and standard; do not certify full conformance from screenshots or one automated tool.

1. Inventory available evidence: static image, rendered UI, source, DOM/accessibility tree, keyboard tests, assistive technology, and automated results. Define coverage and limitations.
2. Inspect semantic structure, headings, landmarks, labels, accessible names, status messages, error association, and alternatives for media.
3. Test keyboard access, order, visible focus, traps, modal focus management, dismissal, and focus restoration where an interactive interface is available.
4. Measure actual contrast and target sizes. Check color-independent status cues and focus visibility. Label visual estimates as estimates. Apply the correct criterion and exceptions.
5. Check zoom, text resizing, reflow, orientation, pointer/touch alternatives, reduced motion, and non-drag operation. Check long translated labels and RTL where applicable.
6. Use a screen reader and relevant platform checks when available. If unavailable, describe the exact manual tests needed. Automated results supplement manual checks.
7. Record each finding with criterion, evidence, method, consequence, fix, and retest. Distinguish confirmed failure, potential issue, and not tested. Implement and retest authorized fixes.

Deliver a scoped accessibility report with tested conditions, results, unresolved checks, and practical repair order. State that design guidance and test evidence do not establish legal certification or complete WCAG conformance.
