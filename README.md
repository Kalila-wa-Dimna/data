# Kalila wa Dimna — edition data

Public snapshot of production edition data from the Kalila transcription/edition platform.

Source: `s3://kalila-pages-prod/public/data_prod/edition_data/`

## Layout

| Path | Contents |
|------|----------|
| `edition_data/manuscripts/` | Per-witness page JSON by siglum / chapter / page |
| `edition_data/xml_data/` | TEI page XML by siglum / chapter / page |
| `edition_data/collations/` | Chapter collation export files |
| `edition_data/unit_profiles/` | Unit profile JSON for AI / analysis |
| `edition_data/manuscripts_description/` | Manuscript metadata |
| `edition_data/images/` | Illustration / image assets used by the edition |

## Not included

`edition_data/page/` (facsimile page images, ~7 GiB) is omitted because it exceeds practical GitHub repository size limits. Those files remain on the project S3/CDN storage.

## Sync date

Synced from production S3 on 2026-09-14.
