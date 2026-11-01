# Detailed project records

This folder is for **optional, durable reasoning and evidence**, not a second commit history.

## When to add a log

Write a dated record only when it would help a future maintainer understand something important that a code diff alone cannot explain: a design decision with trade-offs, a research experiment or evaluation, a major migration, a difficult bug investigation, or an important validation result.

For routine fixes or documentation polishing, a descriptive Git commit is enough. Update `CHANGELOG.md` for meaningful user-facing changes; it can link here when useful.

## Filename and scope

Use `YYYY-MM-DD-short-descriptive-topic.md` (for example, `2026-10-31-reproducibility-design.md`). Make one record per logical event. If two events occur on the same day, give them different topic slugs. Do not produce a new file for every coding step.

Start from [TEMPLATE.md](TEMPLATE.md) if it helps, but omit irrelevant sections. Prefer concise records with concrete links or evidence. Clearly separate proposed, implemented, tested, and unverified claims.

Git commits and pull requests remain authoritative for exact changes. Preserve the accuracy of past evidence; record corrections transparently. Do not include confidential information or private research data.

**Indexing:** do not manually duplicate an ever-growing file list here. Use descriptive filenames, repository search, and links from `CHANGELOG.md`.
