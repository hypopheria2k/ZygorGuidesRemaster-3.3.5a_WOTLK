# Release Notes - 3.0.178

## Gear Advisor

- Prevented DB-only fallback gear records from being scored before live item details resolve.
- Pending item details now return a non-final invalid verdict and `GetItemScore()` skips those items until the tooltip/cache scan succeeds.
- This targets the remaining Laplace report where ruRU priest characters could still see unusable leather/mail items recommended from armor-only fallback data after 3.0.177.

## Metadata

- Updated `Ver.lua` and `ZygorGuidesViewerRM.toc` to 3.0.178.
