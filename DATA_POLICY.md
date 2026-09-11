# SIT-UP Data Policy

This repository is intended for public research collaboration. To reduce privacy
risk, only anonymized or synthetic samples may be committed.

## Consent and Collection

- Record data only from participants with explicit informed consent.
- Do not commit raw personally identifiable recordings or logs.
- Keep signed consent forms and raw source data in private storage outside this repository.

## Anonymization Requirements

Before any sample data is committed:

- Remove names, usernames, email addresses, and device identifiers.
- Replace participant identifiers with non-reversible pseudonyms.
- Strip exact timestamps when not required for reproducibility.
- Remove location metadata and any free-text participant notes.

## Retention and Access

- Keep raw participant data in access-controlled storage.
- Retain public repository data only if it is anonymized and necessary for reproducibility.
- Delete public copies of data that are later found to contain identifying fields.

## Repository Rules

- `logs/` in this repository contains anonymized samples only.
- `questionnaire/` contains study templates only, not participant responses.
- Never commit API keys, account credentials, or cloud tokens.

## Reporting

If you find identifying data in this repository, open a private maintainer report
and remove the artifact in the next patch release.
