# Hayato Tagawa

Source for my personal academic website:
[https://hayataga.github.io/HayaTaga](https://hayataga.github.io/HayaTaga)

This site is built with [Jekyll](https://jekyllrb.com/) and is based on the
[al-folio](https://github.com/alshedivat/al-folio) theme, with the repository
trimmed down to a simpler personal-site setup.

## Research Interests

- Econometrics
- Causal inference
- Panel data analysis
- Spatial econometrics
- Network models

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/HayaTaga/`.

## Build

```bash
bundle exec jekyll build
```

The generated site is written to `_site/`.

## Deployment

Deployment is handled by GitHub Actions on pushes to `main` or `master`.

## Credit

The original theme and documentation are from
[alshedivat/al-folio](https://github.com/alshedivat/al-folio).
