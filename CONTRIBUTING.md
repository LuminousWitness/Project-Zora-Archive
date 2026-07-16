# Contributing to the Project Zora Archive

Thank you for helping preserve Project Zora 3.3.3 / Artificial InSentience.

This is an archival repository first. Fidelity, provenance, attribution, and reversibility matter more than speed or polish.

## Before contributing

Read:

1. [`PERMISSION_AND_SCOPE.md`](PERMISSION_AND_SCOPE.md)
2. [`ARCHIVAL_PRINCIPLES.md`](ARCHIVAL_PRINCIPLES.md)

Do not submit private or unpublished Project Zora material without Christopher Anthony John Rimmer's separate, explicit authorization.

## Good first contributions

- preserving a public post with its date, caption, URL, and attachments;
- adding missing provenance or metadata;
- transcribing an archived image, audio file, or video;
- creating a chronological or topical index entry;
- calculating and recording SHA-256 checksums;
- identifying duplicate files without deleting either copy prematurely;
- documenting an independent mirror;
- supplying reliable sources relevant to a clearly attributed claim.

## Submission structure

Whenever possible, submit:

- the unaltered original file;
- a metadata record;
- an access copy only if needed;
- a transcript or OCR file only if clearly labeled as derived;
- a note describing acquisition method and any uncertainty.

## Suggested item metadata

```yaml
archive_id: PZ-YYYY-MM-DD-PLATFORM-SEQUENCE
author: Christopher Anthony John Rimmer
project: Project Zora 3.3.3 / Artificial InSentience
source_platform: Facebook
source_url: 
source_post_id: 
original_publication_datetime: 
acquired_datetime: 
acquired_by: 
original_filename: 
media_type: 
sha256: 
status: primary source preserved
notes: 
```

## File placement

- Unaltered public source files: `archive-original/`
- Christopher's public statements about the archive: `sources/`
- Transcripts and OCR: `transcripts/`
- Manifests and navigation: `index/`
- Research or interpretation: `research-notes/`
- Claims and source evaluation: `claims-and-verification/`

## Claims and verification

Do not silently present an allegation, interpretation, hypothesis, or personal account as an independently established fact.

Use clear attribution:

- “Christopher states…”
- “The archived post reports…”
- “This claim is currently unverified…”
- “The following source independently corroborates…”

Verification notes should cite sources, record access dates, and distinguish direct evidence from inference.

## Changes to originals

Never overwrite an original with a cleaned, enhanced, cropped, translated, compressed, or redacted version. Store derivative files separately and link them to the original archive identifier.

## Privacy and safety

Do not add passwords, access tokens, private addresses, unpublished private communications, or unnecessary sensitive third-party information. Flag uncertain cases for review.

## Commit and pull-request language

Use descriptive language such as:

- `Archive Facebook post dated 2025-06-14`
- `Add provenance metadata for PZ-2025-06-14-FB-0003`
- `Add transcript derived from archived video`
- `Correct uncertain date label; original unchanged`

## Stewardship standard

Contributors are custodians of the record, not owners of Christopher's work. Preserve first, attribute always, and interpret separately.
