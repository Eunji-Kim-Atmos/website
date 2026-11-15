# Publish Eunji Kim's website

Repository: https://github.com/Eunji-Kim-Atmos/website

Expected site URL after deployment: https://eunji-kim-atmos.github.io/website/

The Quarto project files must be in the repository root, with `_quarto.yml`, `index.qmd`, `styles.css`, `images/`, and `.github/workflows/publish.yml` directly under the root.

## Deploy

1. Go to Settings > Actions > General, and allow GitHub Actions to run. Workflow permissions may need to be set to **Read and write permissions**.
2. Go to Actions > Publish Quarto website and check the run triggered by the latest push. If there is no run, use **Run workflow**.
3. Once the workflow completes, open Settings > Pages, select **Deploy from a branch**, **gh-pages**, **/(root)** and Save.
4. Check https://eunji-kim-atmos.github.io/website/ after GitHub shows a successful deployment.

See https://quarto.org/docs/publishing/github-pages.html for Quarto documentation.
