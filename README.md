# VibeDesign: UI UX Designer

![VibeDesign icon](plugin/assets/icon.png)

VibeDesign is a skills-only, CLI-based UI/UX design plugin for Claude Code. Turn a brief into source-linked research, competitor analysis, user flows, wireframes, design systems, accessible screen specifications, optional implemented UI, and a developer handoff. Optional live research uses Khadin Akbar's Apify Actors through the user's own external CLI account; offline work accepts supplied files and screenshots.

See the [complete plugin guide](plugin/README.md), [privacy policy](plugin/PRIVACY.md), [support](plugin/SUPPORT.md), [terms](plugin/TERMS.md), and [third-party notices](plugin/THIRD-PARTY-NOTICES.md).

The canonical installable package is in `plugin/`. The root marketplace exposes one plugin, `vibedesign`. Twelve focused skills and 948 pinned reference rows supply the workflow and design ingredients. There is no bundled MCP server, hook, agent, installer, runtime binary, or scheduler.

Release 0.1.3 is the publisher-approved public release. Plugin Builder was used to refine the existing package and export separate Anthropic and private Plugin Creator editions from the same skills corpus. The private adapter is in `adapters/plugin-creator/`; it supplies presentation metadata rather than another implementation.

Public release, directory validation, submission, review approval, and listing availability are separate states. The [approval packet](docs/APPROVAL.md) records the approved listing and release scope; [verification evidence](docs/VERIFICATION.md) and [Plugin Builder review](docs/BUILDER-REVIEW.md) record checks actually completed.

The [v0.1.3 public release](https://github.com/khadinakbarlabs/vibedesign-plugin/releases/tag/v0.1.3) includes the native Claude archive and checksum. VibeDesign v0.1.3 was submitted to Anthropic on October 12, 2026 after publisher approval. Source validation passed; the scan passed with directory policy warnings, publication was requested, and Anthropic reviewer approval remains pending. The directory listing is not live.
