# Duckify Portfolio

[![Website https://nathananto.github.io/duckify-portfolio/](https://img.shields.io/website-up-down-green-red/http/nathananto.github.io/duckify-portfolio/index.html.svg)](https://nathananto.github.io/duckify-portfolio/)

This repo contains the content of my semester project done in the 303.1 - Semester project course

## Website

This project website is available [here](https://nathananto.github.io/duckify-portfolio/) or locally at `_site/index.html` -->

The website contains the following competency sections:
 - Computer Science Engineer
 - Data Engineer
 - Professionalism

## Local Setup

To set up the project website locally:

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/)
2. Clone the repository
3. Run `uv sync` to install dependencies
4. Run `uv run quarto render` to build the site

The site will be in the `_site/` directory.

## Submodules

This repository uses Git submodules to include related projects:
 - TODO

To initialize and update submodules after cloning:

```bash
git submodule init
git submodule update
```
