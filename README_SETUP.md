# Dengfeng Huang — Academic Pages site files

These files are an **overlay for an existing Academic Pages Jekyll repository**, not a standalone full Jekyll theme. They should be copied into the root of your existing `df.github.io` repository, preserving the directory structure.

## Install

1. Back up your repository.
2. Upload/replace `_config.yml`, `_data/navigation.yml`, `_pages/*.md` and `images/profile.png`.
3. In GitHub, commit the changes and check **Actions** / **Settings → Pages** for build status.
4. Visit `https://df.github.io/` (only if your GitHub username really is `df`).

The homepage is `_pages/about.md` with permalink `/`. If your repository already has another page with permalink `/`, remove or change that old homepage to avoid a conflict.

## Verify before publishing

- Confirm the author identity, affiliation wording, project descriptions, publication citations and authorship contributions.
- The CV says the 2026 Signal Transduction and Targeted Therapy paper was **accepted**, so it is shown as accepted, not definitively published.
- The portrait is extracted from the uploaded CV. Replace it if you prefer a higher-resolution photograph.
- No private phone number, birth date, or referees' contact details are published.
- The original CV PDF is deliberately **not** included because it contains private personal and referee details. `/cv/` provides a public-facing web CV.
- All missing academic profile URLs remain blank.

## Scope

This package assumes you already have the Academic Pages template files (Gemfile, `_layouts`, `_includes`, assets, etc.) in your repository. Without those, it will not build as a standalone site.
