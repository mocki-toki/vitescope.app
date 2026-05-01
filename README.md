# vitescope.app

Static website for Vitescope legal/support pages and root redirect.

## Pages

- `/` -> redirects to `https://apps.apple.com/us/app/vitescope/id6764871497`
- `/privacy-policy/` -> Privacy Policy
- `/support/` -> Support

## Deployment

This repository deploys automatically to GitHub Pages via `.github/workflows/pages.yml` on push to `main`.

Custom domain is configured with `CNAME`:

- `vitescope.app`
