# Adrian Vale — The Hub

**Live website:** https://adrianvaleitl-debug.github.io/Adrian-Vales-Projects/

A central home for Adrian Vale's software, downloads, project websites, release notes and creator links.

## Website features

- **Light and dark mode:** manual theme switch, remembers the visitor's choice on their device, and respects the system theme on first visit.
- **Download centre:** automatically finds the latest public Windows installer (.exe) and portable ZIP assets from GitHub Releases.
- **Live project directory:** discovers public, non-fork, non-archived repositories and displays project websites, source code and release links.
- **Latest releases:** shows a live feed of recently published releases.
- **Central links page:** GitHub, YouTube, TikTok, Ko-fi and project repositories.
- **Long-form layout:** quick navigation, project overview, creator/about section and contact links.
- **Responsive navigation:** mobile menu, keyboard-friendly controls and reduced-motion support.

## Featured projects

| Project | Website | GitHub |
|---|---|---|
| MarketView | https://adrianvaleitl-debug.github.io/Adrian-Vales-Projects/marketview/ | https://github.com/adrianvaleitl-debug/MarketView |
| Ledger | https://adrianvaleitl-debug.github.io/Adrian-Vales-Projects/Ledger/ | https://github.com/adrianvaleitl-debug/Ledger |
| Daymark | https://adrianvaleitl-debug.github.io/Adrian-Vales-Projects/Daymark/ | https://github.com/adrianvaleitl-debug/Daymark |

The website reads the account's public repositories from the GitHub API. It excludes this portfolio repository, forks and archived repositories. For each repository, the homepage URL is preferred; if none is set and GitHub Pages is enabled, the website uses the repository's Pages URL. Latest releases are fetched from GitHub Releases.

## Creator links

- GitHub: https://github.com/adrianvaleitl-debug
- YouTube: https://www.youtube.com/@Adrianvaleitl
- TikTok: https://www.tiktok.com/@adrianvaleitl
- Ko-fi: https://ko-fi.com/marketinsight

**Discord:** the invite URL has not yet been supplied, so the website marks this link as pending rather than publishing an invented or invalid invite.

## Local preview

No build step is required. Clone the repository and open `index.html` in a modern browser. An internet connection is required for Google Fonts and the live GitHub API data.

## Deployment

GitHub Actions deploys the site to GitHub Pages on pushes to `main` and on manual workflow dispatch. Workflow: `.github/workflows/pages.yml`.

## Contributing

Use [Issues](https://github.com/adrianvaleitl-debug/Adrian-Vales-Projects/issues) to report bugs or suggest improvements.
