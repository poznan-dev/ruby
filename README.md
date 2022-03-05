# Poznań Ruby User Group website
[![Jekyll Deploy](https://github.com/poznan-dev/prug/actions/workflows/jekyll.yml/badge.svg)](https://github.com/poznan-dev/prug/actions/workflows/jekyll.yml)

## Requirements
- Ruby 3.1.1 (`.ruby-version`)
- Node 16.13.2 (`.node-version`)

## Stack
- Jekyll
- Tailwindcss

## Development
After installing dependencies with `npm` and `bundler` it's as easy as:
```shell
bundle exec jekyll serve
```
It supports regeneration on change for both styles and content.

## Production
Deployments are run on GitHub Actions after each merge to `main` branch.
It runs Jekyll build and puts generated content to `gh-pages` branch.

For more details check out `.github/workflows/jekyll.yml`.
