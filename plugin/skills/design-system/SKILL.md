---
name: design-system
description: "Use to create or refine design systems, accessible color palettes, typography, spacing, themes, design tokens, and reusable component rules for websites and apps. Consult a curated local design reference library and export editable tokens with rationale."
---

# Design system

Apply the [work policy](../design/references/work-policy.md). Preserve existing brand and component conventions. Read the [reference library guide](references/library.md) and [token contract](references/token-contract.md). Use the [accessibility reference](../accessibility-review/references/wcag-checks.md) when evaluating contrast and targets.

1. Identify the product category, audience, task density, brand, supported platforms, languages, and existing constraints. A calm finance tool and an expressive music experience need different choices.
2. Search only relevant rows in the curated library. Record table, row ID, upstream commit, suitability, and any rejected alternatives. For styles, recommend active entries; deprecated and supplemental entries are context. Data is design guidance, not user research or normative accessibility authority.
3. Choose one coherent direction. Explain color roles, type roles, layout rhythm, icon treatment, elevation, and motion. Avoid applying a fashionable preset to every product. Do not let generic data override explicit brand requirements.
4. Build primitive values, semantic roles, and component tokens. Add light/dark themes only when useful. Reference semantic tokens from components rather than scattering literal colors.
5. Define core components by anatomy, variants, size, content, loading, disabled, focus, error, and success behavior. Include a status treatment independent of color alone.
6. Specify typography with script support and fallbacks, line length, scaling, wrapping, and number treatment. Verify font licensing before fetching or distributing a font. Bundled data contains font recommendations, not font files or a license grant for them.
7. Check actual text/surface and control/surface contrast pairs, not palette names. Document values and results per theme. Check reduced motion, focus, enlarged text, long labels, and RTL as relevant.

Deliver `tokens.json` following the token contract and `design-system.md` with usage rules, component states, rationale, and verified/untested checks. Export platform-specific tokens only when requested. Keep existing working values unless the brief or evidence justifies changing them.
