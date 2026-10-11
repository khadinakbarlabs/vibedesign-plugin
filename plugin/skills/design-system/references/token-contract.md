# Token contract

Use a JSON object with `version`, `product`, `direction`, `primitives`, `semantic`, `components`, and `verification`. This is VibeDesign's simple editable project format, not a claim of compatibility with every token standard.

- `primitives`: explicit color, font, type size, line-height, spacing, radius, elevation, and motion values. State units.
- `semantic`: roles such as text.primary, text.secondary, surface.default, border.default, action.primary, focus.ring, and status.error. Add theme maps when requested. Each value references an existing primitive.
- `components`: values reference semantic roles where practical. Include states and platform exceptions.
- `verification`: actual foreground/background pairs, contrast ratio, applicable threshold, measured/pending status, test method, and date. Record device/font/RTL checks separately.

Resolve every reference and reject cycles or missing values before handoff. Fonts use a safe fallback stack until an approved licensed asset is available. Do not claim a recommended palette guarantees accessible output.
