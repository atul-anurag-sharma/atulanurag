# GitHub–Netlify Migration

This website is configured for the custom domain `https://www.atulanurag.com/` and is intended to remain hosted by Netlify.

## Repository

Existing remote:

`https://github.com/atul-anurag-sharma/atulanurag.git`

## Replace the existing repository contents

From the cleaned website folder:

```bash
git clone https://github.com/atul-anurag-sharma/atulanurag.git
cd atulanurag

# Copy the contents of this cleaned package into the cloned folder,
# replacing the existing source files but keeping the .git folder.

git rm -r --cached node_modules public resources 2>/dev/null || true
git add .
git commit -m "Clean website source and Netlify deployment"
git push origin main
```

## Netlify settings

Keep the existing Netlify project. In **Project configuration → Build & deploy → Continuous deployment**, connect this GitHub repository if it is not already linked.

Use:

- Production branch: `main`
- Build command: `hugo`
- Publish directory: `public`

The repository includes `netlify.toml`, which defines these values and the required Hugo, Go, and Node versions.

## Custom domain

Do not create a GitHub Pages deployment and do not change DNS merely because the source is on GitHub. Keep `www.atulanurag.com` assigned to the existing Netlify project under **Domain management**.

## Local development

Install Node dependencies:

```bash
npm ci
```

Then run Hugo Extended using the version specified in `netlify.toml`.
