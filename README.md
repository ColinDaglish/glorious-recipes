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
