# Changelog

All notable changes to this project are documented in this file.  
Format: `[vMAJOR.MINOR.PATCH] - YYYY-MM-DD`

---

## [v1.3.2] - 2024-10-26

- added `-tr` versions

---

## [v1.3.0] - 2026-08-24

- CI/CD: parallel matrix build for all 6 CV variants via GitHub Actions
- CI/CD: automatic GitHub Release creation on `git tag v*.*.*`
- CI/CD: `concurrency` group to cancel stale runs on new push
- `.gitignore`: removed `.github/` exclusion so workflows are tracked in git
- `README.md`: download table, project structure, CI/CD usage docs, preview table for all variants

### Changed

- `latex.yml`: replaced single-file compile with `matrix` strategy (6 variants, `fail-fast: false`)
- `latex.yml`: artifacts now have 30-day retention
- `.gitignore`: cleaned and scoped to LaTeX-relevant ignores only

---

## [v1.2.0] - 2026-03-11

- Initial CI/CD workflow (`latex.yml`) - basic compile + artifact upload
- `en-tr` (Trading) variant added

---

## [v1.0.0] - 2024-10-26

- Initial LaTeX CV - French and English versions
- `src/en/` and `src/fr/` directory structure
- `resources/img/` preview images
- MIT License
