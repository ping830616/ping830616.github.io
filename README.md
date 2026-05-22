# Hsiao-Ping Ni Academic Website

This is a Quarto academic website migrated from a public Notion research profile.

## Local preview

Install Quarto, then run:

```bash
quarto preview
```

## Render

```bash
quarto render
```

## Publish

The repository includes a GitHub Actions workflow at `.github/workflows/publish.yml`. On every push to `main`, GitHub Actions installs Quarto, renders the site, uploads `_site`, and deploys it to GitHub Pages.

If this repository is named `ping830616.github.io`, the final site URL is:

```text
https://ping830616.github.io/
```
