# Polished Quarto Project Website

This is a more polished drop-in replacement for your GitHub Pages project repository website.

## Files included

- `_quarto.yml`
- `index.qmd`
- `projects.qmd`
- `about.qmd`
- `assets/css/styles.css`
- `data/projects.csv`
- `project_page_templates/`

## Recommended installation

1. Back up your current website folder.
2. Copy these files into your local `project-search-website` folder.
3. If you already customized `data/projects.csv`, either:
   - merge your rows into this new CSV structure, or
   - add the new columns to your existing CSV.
4. Render:

```bash
quarto render
```

5. Commit and push:

```bash
git add .
git commit -m "Polish project website design"
git push
```

## Important

This design assumes GitHub Pages is serving from the `docs/` folder.
