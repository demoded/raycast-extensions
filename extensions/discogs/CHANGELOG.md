# discogs Changelog

## [Initial Version] - 2024-01-15

## [Windows Support and New Features] - 2026-03-03
Added Windows support config.
Bumped up dependencies.
Added new functions:
- Search for any release (original is Vinyl only)
- Search by Barcode
- Search by ReleaseNumber (CatNo)

## [Bug Fixes and quality of life improvements] - 2026-06-14
- Display release date as string without timezone conversion
- Remove catalog number from labels field, show name only
- Deduplicate barcodes by removing spaces before comparison
- Reordered release detail fields to present information in a more logical sequence
