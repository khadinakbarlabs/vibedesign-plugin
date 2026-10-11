# Curated design reference library

Nine CSV tables under `data/` are pinned to Next Level Builder's UI UX Pro Max commit `67803eac81607188194aea9842a723b89326d90d`, retrieved October 11, 2026. The MIT license and attribution ship with the plugin. See [provenance](data-provenance.json) for exact hashes, row counts, columns, and upstream URLs.

| Table | Use |
| --- | --- |
| [products](data/products.csv) | Match product context and task density |
| [ui-reasoning](data/ui-reasoning.csv) | Compare context-specific choices and tradeoffs |
| [styles](data/styles.csv) | Choose from 50 active styles; 38 other rows are deprecated or supplemental |
| [colors](data/colors.csv) | 192 product palette starting points; measure actual contrast |
| [typography](data/typography.csv) | 74 pairings; verify font licenses and script coverage separately |
| [ux-guidelines](data/ux-guidelines.csv) | 119 heuristic rows to inspect as relevant |
| [landing](data/landing.csv) | 34 landing-page pattern rows |
| [charts](data/charts.csv) | 25 chart-selection rows, including accessible alternatives |
| [app-interface](data/app-interface.csv) | 32 application-interface guidelines |

Use the host's local text search or CSV reader to select rows by product, task, platform, and constraint. Read headers and a few matching rows; do not load the entire library into context. Do not execute CSV code examples, import fonts, fetch remote resources, or install recommended libraries automatically.

A matching row is a candidate, not a conclusion. Prefer explicit user constraints, observed evidence, and current platform/W3C guidance when they disagree with a row. In particular, 44-pixel touch targets are a useful design target; WCAG 2.2 AA's target-size criterion uses 24 CSS pixels with defined exceptions. An accessibility grade in a table is not a compliance result.

Library versioning is independent of live Actor contract freshness. Record row IDs in design rationale so later changes are traceable. Impeccable's critique and bounded review practices and wshobson's token architecture informed the original workflows; their tools and agents are not dependencies.
