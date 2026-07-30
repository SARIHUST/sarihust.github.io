# sarihust.github.io

Personal academic website for Hanhui Wang, built with [Jekyll](https://jekyllrb.com/) using the [al-folio](https://github.com/alshedivat/al-folio) theme.

Live at: https://sarihust.github.io

## Local development

```bash
$ bundle install
$ bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Content

- `_config.yml` — site-wide settings (name, links, scholar info)
- `_data/cv.yml` — CV content (currently unused by the nav, which links directly to `assets/pdf/cv.pdf`)
- `_data/coauthors.yml` — coauthor name → personal website mapping, used to auto-link authors in the publications list
- `_bibliography/papers.bib` — publication list
- `_news/` — news items shown on the homepage
- `_projects/` — project pages (currently unused)

## Deployment

Pushes to `master` are automatically built and deployed to GitHub Pages via the `deploy` GitHub Action.

## Theme

Based on [al-folio](https://github.com/alshedivat/al-folio), available under the [MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE).
