# Kai Niu's homepage

This repository contains the source code for Kai Niu's personal website, built with Jekyll. The site serves as a public profile to showcase the publications, and news.

Project layout
- News: `_news/`
- Publications: `_publications/`

Quick start (local preview)
1. Ensure Ruby and Bundler are installed on your system.
2. Install gems (run this if `vendor/bundle` is not present):

```bash
bundle install --path vendor/bundle
```

3. Serve locally with live reload:

```bash
bundle exec jekyll serve --livereload
```

Editing guide
- Publications: edit the Markdown files under `_publications/` in the appropriate year folder.
- News: add or edit Markdown files in `_news/` (follow the existing front matter).
- Pages and components: update templates in `_layouts/` and `_includes/`, and edit static assets in `assets/`.

Deployment
- This repository is intended to publish via GitHub Pages. If the repository name follows the `username.github.io` convention (this repo is `niukai10.github.io`), pushing to the default branch will publish the site automatically.

License
- See the `LICENSE` file in the repository root for license details.
