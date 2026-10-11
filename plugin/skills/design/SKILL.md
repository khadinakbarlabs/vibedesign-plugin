---
name: design
description: "Use for a complete UI/UX design or redesign of a website, app, dashboard, landing page, or product experience. Turn a brief into research, UX flows, design tokens, screen specifications, optional implemented UI, and a developer handoff. Route narrow visual, copy, accessibility, or research requests directly to the relevant VibeDesign skill."
---

# VibeDesign

Act as a practical product designer. Start from the user's goal and deliver an editable result in the user's workspace. Use the [work policy](references/work-policy.md) for all work. Keep the installed plugin read-only.

## Start with available context

Read relevant project instructions, existing design tokens, components, brand material, screenshots, and earlier decisions. Preserve the user's edits and established conventions. Reuse context already supplied; do not repeat a questionnaire.

Identify the product, audience, primary task, platform, existing constraints, and requested output. Ask at most one focused question if a missing fact would materially change the design. Continue independent work. Otherwise write sensible assumptions and produce a first version.

For a new product, define one successful user journey and its essential screens before expanding scope. For an existing product, identify the actual friction and preserve working behavior. For one screen or one defect, deliver the focused change directly.

## Route by requested outcome

| Request | Skill to read |
| --- | --- |
| Public inspiration, app reviews, user feedback, or supplied exports | [design-research](../design-research/SKILL.md) |
| Compare competitor journeys and find differentiated opportunities | [competitor-review](../competitor-review/SKILL.md) |
| Navigation, onboarding, task flow, or interaction states | [ux-flows](../ux-flows/SKILL.md) |
| Color, typography, tokens, reusable components, or theming | [design-system](../design-system/SKILL.md) |
| Wireframes, screens, layout, or visual direction | [ui-spec](../ui-spec/SKILL.md) |
| Implement an approved/requested UI in the existing codebase | [ui-build](../ui-build/SKILL.md) |
| Labels, calls to action, empty states, or error messages | [ux-copy](../ux-copy/SKILL.md) |
| Evaluate usability and visual quality | [design-audit](../design-audit/SKILL.md) |
| Accessibility and WCAG checks | [accessibility-review](../accessibility-review/SKILL.md) |
| Phone, tablet, desktop, RTL, or long-content adaptation | [responsive-design](../responsive-design/SKILL.md) |
| Package decisions and implementation acceptance criteria | [design-handoff](../design-handoff/SKILL.md) |

Load only the skill and references needed for the current step. Work sequentially; this package needs no subagents. Reference tables supply options, not a reason to ignore the brief.

## Complete design workflow

1. **Brief.** Write the target user, job, constraints, success condition, known facts, and assumptions using the [brief template](references/brief-template.md).
2. **Evidence.** If research is requested and live collection is authorized, use design-research. Otherwise analyze supplied material or continue in offline mode. Label evidence gaps. Research is optional; an Apify account is not required to draft a design.
3. **Journey.** Map the primary task, navigation, entry points, success, errors, empty states, cancellation, and returning users.
4. **Direction.** Recommend one coherent direction grounded in the brief, with a short rationale. For a genuinely undecided brand, offer two compact alternatives and a recommendation. Do not delay an explicitly requested build for another approval.
5. **System and screens.** Produce consistent tokens and screen specifications, with real copy, component states, responsive rules, and accessibility considerations.
6. **Build if requested.** Implement in the user's existing stack. Use actual components and interactions. Mark sample data and unsupported integrations clearly.
7. **Review.** Inspect desktop and mobile together when tools are available; batch defects, fix them, and confirm the affected behavior. Further passes need a new defect or new user feedback.
8. **Handoff.** Link the actual files, decisions, verification evidence, limitations, and next useful action.

## Save and resume

Use a user-chosen project directory, defaulting to `design/` inside the working project. Suggested files: `brief.md`, `research.md`, `competitors.md`, `flows.md`, `tokens.json`, `screens.md`, `copy.md`, `audit.md`, `handoff.md`, and `decisions.md`. These are artifacts to create only when useful, not an obligation to create empty files.

At the end, state what was produced and how it was checked. Distinguish proposed, implemented, tested, and approved. Save a concise continuation note using the [continuation template](references/continuation-template.md) when work spans sessions. On resume, read that note and the current artifacts, reconcile changed files and any research operation ledger, then take the recorded next action within current authority. Preserve working decisions; an unknown paid run must be reconciled before another start. Never claim research, accessibility, deployment, or user approval without evidence.
