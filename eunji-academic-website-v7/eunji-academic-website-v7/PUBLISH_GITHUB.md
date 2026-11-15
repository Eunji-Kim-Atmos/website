# Publish your website to GitHub Pages

## Prepared GitHub account

Your connected GitHub username is **Eunji-Kim-Atmos**. The recommended repository name is **academic-website**.

Once the repository exists, the website's **intended** URL will be:

`https://Eunji-Kim-Atmos.github.io/academic-website/`

**This URL is not live yet.** The homepage repository has not been created or published. Publishing requires you to create the repository and enable deployment.

## Step 1. Create a public repository

Open https://github.com/new, select your account `Eunji-Kim-Atmos`, name it `academic-website`, and set the visibility to **Public**. Do **not** initialize with README, .gitignore, or license (the website package already includes these files). Click **Create repository**.

> A public GitHub Pages site is visible to anyone. Review the photo, affiliation details, awards, and conference list before publishing.

## Step 2. Upload the Quarto sources

Install Git if needed and open Git Bash (Windows) or a terminal. In the extracted `eunji-academic-website-v7` folder (the folder containing `_quarto.yml`), run:

```bash
git init
git add .
git commit -m "Publish academic website v7"
git branch -M main
git remote add origin https://github.com/Eunji-Kim-Atmos/academic-website.git
git push -u origin main
```

GitHub may ask you to sign in via your browser. If Git reports that your user name or email are not set, use `git config --global user.name "Your Name"` and `git config --global user.email "your-github-email"` (use your real GitHub email).

**Important:** GitHub must receive the contents of this project folder at the **root of the repository**. Don't upload the enclosing ZIP as one file.

## Step 3. Enable GitHub Actions and Pages

In the repository, go to **Settings > Actions > General > Workflow permissions** and enable **Read and write permissions** if not already enabled; save.

A GitHub Actions workflow included at `.github/workflows/publish.yml` will run on push to `main`, install Quarto, build the site, and publish it to `gh-pages`.

Check **Actions > Publish Quarto website** for a green check mark. After the workflow creates `gh-pages`, go to **Settings > Pages**. Select **Deploy from a branch**, branch **gh-pages**, folder **/(root)**, then **Save** if GitHub has not already configured this automatically.

After GitHub confirms deployment, open:

`https://Eunji-Kim-Atmos.github.io/academic-website/`

## Step 4. Keep updating

Edit the relevant `.qmd` file, then run:

```bash
git add .
git commit -m "Update website"
git push
```

GitHub Actions will rebuild the site after a successful push.

## Test locally without GitHub

Open `preview/index.html` in a browser. To test Quarto-generated output (requires Quarto installed), run `quarto preview`.

## Official references

- https://quarto.org/docs/publishing/github-pages.html
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
