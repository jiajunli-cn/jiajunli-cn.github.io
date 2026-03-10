# Jiajun Li Academic Website

Personal academic website for Jiajun Li, built with Jekyll and hosted through GitHub Pages.

## Site structure

- `_pages/about.md`: homepage
- `_pages/research.md`: research overview
- `_pages/cv.md`: CV page
- `_config.yml`: site-wide settings and sidebar profile
- `_data/navigation.yml`: top navigation
- `assets/css/main.scss`: custom styling

## Local development

This project uses Jekyll.

Typical local workflow:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000` in your browser.

## Notes

- PDF files are stored in `files/`
- Images used by the site are stored in `images/`
- The current public site URL is `https://jiajunli-cn.github.io`
