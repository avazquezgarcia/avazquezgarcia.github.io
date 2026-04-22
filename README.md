# Personal website for Alba Vázquez García

## Overview

This repository contains the static personal website for Alba Vazquez García. It is a simple HTML/CSS site with four main pages:

- `index.html` — Home / profile
- `research.html` — Research and working papers
- `teaching.html` — Teaching and course information
- `tax_changes.html` — Tax changes in Spain (interactive reference) *(work in progress)*

## Local preview

You can preview the site locally using any static file server. For example, with Python 3 run:

```bash
python -m http.server 8000

# then open http://localhost:8000 in your browser
```

## Editing

- Site files are plain HTML with embedded CSS. Edits can be made directly to the `.html` files.
- Keep styles consistent across pages by updating the inline `<style>` blocks in each file.

## Deployment

This repository is hosted on GitHub Pages. Push changes to the `main` branch and the site will publish at `https://avazquezgarcia.github.io/`.
