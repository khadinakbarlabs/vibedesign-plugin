# VibeDesign verification

Version 0.1.3; updated October 12, 2026.

## Completed local checks

- Native Anthropic manifest and repository marketplace: strict Claude Code validation passed with zero errors/warnings. The native manifest was also checked from the extracted final Claude archive.
- Plugin Builder 0.2.1 private-adapter validation passed from source staging and extracted archive. This is a local Codex package check, not a public-submission or Anthropic approval result.
- Builder's conservative Claude component profile passed: twelve skills, zero commands, zero agents. Its thresholds are local guidance, not vendor limits.
- Fifty-six package checks and twelve Skill Creator frontmatter checks passed on 0.1.1: discovery metadata, resource containment, JSON parsing, listing constraints, document/license completeness, nine pinned upstream data hashes and 948 rows, bounded Actor examples, PNG dimensions, composition, and credential/local-path exclusion.
- Version 0.1.2 preserved private-preview publisher metadata and synchronizes release versions. Affected manifest and archive checks were rerun. Skills and reference resources are unchanged from 0.1.1. Version 0.1.3 updates only release metadata, changelog and public-installation wording; affected native/marketplace/private manifests and extracted archives passed again.
- Final Claude archive: 59 files. Final private Plugin Creator archive: 72 files, including twelve OpenAI skill presentation metadata files. Both archives were compared byte-for-byte against their source editions, checked for containment and symlinks, and extracted for validation. Required licensing and attribution are included.
- PNG icon: square 1254 by 1254, 1,248,520 bytes.
- Claude archive SHA-256: `d166c6c0d66606e81eb7e8aea312ab278fb01482f1f3e6a50d3d018da12e11c3`.
- Private adapter archive SHA-256: `20f25f9df80909e084c679cb1517847593d3f2b5f55a6d2e54a9c200fee16a71`.

The native strict command validates the manifest; its empty contents report is not counted as skill validation. See `reports/release-checks-0.1.3.json`, `reports/package-checks.json`, `reports/skill-creator-validation.json`, and `docs/BUILDER-REVIEW.md` for scope and limitations. Historical reports remain historical evidence, not the final archive specification.

## Saved private preview

Plugin Creator saved the existing private VibeDesign plugin at 0.1.3, preserving its identity and audience. Readback found all twelve skills and all 72 expected files; the Anthropic manifest is absent from this private edition. The 0.1.2 readback verified eighteen changed/new text resources. The 0.1.3 readback verified its four updated manifest/documentation resources. Both manifests matched semantically, with original publisher fields and starter prompts preserved. The saved release was checked after the guarded update.

The private preview, public source release, and Anthropic submission are distinct states. File inventory/readback do not establish model behavior. The binary icon was verified in the uploaded archive; saved inventory confirms presence/size, not an independent saved binary comparison.

## Host behavior

A restricted Claude Code invocation originally failed to authenticate before any test ran. A fresh authentication-status check now reports signed out. No model behavior case passed or failed. Sixteen synthetic cases cover design routes, imports, adversarial content, empty output, uncertain paid starts, continuation, and nearby requests that should select another workflow. They are defined, not executed. No new paid Actor canary was run.

## Source and directory

The publisher approved the package, listing, public source release and Anthropic submission on October 11, 2026. The repository is public, and GitHub release v0.1.3 targets commit `0b38afafd0e60c0feb9e0095d9ff2e6571a0b6df`. Unauthenticated source/policy fetches matched the local files. Both public release assets were downloaded without authentication and matched their recorded hashes.

Anthropic's portal validated the exact v0.1.3 tag at that commit: seven source checks passed, twelve skills were detected, no MCP servers were found, and five non-blocking warnings concern directory-only metadata fields. The portal states no action is required for the documentation, privacy, support, terms and icon fields. This is source validation, not the later security/policy compliance scan.

The submitted listing targets Claude Code only. Data handling discloses reading/storing possible public-review personal data, optional external transmission documented in README, and retention longer than 30 days because user-controlled project files/Apify datasets can persist until deletion. VibeDesign operates no separate project-data service. The plugin is not targeted at children. Later automatic publication is off; source checks are scheduled, with no new GitHub webhook credential.

On October 12, 2026 the publisher explicitly approved acceptance of the displayed Directory Terms/Policy, the declared execution acknowledgement and final submission. All four compliance acknowledgements were checked. The external Apify CLI use remains disclosed in the source/listing; the execution declaration was confirmed by the publisher.

The portal displayed **Plugin submitted for review** and created the submission record. Its Versions view matches v0.1.3 at the exact release commit. Received and source validation are done; the security scan is running. Reviewer approval and Live have not been reached.

The scan was started, but no completed security/policy scan, reviewer approval or live directory availability is claimed. Actor identity/schema/pricing/historical-output inspection remains separate from a fresh paid cloud canary; Claude Code host behavior remains untested because its CLI is signed out. See `reports/public-source-reachability.json`, `reports/public-release-readback.json`, `reports/anthropic-draft-validation.json` (historical draft), and `reports/anthropic-submission.json` (current submitted state).
