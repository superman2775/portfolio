# super_man2775 Portfolio

A modern, responsive portfolio website showcasing projects, skills, and contact info.

## Features

- **Multilingual**: English, Dutch, German , French
- **Dark/Light Theme**: Persistent toggle with smooth transitions
- **Responsive**: Mobile-first design
- **Accessible**: ARIA labels, keyboard navigation, screen reader support
- **Self-contained**: Single HTML file + translations.js, no build step

## Quick Start

[https://superman2775.gitbook.io/](https://superman2775.github.io/portfolio/)

## Customization

### Languages
Edit `translations.js`:
- Add new languages
- Update existing keys
- Keys match `data-i18n="section.key"` attributes

### Theme
CSS vars in `<style>`:
- `:root` (dark default)
- `[data-theme="light"]`

Toggle via `#themeToggle` button (localStorage saved).

### Content
- Edit HTML directly
- Add `data-i18n="new.key"` for new translatable text
- Update keys in translations.js

## Structure

```
portfolio/
├── index.html     # Main site (HTML + CSS + JS)
└── translations.js # i18n data (4 languages)
```

## Tech

- Vanilla HTML/CSS/JS
- Space Grotesk + IBM Plex Mono fonts (Google Fonts)
- CSS Grid/Flexbox, CSS vars
- localStorage persistence
- Dynamic ES modules for translations

