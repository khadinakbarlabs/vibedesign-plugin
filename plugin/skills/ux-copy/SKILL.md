---
name: ux-copy
description: "Use to write or improve interface labels, buttons, onboarding, form instructions, validation errors, notifications, empty states, and recovery messages. Produce concise, consistent UX copy with accessible context and localization guidance."
---

# UX copy

Apply the [work policy](../design/references/work-policy.md). Read the task flow, actual product behavior, brand voice, and content constraints. Reuse user vocabulary from evidence without copying identifiable reviews.

1. Define the action or information each message must communicate. Use familiar names and active verbs. Preserve consistent vocabulary through buttons, states, and confirmations.
2. Make calls to action predict their consequence. Explain price, permissions, destructive effects, and irreversible changes clearly. Avoid false urgency, hidden commitments, and manipulative defaults.
3. For errors, say what happened and the next useful action. Distinguish invalid input, authorization failure, unavailable service, and empty results. Do not expose stack traces or private implementation details.
4. For empty states, explain the user's next step. For progress, describe real state without invented completion times. For success, say what changed and where it can be found.
5. Ensure labels survive long translations, enlarged text, and RTL. Use complete translatable strings, avoid concatenated fragments, and specify locale-sensitive numbers/dates. Do not certify translations without a qualified check.
6. Specify accessible labels and live-region announcements where visible text alone is insufficient. Avoid redundant screen-reader content.

Deliver `copy.md` as a table: screen/state ID, element, final text, condition, accessible name/announcement, rationale, and localization notes. Match messages to real behavior; do not promise a recovery the product cannot provide.
