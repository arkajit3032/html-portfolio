# html-portfolio

A simple static portfolio site.

## GitHub Pages deployment

This repository now includes a workflow at `.github/workflows/deploy-pages.yml` that deploys the site to GitHub Pages whenever you push to `main`, `master`, or `work`.

### One-time setup in GitHub

1. Open **Settings → Pages** in your GitHub repository.
2. Under **Build and deployment**, choose **Source: GitHub Actions**.
3. Push your latest commits to your default branch.
4. After the workflow completes, your site will be available at:
   - `https://<your-username>.github.io/<repo-name>/` (project pages), or
   - your custom domain if configured.
