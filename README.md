# Atul Anurag — Academic Website

Source code for [www.atulanurag.com](https://www.atulanurag.com/), built with HugoBlox/Hugo and deployed through Netlify.

## Deployment

Pushing to the `main` branch triggers a Netlify build. Deployment settings are defined in `netlify.toml`.

## Local setup

```bash
npm ci
hugo server
```

Use Hugo Extended and the versions specified in `netlify.toml`.

## Repository hygiene

Generated output (`public`, `resources`, and `node_modules`) is intentionally excluded from Git. Netlify regenerates these during deployment.
