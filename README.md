# Singularity Showcase

Interactive Three.js black hole explorer built as a lightweight technical showcase.

## Deployment

This is a static site deployed with Cloudflare Workers static assets. There is no build step and no backend.

Recommended Cloudflare Workers Git deployment settings:

- Project name: `singularity-showcase`
- Production branch: `main`
- Build command: leave blank
- Deploy command: `npx wrangler deploy`
- Non-production branch deploy command: `npx wrangler versions upload`
- Root directory: leave blank
- Builds for non-production branches: optional; leave enabled if you want preview deployments
- Custom domain: `boople.xyz`

## Local Preview

Run a static file server from this directory:

```bash
python3 -m http.server 8080 --directory public
```

Then open:

```text
http://localhost:8080
```
