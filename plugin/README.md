# VibeDesign: UI UX Designer

![VibeDesign icon](assets/icon.png)

**UI/UX design for websites and apps, from evidence to developer handoff.**

VibeDesign helps founders, designers, and developers turn a product brief into clear user flows, wireframes, design systems, screen specifications, usable interface copy, and actionable accessibility reviews. It can also guide implementation in an existing project and verify the affected journey.

It is a **skills-only, CLI-based plugin**. Optional public design research uses Khadin Akbar's Apify Actors through the user's externally installed Apify CLI and account. Drafting and file-import workflows work without Apify. Live CLI research targets **Claude Code**; another host needs a compatible, verified local execution environment.

## What you can create

- A focused design brief and source-linked UX research.
- Competitor comparisons, onboarding journeys, navigation, and interaction states.
- Wireframes and concrete screen specifications with real copy and responsive rules.
- Design tokens, color/typography choices, component states, and usage rules.
- Implemented UI in your existing codebase when you request a build.
- Prioritized usability and accessibility findings with specific fixes and retests.
- A developer handoff connecting evidence, decisions, designs, and acceptance criteria.

Twelve focused skills route to the requested outcome. A one-screen fix stays focused; it does not require a complete product discovery process.

## Try it

```text
/vibedesign:design Design a simple appointment booking app for a neighborhood barber. Create flows and screen specifications first.
/vibedesign:design-audit Audit this dashboard and prioritize specific usability and responsive-layout improvements.
/vibedesign:design-research Prepare bounded public app-review and Pinterest research for our redesign. Show the inputs and cost estimate first.
```

You can also ask naturally: “Create an accessible design system for this app,” “Improve the empty and error states,” or “Package this design for a developer.”

## Install in Claude Code

From Claude Code, add this repository's marketplace and install VibeDesign:

```text
/plugin marketplace add khadinakbarlabs/vibedesign-plugin
/plugin install vibedesign@vibedesign-marketplace
```

For a local checkout, load the plugin folder using Claude Code's plugin-directory option. The source repository currently requires owner access while the release awaits approval; public installation becomes available after the publisher releases it.

## Optional public research

| Backend Actor | Design use |
| --- | --- |
| [Pinterest Data Extractor](https://apify.com/khadinakbar/pinterest-data-extractor) | Visual inspiration and original source links |
| [Apple App Store Scraper](https://apify.com/khadinakbar/apple-app-store-all-in-one-scraper) | iOS app metadata, screenshots, and reviews |
| [Google Play Scraper](https://apify.com/khadinakbar/google-play-all-in-one-scraper) | Android app metadata, screenshots, and reviews |
| [Reddit Posts Search](https://apify.com/khadinakbar/reddit-posts-search-scraper) | Public feedback and user vocabulary |
| [Capterra Reviews](https://apify.com/khadinakbar/capterra-reviews-scraper) | SaaS review complaints, pros, and cons |

Install and authenticate the Apify CLI separately using Apify's official instructions. VibeDesign checks available commands, the live Actor input schema, pricing, and current cost authorization before starting research. It prepares JSON input files and a local operation record, verifies the saved run and relevant output, and reconciles uncertain starts before retrying.

Optional runs can incur Actor, platform, proxy, and storage charges through your own Apify account. Result limits and event-charge caps are not unconditional all-in spending guarantees. Installing the plugin does not authorize spending or change your account plan.

No account is required to work from your own brief, screenshots, notes, or JSON/CSV exports. Empty research remains an evidence gap; the plugin does not invent interviews, review findings, or conversion improvements.

## Design reference ingredients

The curated local reference library includes 192 palette rows, 50 active styles, 74 font pairings, and 119 UX guidelines, plus product reasoning, landing-page, chart, and app-interface tables: **948 rows across nine tables**. These are pinned, licensed UI UX Pro Max reference data, not measured user research or accessibility certification.

Anthropic's frontend-design reference is included under its license. Impeccable's critique practices and wshobson's UI design patterns informed the original workflows. See [third-party attribution](THIRD-PARTY-NOTICES.md) and the provenance record for exact commits, files, hashes, and licenses. No upstream executable, installer, agent, or server is bundled.

## Project files and data handling

VibeDesign writes editable artifacts in your chosen project directory, typically `design/`. It reads relevant project material and processes supplied files through your AI host. Optional live research sends selected **public queries/URLs and run settings** to Apify and the source provider. Private design files, customer records, cookies, and credentials are excluded from Actor inputs.

The package runs no startup hooks, server, scheduler, or telemetry. It does not collect or store credentials. Your host and optional external services retain data according to their own settings and policies. See [privacy](PRIVACY.md), [terms](TERMS.md), [security](SECURITY.md), and [support](SUPPORT.md).

## Verification and limits

Screenshots can support visual observations; they cannot prove keyboard behavior or complete WCAG conformance. Accessibility reports identify what was tested and what remains untested. Prototype fixtures, implemented interactions, live integrations, and deployed behavior are reported separately.

Bundled Actor schemas and prices were read October 11, 2026 and must be refreshed before execution. Historical successful output fields were inspected; a new paid cloud canary was not started during packaging. Native package validation, host behavior tests, and directory review remain distinct checks. Approval and directory availability are reported only after they occur.

## License and publisher

Original VibeDesign work: MIT, Khadin Akbar. Third-party material retains its original license. This project is independent and is not endorsed by Anthropic, Apify, or the upstream reference authors.
