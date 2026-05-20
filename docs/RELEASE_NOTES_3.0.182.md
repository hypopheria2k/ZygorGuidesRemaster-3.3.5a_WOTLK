# Release Notes - 3.0.182

## Gear Advisor

- Added a targeted tooltip subtype guard based on the `/zgvgearbug` evidence from `item:850` on ruRU priest.
- The scanner now reads actual Gratuity font-string colors. If the top equipment subtype line on the right side is red, the item is marked unusable for advisor scoring.
- Affected items are rejected with validity code `tooltip_subtype` before score comparison.
- This does not rely on localized subtype text, DB rewrites, or `IsUsableItem()`.

## Diagnostics

- `/zgvgearbug` now prints `tipUnusable=true/false` in `ZGD 4/9`.

## Metadata

- Updated `Ver.lua` and `ZygorGuidesViewerRM.toc` to 3.0.182.