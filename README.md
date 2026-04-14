# Hugo VSCode Theme (Ayu Dark)

A Hugo static site / blog theme designed to look like **Visual Studio Code** using the beautiful **Ayu Dark** color palette.

## Features

- **VSCode-inspired UI**: sidebar explorer, editor area, status bar, tabs, and activity bar.
- **Ayu Dark colors**: exact palette from the official Ayu theme for backgrounds, tooltips, buttons, menus, and syntax highlights.
- **Alpine.js**: lightweight, embedded JavaScript framework for all interactions — no external JS dependencies.
- **Self-contained assets**: all CSS and JS are bundled inside the theme. The only external resources are web fonts loaded from Google Fonts.
- **Font switcher**: change the site font directly from the UI. Choices include coding fonts like JetBrains Mono and Fira Code.
- **Cookie-based state**: your sidebar visibility and font preference are saved in cookies and persist across sessions.

## Quick Start

```bash
# Add the theme to your Hugo site
cd your-hugo-site
git submodule add https://github.com/fahadysf/hugo-vscode-theme.git themes/hugo-vscode-theme

# Update config to use the theme
echo 'theme = "hugo-vscode-theme"' >> hugo.toml
```

## Requirements

- Hugo Extended `>= 0.124.0`

## Configuration

Example `hugo.toml`:

```toml
baseURL = 'https://example.com'
languageCode = 'en-us'
title = 'My VSCode Blog'
theme = 'hugo-vscode-theme'

[params]
  author = "Your Name"
  description = "A blog that looks like VSCode"
```

## Fonts

The theme offers an in-site font selector in the status bar. Available fonts are loaded via Google Fonts:

- JetBrains Mono (default)
- Fira Code
- Inter
- Roboto Mono

Your preference is stored in a browser cookie.

## License

MIT License — see [LICENSE](LICENSE).
