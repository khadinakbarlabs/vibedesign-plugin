# VibeDesign verification

Version 0.1.2; October 11, 2026.

## Completed local checks

- Native Anthropic manifest and repository marketplace: strict Claude Code validation passed with zero errors/warnings. The native manifest was also checked from the extracted final Claude archive.
- Plugin Builder 0.2.1 private-adapter validation passed from source staging and extracted archive. This is a local Codex package check, not a public-submission or Anthropic approval result.
- Builder's conservative Claude component profile passed: twelve skills, zero commands, zero agents. Its thresholds are local guidance, not vendor limits.
- Fifty-six package checks and twelve Skill Creator frontmatter checks passed on 0.1.1: discovery metadata, resource containment, JSON parsing, listing constraints, document/license completeness, nine pinned upstream data hashes and 948 rows, bounded Actor examples, PNG dimensions, composition, and credential/local-path exclusion.
- Version 0.1.2 preserves private-preview publisher metadata and synchronizes release versions. Affected manifest and archive checks were rerun. Skills and reference resources are unchanged from 0.1.1.
- Final Claude archive: 59 files. Final private Plugin Creator archive: 72 files, including twelve OpenAI skill presentation metadata files. Both archives were compared byte-for-byte against their source editions, checked for containment and symlinks, and extracted for validation. Required licensing and attribution are included.
- PNG icon: square 1254 by 1254, 1,248,520 bytes.
- Claude archive SHA-256: `10d9fa1fb6c90512b72cbb399929985676ffd9645b8734a2c3f51cc445588a7b`.
- Private adapter archive SHA-256: `8b8345220b3396a5e3eb526bcd205eb158dcabac885830c3f8cfd43bfc8b51c9`.

The native strict command validates the manifest; its empty contents report is not counted as skill validation. See `reports/release-checks-0.1.2.json`, `reports/package-checks.json`, `reports/skill-creator-validation.json`, and `docs/BUILDER-REVIEW.md` for scope and limitations. Historical reports remain historical evidence, not the final archive specification.

## Saved private preview

Plugin Creator saved the existing private VibeDesign plugin at 0.1.2, preserving its identity and audience. Readback found all twelve skills and all 72 expected files; the Anthropic manifest is absent from this private edition. Eighteen changed/new text resources matched exactly. Both manifests matched semantically, with original publisher fields and starter prompts preserved. The saved release was checked after the guarded update.

The private preview, public source release, and Anthropic submission are distinct states. File inventory/readback do not establish model behavior. The binary icon was verified in the uploaded archive; saved inventory confirms presence/size, not an independent saved binary comparison.

## Host behavior

A restricted Claude Code invocation originally failed to authenticate before any test ran. A fresh authentication-status check now reports signed out. No model behavior case passed or failed. Sixteen synthetic cases cover design routes, imports, adversarial content, empty output, uncertain paid starts, continuation, and nearby requests that should select another workflow. They are defined, not executed. No new paid Actor canary was run.

## Source and directory

The source repository is private under the user's existing GitHub identity. Public release awaits the user's requested approval. The Anthropic source form identified the repository as private and displayed an agreement before uploading private source for scanning; that agreement was not accepted. The portal draft contains the repository and `plugin/` path. Validation and submission must be recorded from the actual final source commit after approval. Public policy URLs are not verified while the repository is private.

Actor identity, schema, pricing, and historical successful output fields were read live. These checks do not establish a fresh cloud canary. Public-source reachability, host behavior, portal scan, submission, review, and directory availability remain separate later checks.
