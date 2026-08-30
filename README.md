# Mahammad Nabizade - Personal Website

Clean, minimal Jekyll site for my research and academic profile.

## Structure

_layouts/ - Base HTML templates
_includes/ - Reusable components
_pages/ - Content pages (markdown)
assets/css/ - Styling
images/ - Profile picture & assets


## Run Locally

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`

## Deploy

Push to `master` branch. GitHub Pages rebuilds automatically.

## Building

- **DRY**: Components in `_includes/` prevent repetition
- **SOLID**: Each file has single responsibility
- **Clean**: Minimal, readable code
- **Maintainable**: Easy to modify and extend
