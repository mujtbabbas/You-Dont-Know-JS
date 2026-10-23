# Changelog

All notable changes to this standalone edition of You Don't Know JS are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, credit, and the explicit 2nd-edition branch provenance.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — the repository's first workflow, since upstream ships none); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream book text.
- Set the repository About description and homepage (the main upstream repository).
- Upstream already ships a root `.editorconfig` — verified and kept exactly as-is.
- Licence note recorded: `LICENSE.txt` is the CC BY-NC-ND 4.0 text; the NoDerivatives term restricts sharing adapted material. Nothing about the licence was changed.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) taken from the upstream **2nd-ed branch** (the upstream default branch — the second edition of the book series) at commit `044120ef55564939cd35f5ddaf3f6c0a45d7b02c` (upstream HEAD dated 2026-01-18). The 1st-ed branch was deliberately not used.
- Fork history severed; all files and the CC BY-NC-ND 4.0 licence (`LICENSE.txt`) preserved as-is, including the 15 binary images.
