# Anna Lu — Portfolio

**Live site:** [[luyi22.github.io/Portfolio-Page](https://luyi22.github.io/Portfolio-Page/)](https://luyi22.github.io/my_portfolio/)

## What’s on the site

- Professional experience and technical toolkit
- Selected projects:
  - [Bookmark Manager](https://github.com/LUYI22/Bookmark-Manger) — a
    self-hosted JavaScript app with an Express API and SQLite database
  - [RUMAPS](https://github.com/LUYI22/RUMAPs) — an interactive Rutgers campus
    map using Java graph algorithms
- Education, interests, and contact links
- Downloadable resume and profile photo

## Preview locally

This is a static site; no build step or package installation is required.
From the repository root, start a local web server:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000> in a browser. The resume, stylesheets,
scripts, and profile photo are served from the repository.

## Project structure

- `index.html` — portfolio content and page structure
- `assets/css/portfolio.css` — portfolio-specific styling
- `assets/css/main.css` and `assets/js/` — HTML5 UP template styles and scripts
- `images/headshot.jpeg` — profile photo
- `LuAnna_Resume.pdf` — downloadable resume
