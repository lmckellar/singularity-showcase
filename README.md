# Singularity Showcase

Interactive Three.js black hole explorer built as a lightweight technical showcase.

## Deployment

This is a static site. There is no build step and no backend.

Recommended Cloudflare Pages settings:

- Project name: `singularity-showcase`
- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`
- Production branch: `main`
- Custom domain: `boople.xyz`

## Local Preview

Run a static file server from this directory:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```
