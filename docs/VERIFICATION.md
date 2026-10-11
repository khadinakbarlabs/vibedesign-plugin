# VibeDesign verification

Version 0.1.3; October 11, 2026.

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

The publisher approved public source release and Anthropic submission on October 11, 2026. Source publication and portal results are recorded only after they occur. The Anthropic source form identified the repository as private and displayed an agreement before uploading private source for scanning; that agreement was not accepted. The portal draft contains the repository and `plugin/` path. Validation and submission must be recorded from the actual final source commit. Public policy URLs are not verified while the repository is private.

Actor identity, schema, pricing, and historical successful output fields were read live. These checks do not establish a fresh cloud canary. Public-source reachability, host behavior, portal scan, submission, review, and directory availability remain separate later checks.
