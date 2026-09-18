# Ender Bot Landing Page

Deployed at [enderbot.cyberender.net](https://enderbot.cyberender.net) via GitHub Pages.

A production-quality marketing site for Ender Bot — a native desktop AI assistant for Windows and Mac.

## Development

No build step required. Pure HTML + CSS + vanilla JS.

```bash
# Serve locally (any static file server)
npx serve .
# or
python -m http.server 8080
```

## Deployment

Pushes to `main` automatically deploy via GitHub Actions → GitHub Pages.

## DNS (GoDaddy)

Add one record to point `enderbot.cyberender.net` to GitHub Pages:

| Type  | Name     | Value                 |
|-------|----------|-----------------------|
| CNAME | enderbot | cyberender1.github.io |