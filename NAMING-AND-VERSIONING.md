# Naming and Versioning

## PDF filenames

Use:

~~~text
YYYY-MM-DD_provider_model_session-state_short-title_vNN.pdf
~~~

Example:

~~~text
2026-09-16_google_gemini_cold-default_deep-ethical-reasoning_v01.pdf
~~~

Use lowercase ASCII characters, numbers, hyphens, and underscores. Keep the filename descriptive enough to recognize outside GitHub.

## Companion metadata

Give the metadata file the same basename:

~~~text
2026-09-16_google_gemini_cold-default_deep-ethical-reasoning_v01.md
~~~

## Corrections

Do not overwrite a published PDF when its contents change materially. Publish v02, retain v01, and create or update a record in [CORRECTIONS/](CORRECTIONS/README.md) stating:

- what changed;
- why it changed;
- who identified the issue;
- whether the earlier interpretation remains historically useful;
- which version should normally be read first.

Metadata-only corrections that do not alter the PDF may update the companion Markdown file through ordinary Git history.
