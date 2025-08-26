# Personal Site Template (GitHub Pages)

A minimal one‑page portfolio optimized for fast setup on GitHub Pages. Dark/light mode friendly, no build tools, just `index.html`.

## Quick Start

1) Create a repository named `<your-username>.github.io` on GitHub.
2) Upload `index.html` (and optionally `resume.pdf`) to the root of the repository and commit.
3) Go to **Settings → Pages → Build and deployment → Source → Deploy from a branch** and choose your default branch and **/(root)**. Save.
4) Your site will be available at `https://<your-username>.github.io/` after it builds.

## Personalize

- Replace the `{{PLACEHOLDERS}}` in `index.html`:
  - `{{NAME}}`, `{{INITIALS}}`, `{{ROLE}}`, `{{LOCATION}}`
  - `{{EMAIL}}`, `{{GITHUB_USERNAME}}`, `{{LINKEDIN_SLUG}}`
  - `{{TAGLINE}}`
  - Experience block placeholders (ROLE_1, COMPANY_1, etc.)
  - `{{TARGET_REGIONS}}`, `{{CLOUD_PROVIDER}}`
- Add your PDF as `resume.pdf` in the repository root to enable the Resume button.

## Custom Domain (optional)

- Buy a domain and add it under **Settings → Pages → Custom domain**, then set up DNS per GitHub’s instructions.
