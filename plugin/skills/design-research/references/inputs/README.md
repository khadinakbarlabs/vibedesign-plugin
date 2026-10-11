# Input examples

These bounded examples were checked against live build input schemas on October 11, 2026. They are starting points, not preauthorized runs. Inspect the current contract and pricing before starting.

| Input file | Catalog key | Purpose |
| --- | --- | --- |
| [pinterest-inspiration](pinterest-inspiration.json) | pinterest-data-extractor | Up to 12 design-inspiration pin records |
| [apple-reviews](apple-reviews.json) | apple-app-store-all-in-one-scraper | One app's metadata and up to 15 reviews |
| [google-play-reviews](google-play-reviews.json) | google-play-all-in-one-scraper | Up to 15 app review records |
| [reddit-feedback](reddit-feedback.json) | reddit-posts-search-scraper | Up to 15 public feedback posts |
| [capterra-reviews](capterra-reviews.json) | capterra-reviews-scraper | Up to 15 reviews of one public SaaS product |

Replace sample targets with the user's requested public sources. Keep country, language, sort, and limits explicit. App Store review collection may emit app metadata alongside reviews; count only relevant review records. Capterra limits are per product; avoid multiplying an unbounded product list by a review limit.

Create separate run-options after verifying the build, memory, pricing, finite timeout, and authorized event-charge cap. Do not put billing parameters into an Actor input unless its current schema explicitly supports them.
