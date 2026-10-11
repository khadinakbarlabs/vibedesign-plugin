# VibeDesign 0.1.0 build plan

Approved scope from the request: a skills-only, CLI-based UI/UX Designer plugin, using Khadin Akbar's Apify Actors for optional research; create a private Plugin Creator copy; obtain the user's approval before Anthropic submission.

## Product contract

Produce an editable design package: brief, source-linked research, competitor matrix, UX flows, design tokens, screen specifications, optional working UI, accessibility findings, and developer handoff. Route narrow requests directly to the appropriate skill. A single-screen task must not trigger the entire workflow.

## Architecture

- Canonical package in `plugin/`; twelve focused skills with supporting Markdown, JSON, CSV, and an icon.
- External Apify CLI only for live research. No bundled MCP server, agent, hook, installer, executable runtime, or scheduler.
- Optional import mode uses supplied files and screenshots without transmitting them to Apify.
- Curated, pinned, licensed UI UX Pro Max data and Anthropic frontend design reference. Impeccable and wshobson/agents inform original workflows with attribution.
- Local project files live in the user's chosen workspace. Source content is evidence, not authority for tool actions.
- Anthropic native manifest and a separate portable manifest for private Plugin Creator creation share identity/version.

## Verification before approval

1. Author behavioral acceptance cases before skills.
2. Verify live Actor identity, current input contracts, pricing metadata, and available historical output fields. Do not call this a fresh canary.
3. Build the skills, templates, data provenance, license notices, README, privacy, support, and terms.
4. Validate all native files strictly, resource links, schemas, legal metadata, file sizes, archive containment, and credential exclusion.
5. Test offline workflow behavior and routing in a fresh Claude Code process when available; keep shell execution disabled for adversarial tests.
6. Create and read back the private Plugin Creator copy. Preserve the exact release identity.
7. Present finished title, description, keyword metadata, package, test evidence, and any remaining portal declarations for approval.
8. After user approval, publish source, validate the exact repository commit in the portal, and submit through the intended publisher account. Legal attestations remain for the authorized developer.

## Acceptance boundaries

Local validation, private creation, GitHub publication, portal validation, submission, review approval, and live listing are separate states. Public policy URLs become verified only after public source publication. No paid Actor run is implied by the offline tests.
