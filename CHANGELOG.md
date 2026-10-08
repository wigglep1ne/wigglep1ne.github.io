# Changelog

## [0.1.0] — 2026-10-08

### Added

- GitHub Actions workflow to build and deploy the Hugo site to GitHub Pages on pushes to `main`
- Automated Pages deployment pipeline with Hugo build, artifact upload, and GitHub Pages publish
- Manual workflow trigger support for redeploying the site without a push

### Changed

- Site deployment process moved to a CI/CD pipeline for consistent production builds

### Fixed

- Ensured Hugo builds are generated through the same production workflow used for deployment

## [0.0.2] — 2026-06-27

### Added

- Social links in footer (GitHub, LinkedIn, Twitter, Reddit)
- SEO meta tags (Open Graph, Twitter Card, JSON-LD, canonical)
- Umami analytics support
- Favicon set (ICO, SVG, PNG, apple-touch-icon, webmanifest)
- Componentized layout (partials for head, header, footer, SEO, umami)
- External CSS via Hugo Pipes with minification and fingerprinting
- Dark mode pre-load script for no-flash theme switching

## [0.0.1] — 2026-06-27

### Added

- Home page with name and email
- About page
- Contact page with Formbold integration
- PGP public key display with copy and download
- Dark mode with system preference detection and manual toggle
- Responsive navbar with brand name and navigation links
- Footer with copyright
- Hugo static site scaffold (zero JS framework)
- Not zoomable on mobile viewport
