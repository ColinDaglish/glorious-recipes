# Glorious Recipes

A small Quarto website for publishing a recipe collection.

## Structure

- `index.qmd` - landing page
- `recipes/index.qmd` - recipe directory
- `recipes/*.qmd` - recipe detail pages
- `_quarto.yml` - Quarto website configuration
- `styles.css` - site styling

## Prerequisites

Install [Quarto](https://quarto.org/docs/get-started/).

## Preview locally

```powershell
quarto preview
```

## Build the site

```powershell
quarto render
```

The generated site will be written to `_site/`.

## Deploy to GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that renders the Quarto site and publishes `_site/` to GitHub Pages.

In the repository settings, set **Pages** to use **GitHub Actions** as the source.
