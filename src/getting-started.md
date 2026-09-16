# Getting Started

This site is built with [mdBook](https://rust-lang.github.io/mdBook/).

## Local development

```bash
# Build the static site into ./book
mdbook build

# Serve with live reload at http://localhost:3000
mdbook serve --hostname 0.0.0.0 --port 3000
```

## Adding content

1. Create a Markdown file under `src/`.
2. Add a link to it in `src/SUMMARY.md` so it appears in the sidebar.
3. Rebuild or let `mdbook serve` reload automatically.
