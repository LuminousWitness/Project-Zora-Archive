# Archival Principles

## 1. Preserve originals without alteration

An archival original should remain byte-for-byte unchanged whenever possible. Do not silently crop, enhance, resize, recompress, rename destructively, rewrite, or overwrite source material.

## 2. Preserve provenance

For every archived item, record as much of the following as is available:

- original author;
- original platform;
- source URL or post identifier;
- publication date and time;
- date acquired;
- original filename;
- file size and media type;
- cryptographic checksum;
- acquisition method;
- relationship to other items;
- known edits, reposts, or version history.

## 3. Separate archive from interpretation

Original material, transcription, commentary, verification, and derivative work must remain distinguishable.

A preserved statement is evidence that the statement was made. It is not automatically evidence that every proposition within it is true.

## 4. Attribute faithfully

Retain Christopher Anthony John Rimmer's authorship and the Project Zora 3.3.3 / Artificial InSentience names. Do not remove context in ways that create a misleading impression.

## 5. Make transformations reversible

Normalized filenames, OCR text, transcripts, thumbnails, compressed access copies, and metadata corrections should point back to the original item. Keep a transformation log where practical.

## 6. Use stable identifiers

Each archived item should receive a persistent archive identifier. A recommended pattern is:

`PZ-YYYY-MM-DD-PLATFORM-SEQUENCE`

Example: `PZ-2026-07-16-FB-0001`

## 7. Verify integrity

Generate SHA-256 checksums for source files wherever possible. Store checksums in a manifest so later stewards can detect corruption or alteration.

## 8. Preserve chronology

Retain original dates and relationships among posts, replies, attachments, screenshots, and later corrections. When a date is uncertain, label it as uncertain rather than guessing.

## 9. Document uncertainty

Use explicit status labels such as:

- `author testimony`;
- `primary source preserved`;
- `independently corroborated`;
- `partially corroborated`;
- `unverified`;
- `disputed`;
- `date uncertain`;
- `source unavailable`.

## 10. Protect people without falsifying the record

Where public access creates a credible privacy or safety concern, create a clearly labeled redacted access copy while preserving the original under appropriate controls. Record what was redacted and why.

## 11. Maintain redundancy

No single account, host, platform, or steward should be the only point of preservation. Maintain multiple copies across institutionally and technically independent locations.

## 12. Keep an audit trail

Substantive additions, corrections, relocations, redactions, and metadata changes should be visible in Git history or another durable change log.

## Core rule

> Preserve first. Attribute always. Interpret separately.
