# AiCube — promotional site

This is the source for the [aicube-website.github.io](https://aicube-snt.github.io/aicube-website/)
promotional site for [AiCube](https://github.com/AiCube-SNT).

## What

A single-file static landing page describing the AiCube UAV perception + control
stack. Pure HTML + CSS + inline SVG — no build step, no JS frameworks, no
external image assets (only Inter / JetBrains Mono from Google Fonts).

## Files

- `index.html` — the entire site. Edit and push; GitHub Pages re-publishes within
  ~60 s.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

The site is served from the `main` branch via GitHub Pages. Any commit to
`main` triggers a redeploy.

## License

Apache-2.0 — same as the rest of the AiCube ecosystem.
