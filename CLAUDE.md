# DEVolver Blog

Personal software development blog by Eric Sal, built with Jekyll and hosted on GitHub Pages.

## Stack
- Jekyll with Minima theme (default skin)
- GitHub Pages via GitHub Actions deploy workflow
- URL: https://esalavat.github.io/devolver

## Local Development
```bash
bundle install
bundle exec jekyll serve
```

## Project Structure
- `_posts/` — blog posts (YYYY-MM-DD-title.md)
- `assets/images/` — site images (devolver.png logo, devolver_title.png hero)
- `.github/workflows/deploy.yml` — GitHub Actions deployment
- `_config.yml` — Jekyll configuration

## Notes
- Do not commit `_site/` (build output)
- Images in `assets/images/` are committed directly (no LFS needed)
