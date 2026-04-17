<<<<<<< HEAD
# My Links — lesson-5

One-page, mobile-first link-in-bio built with plain HTML, CSS, and JavaScript.

Quick setup

- Open the repo on GitHub and enable Vercel integration (recommended): https://vercel.com/new
- Or use the GitHub Action workflow included below to deploy from GitHub Actions (requires Vercel secrets).

Vercel (recommended)

1. Go to https://vercel.com/new and import the repository `lesson-5`.
2. Vercel will detect this as a static site; no build command is required. The provided `vercel.json` will route to `index.html`.
3. Enable Automatic Deploys from the `main` branch.

GitHub Actions (optional)

This repository includes a workflow at `.github/workflows/vercel-deploy.yml` that will deploy on push to `main` using the Vercel CLI action. To use it, add these repo secrets in GitHub:

- `VERCEL_TOKEN` — your personal Vercel token (from https://vercel.com/account/tokens)
- `VERCEL_ORG_ID` — your Vercel organization ID (from project settings)
- `VERCEL_PROJECT_ID` — your Vercel project ID (from project settings)

After adding secrets, pushes to `main` will trigger the action and deploy to Vercel.

Local preview

Open `index.html` in your browser or run a simple static server (Python):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

Deploy: drop the folder into Vercel as a static site.
