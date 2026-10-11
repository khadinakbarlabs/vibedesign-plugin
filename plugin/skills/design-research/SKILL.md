---
name: design-research
description: "Use to collect UI inspiration, app screenshots, public user reviews, or product feedback through Khadin Akbar's Apify Actors and the external Apify CLI, or to analyze supplied JSON/CSV exports. Produce source-linked research with confidence, sample limitations, and actionable design implications."
---

# Design research

Read the [work policy](../design/references/work-policy.md). Use the [Actor catalog](references/actor-catalog.json), [CLI workflow](references/apify-cli.md), [evidence contract](references/evidence-contract.md), and [input examples](references/inputs/README.md). Live collection needs the user's separately installed Apify CLI. Import analysis needs neither that CLI nor an Apify account.

## Choose evidence by question

- Visual composition or mood: Pinterest Data Extractor. Preserve original sources and rights; popularity is not usability proof.
- Mobile competitor screens and complaints: Apple App Store or Google Play. Set app, country, language, review sort, and bounded limits explicitly.
- Community pain points and vocabulary: Reddit Posts Search. Use public queries; exclude NSFW material and unnecessary author data.
- SaaS workflow complaints: Capterra Reviews. Prefer known public product URLs, bounded samples, and relevant recent reviews.
- Existing product evidence: supplied interviews, screenshots, analytics summaries, or exports. Analyze locally; do not upload them to Actors.

Choose the smallest useful source set. Read the live schema and pricing; bundled snapshots are dated reference material. Use catalog IDs, not a guessed Actor name. Current schema drift requires refreshing the input and estimate before execution.

## Workflow

1. Define the design question, target population, scope, and information needed. Separate assumptions from observations.
2. Choose live collection or import mode. In live mode, verify CLI capability, account, current schema, build, price, and budget. Prepare bounded input and run-options files before starting.
3. Explain which public targets go to Apify. Keep a local operation ledger with input fingerprint and selected build. Start only within current authorization. Do not blindly retry an ambiguous start.
4. Read the saved run's terminal status and output. Inspect actual record types and required fields, not just row count. Preserve retrieval date, source URL, locale, and version where available. An empty or failed run is an evidence gap.
5. Normalize relevant fields into the evidence contract. Remove duplicates using canonical source URLs or source IDs plus record type. Keep verbatim excerpts brief; use paraphrases and links by default. Do not retain reviewer profiles unnecessarily.
6. Group recurring friction by task stage: discovering value, starting, entering information, completing, recovering, and returning. Record the sample denominator, selection method, contrary evidence, and uncertainty.
7. Turn each supported finding into a specific design opportunity and an acceptance criterion. Prioritize severity, reach within the observed sample, and confidence separately. Never estimate population prevalence from a convenience sample.

## Output

Create `research.md` with the question, method, sources, collection dates, observed counts, findings, contradictions, confidence, and design implications. Create a normalized `evidence.json` only if it helps trace the findings. Use the [research template](references/research-template.md).

If usable evidence is absent, produce a proposed research plan and design hypotheses labeled as hypotheses. If live collection is blocked, use supplied exports or continue design offline. Offer one precise recovery step without launching more paid collection automatically.
