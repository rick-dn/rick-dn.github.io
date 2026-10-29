# rick-dn.github.io

Personal portfolio built with Jekyll and hosted on GitHub Pages.

## Structure

```
_config.yml        site settings, social links, photo/resume paths
_layouts/          page layout (default.html)
_includes/         shared header, footer, icons
_projects/         one Markdown file per project (shown newest first)
assets/css|js|images
index.html         Projects (home)
about.html         About
```

## Add a project

Create `_projects/YYYY-MM-DD-name.md`:

```yaml
---
title: Project name
date: 2026-10-01
summary: Short description.
tags: [Python, ML]
repo: https://github.com/...
demo:
image: /assets/images/name.png
---
```

## Local preview

Requires Ruby with dev headers (`ruby-dev` on Ubuntu) and Bundler.

```
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploy

Push to a GitHub repo named `rick-dn.github.io`. The site will be live at https://rick-dn.github.io.
