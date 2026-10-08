# wigglep1ne.github.io

Personal page [wigglep1ne.dev](https://wigglep1ne.dev).

Built with [Hugo](https://gohugo.io) — a fast, zero-dependency static site generator.

## Quick start

```sh
hugo server
```

Open [http://localhost:1313](http://localhost:1313).

## Build

```sh
hugo --minify --environment production
```

Output lands in `public/`.

## Structure

```
├── hugo.toml            # Site config (params, contact form, etc.)
├── content/             # Pages (home, about, contact)
├── layouts/             # Templates (base, partials, contact)
│   ├── _default/        # baseof, list, single
│   ├── partials/        # header, footer
│   └── contact/         # contact page layout
├── static/              # Static assets (PGP key, etc.)
└── archetypes/          # Default front matter
```

## Features

- Zero JavaScript framework — vanilla HTML + minimal inline JS
- Dark mode with system preference detection and toggle
- Contact form with optional client-side PGP message encryption
- Publications with categories, tags, search, pagination, navigation, and numbered table of contents
- Not zoomable on mobile (`user-scalable=no`)

## License

GPLv3 — see [LICENSE.txt](LICENSE.txt).
