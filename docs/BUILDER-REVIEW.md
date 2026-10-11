# Plugin Builder review

Applied the installed Plugin Builder 0.2.1 on October 11, 2026 to the existing VibeDesign project. The requested architecture remains skills-only, with an external Apify CLI for optional public research.

## Improvements

1. Kept the canonical Anthropic package in `plugin/`. Moved the portable manifest and OpenAI presentation metadata into `adapters/plugin-creator/`. Both editions reuse the same twelve skill bodies and contained resources.
2. Exported separate Claude and private Plugin Creator archives using Builder's bundle command. Its default allowlist omitted this project's changelog, attribution, and two upstream license files. Those candidates were rejected for resource closure, then finalized with an explicit four-file allowlist extension. Builder source was not modified. Final archives retain all required content and the intended provider metadata.
3. Added a security reporting guide and continuation template. Resume reads current artifacts, preserves accepted decisions, and reconciles unknown research operations before another paid start.
4. Clarified that imports need no Apify account or CLI, while live collection needs the user's installed CLI.
5. Added twelve OpenAI presentation metadata files to the private adapter only. Claude's skill discovery remains native.
6. Expanded the planned synthetic acceptance corpus to sixteen cases, including missing CLI, continuation, and nearby non-design requests. These are planned cases, not executed model evaluations.
7. Read back the private preview after its update. A publisher field omitted by the initial update was restored; final 0.1.2 readback preserves publisher metadata and every starter prompt.

## Executed checks and tool limits

Builder `component-budget`, `validate`, `bundles`, and `graph` were used. The decision graph was extended with actual controls, executed checks, blocked host cases, and independent destination gates; `platform-matrix.json` records each observed state. The private validation report passed without errors/warnings. Both final archives were compared with their source editions and validated after extraction. Claude's native strict validator and Skill Creator's twelve frontmatter checks passed. Package resource, provenance, metadata, composition, and credential checks passed.

Builder's `release-validate` implementation in this installed version is a self-audit hard-coded to the Plugin Builder package name and its six-platform/npm runtime files. It was inspected and not applied as a VibeDesign release verdict. npm, Cursor, and unrelated marketplace publication are outside this request. OpenAI public-submission requirements are separate from this private-preview/Anthropic scope.

The installed Plugin Creator package contains no standalone `validate_plugin.py`; its source/readback tools, successful private update, Builder validation, and separate package checks provide the evidence used here. No independent reviewer or subagent was run. Static/manual guidance review does not establish selection precision or completed model outcomes.

## Remaining checks

- Claude Code host evaluation: blocked by sign-in; no behavioral pass is claimed.
- New paid Actor canary: not run; only read-only provider qualification was authorized during packaging.
- Public source/policy reachability: pending the user's requested release approval.
- Anthropic portal validation and submission: pending approval and applicable host/release prerequisites.
- Vendor review and public availability: not observed.

Native packaging rules were refreshed against [Anthropic's manifest reference](https://code.claude.com/docs/en/plugins-reference) and [pre-submission checklist](https://claude.com/docs/plugins/pre-submission-checklist). Builder's local conservative component thresholds are not official platform maxima.
