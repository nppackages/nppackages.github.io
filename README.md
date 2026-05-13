# NP Packages Website

This repository hosts the public website for NP Packages:

https://nppackages.github.io

The site is a lean entry point for nonparametric and semiparametric software, references, replication links, contributors, and funding acknowledgments. Package documentation lives in the individual package repositories.

## Packages

- [binsreg](https://github.com/nppackages/binsreg): binscatter methods for partition selection, estimation, inference, and graphical procedures.
- [portsort](https://github.com/nppackages/portsort): estimation and inference using portfolio sorting methods.
- [lspartition](https://github.com/nppackages/lspartition): partitioning-based least squares methods, including B-splines, wavelets, and piecewise polynomial regression estimators.
- [nprobust](https://github.com/nppackages/nprobust): kernel density and local polynomial regression methods.
- [lpdensity](https://github.com/nppackages/lpdensity): local polynomial distribution and density regression methods.
- [lpcde](https://github.com/nppackages/lpcde): local polynomial conditional distribution and density regression methods.
- [scpi](https://github.com/nppackages/scpi): synthetic control methods for causal analysis.

The legacy package URLs under this site, such as `/binsreg/`, are kept as redirect stubs to the corresponding GitHub repositories. Mirror-style aliases under `/nppackages/<package>/` are also generated as redirects.

## Repository Structure

- `_config.yml`: Jekyll and GitHub Pages settings.
- `.editorconfig` and `.gitattributes`: editor and line-ending conventions.
- `Gemfile`: local GitHub Pages/Jekyll dependencies.
- `_includes/`: shared HTML fragments for metadata.
- `_layouts/`: page templates.
- `index.md`: homepage content.
- `<package>/index.md`: package redirect stubs.
- `nppackages/<package>/index.md`: mirror-style package redirect aliases.
- `replication/index.md`: replication resources.
- `references/`: PDF references linked from the website.
- `public/`: CSS and static assets.

## Editing

Most content changes happen in Markdown files. Each rendered page needs YAML front matter at the top, for example:

```yaml
---
layout: page
title: Page title
permalink: /page-slug/
---
```

Use relative internal links when possible, such as `/replication/` or `/references/file.pdf`, so the site remains portable across local previews and GitHub Pages.

## Local Preview

This is a Jekyll site. On a machine with Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000
```

This checkout includes a `Gemfile` and `Gemfile.lock` for GitHub Pages/Jekyll dependencies.

Note: local Windows builds were tested with Ruby 3.3.10. Ruby 3.4 exposed compatibility issues in the pinned `github-pages`/Jekyll 3.10 stack, so use Ruby 3.3.x for local GitHub Pages previews until the dependency stack is upgraded.

## Repository Maintenance

GitHub Actions validates whitespace and the Jekyll build on pushes and pull requests to `main`. Dependabot checks the Bundler and GitHub Actions dependency surfaces monthly.

## Deployment

The repository is intended for GitHub Pages at `nppackages.github.io`. The current source branch is `main`.

## Security

Please report security concerns or website integrity issues by email, not through a public issue.

## Queries and Requests

Please email [nppackages@googlegroups.com](mailto:nppackages@googlegroups.com).
