# Change Log

| Date | Commit | File | Section | Lines | Change Type | Summary | Reason | Status |
|------|--------|------|---------|-------|-------------|---------|--------|--------|
| 2026-05-09 | `0cd854d` | `sections/header.liquid` | JSON-LD Organization `sameAs` | 336-346 | Modified | Skip blank `social_*_link` values; add LinkedIn and WhatsApp | Empty strings in `sameAs` flagged by SEO crawlers | Pushed to `main` |
| 2026-05-11 | `e0c23a2` | `sections/featured-home-collection.liquid` | Homepage product card loop | 76-114 | Added | Emit per-product schema.org `Product` JSON-LD (name / image / price / availability / brand / sku / url) with `@id` for dedup | Homepage product blocks were invisible to Google rich results and AI shopping agents; structured data unlocks rich product cards and lets assistants quote prices | Pushed to `main` |
