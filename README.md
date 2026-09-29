# DREAM HOUSE — Final Classic Corporate

Mobile-first real-estate office system for DREAM HOUSE / Fayoum.

## Identity
- Engineer Ahmed Galal
- 01035032020

## PDF behavior
- Select only the properties you want.
- One click creates ONE PDF containing only those selected properties.
- Up to 20 selected properties per PDF.
- Each property gets a complete, readable A4 page with its photo and details.
- No summary-image picker and no page-by-page save dialog.
- Direct browser download is attempted first; iPhone/iPad share-to-Files is the fallback.

## Storage
- Property/client data: localStorage.
- Property images: IndexedDB.
- Backup/restore remains available from Reports.

## Checks
- JavaScript syntax checked with Node.
- Package structure kept flat for simple deployment.
