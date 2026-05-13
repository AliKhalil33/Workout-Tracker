# Workout Tracker

This repository contains a simple static workout tracker app in `index.html`.

## GitHub Pages Deployment

A GitHub Actions workflow is already added at `.github/workflows/pages.yml` to deploy the repo as a public static site from the `main` branch.

### To finish deployment

1. Commit the workflow:
   ```bash
   git add .github/workflows/pages.yml README.md
   git commit -m "Add GitHub Pages deployment workflow"
   git push origin main
   ```

2. Visit the public site once GitHub Actions finishes deploying:
   ```text
   https://AliKhalil33.github.io/Workout-Tracker/
   ```

### Notes

- The app is served directly from your repository root.
- If the site does not appear immediately, wait a few minutes for GitHub Pages to complete deployment.
