# Project Guidelines

## Purpose

This workspace is a small Quarto website for publishing recipes.
Prefer small, focused changes that preserve the existing site structure and writing style.

## Project Structure

- `index.qmd` is the homepage.
- `recipes/index.qmd` is the recipe directory.
- `recipes/*.qmd` are individual recipe pages.
- `_quarto.yml` controls site configuration and output.
- `styles.css` contains the shared visual styling.

## Content Conventions

- Keep recipe pages simple and readable with these sections when relevant: `Summary`, `Ingredients`, `Method`, and `Serving note`.
- Match the existing Markdown and Quarto style used in the recipe pages.
- Write recipe content in original wording. Do not copy external recipe text verbatim.
- When adapting a recipe from a source, summarize the technique in fresh language and keep ingredient lists and instructions practical.
- Prefer metric measurements for recipes, especially weights and liquid volumes such as `g`, `kg`, `ml`, and `l`.
- Avoid cup-based measurements when a practical metric weight or fluid measurement can be given instead.

## Editing Guidelines

- Preserve existing page titles, links, and relative paths unless the task requires changing them.
- When adding a new recipe, update any index or featured sections that should link to it.
- Keep styling changes in `styles.css` minimal and consistent with the current warm visual theme.
- Do not edit `_site/` by hand because it is generated output.

## Build And Validation

- Use `quarto preview` for local preview when needed.
- Use `quarto render` to regenerate the site after content or styling changes.
- If a build cannot be run, state that clearly in the final response.