# Changelog

## Task 1 — Accurate README

- File: `README.md`
  - Before: Candidate/review and deployment restrictions, missing preview and QA paths, `site/` prefixes, and historical claims.
  - After: Published-site description, verified file list, HTTP preview instructions from the repository root, and the retained no-new-reuse-license note.
  - Reason: Document the actual site and repository accurately.
- File: `CHANGELOG.md`
  - Before: Absent.
  - After: Per-task records of files, before/after states and reasons.
  - Reason: Provide the requested audit trail; subsequent tasks append their records here.

## Task 2 — Shared cache version

- File: `index.html`
  - Before: `20261111-final-details1`, `20261111-mobile23-note2`, `20261111-review08-transition-fix`, `20261112-desktop-wheel8`, `20261112-home-hero-copy8`, `20261112-nav-shell2`, `20261112-project-typography20`, `20261112-stable-grip6`, `20261112-touch-nav18`.
  - After: All nine versioned href/src references use `20261112-cleanup1`.
  - Reason: Use an identical cache key for each shared asset across pages.
- File: `factory.html`
  - Before: `20261111-final-details1`, `20261111-mobile23-note2`, `20261111-review08-transition-fix`, `20261112-desktop-wheel8`, `20261112-nav-shell2`, `20261112-project-typography17`, `20261112-stable-grip6`, `20261112-touch-nav18`, `20261112-unified-nav20`.
  - After: All nine versioned href/src references use `20261112-cleanup1`.
  - Reason: Use an identical cache key for each shared asset across pages.
- File: `notebooks/01_data_quality_analysis.html`
  - Before: `20261111-final-details1`, `20261111-mobile23-note2`, `20261111-review08-transition-fix`, `20261112-desktop-wheel8`, `20261112-nav-shell2`, `20261112-project-typography17`, `20261112-stable-grip6`, `20261112-touch-nav18`, `20261112-unified-nav20`.
  - After: All nine versioned href/src references use `20261112-cleanup1`.
  - Reason: Use an identical cache key for each shared asset across pages.
- File: `notebooks/02_data_cleaning_validation.html`
  - Before: `20261111-final-details1`, `20261111-mobile23-note2`, `20261111-review08-transition-fix`, `20261112-desktop-wheel8`, `20261112-nav-shell2`, `20261112-project-typography17`, `20261112-stable-grip6`, `20261112-touch-nav18`, `20261112-unified-nav20`.
  - After: All nine versioned href/src references use `20261112-cleanup1`.
  - Reason: Use an identical cache key for each shared asset across pages.
