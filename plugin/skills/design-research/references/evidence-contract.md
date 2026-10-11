# Evidence contract

Every normalized observation needs:

- `id`: stable local ID.
- `sourceType`: pinterest, apple-app-store, google-play, reddit, capterra, supplied-file, screenshot, or observation.
- `sourceUrl`: public original URL where available; do not fabricate one.
- `collectedAt`: actual retrieval date or unknown.
- `sourceDate`: review/post/publication date or unknown.
- `locale`, `appVersion`, `recordType`: observed values or unknown.
- `observation`: short paraphrase; brief necessary excerpts only.
- `taskStage`: the affected user task or stage.
- `evidenceKind`: observed, measured, reported-by-user, inferred, or hypothesis.
- `confidence`: high, medium, or low with rationale.
- `designImplication`: concrete proposed response.
- `limitations`: missing context, convenience sample, promotional image, stale version, etc.

Optional run provenance can stay in the user's private operation ledger. Keep personal reviewer profiles and account identifiers out of shared reports.

Do not combine metadata and review records as if every row were a review. App screenshots provide visual references, not proof of actual navigation. Reddit feedback is self-selected; engagement is not prevalence. Pinterest inspiration is not permission to redistribute the image. Preserve contradictory evidence instead of selecting only complaints that support the intended redesign.

For themes, report unique relevant observation count and inspected denominator. Deduplicate by original source ID/URL and record type; do not count the same syndicated review twice. Never state that a sample percentage describes all users.
