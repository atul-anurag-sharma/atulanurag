# Apply the cleaned website fix

This update fixes the conflicting CSS setup, restores boxed homepage buttons,
keeps pages centered without a sidebar, and makes the top navigation visible
and usable on phones by wrapping the links into a centered row.

## Files changed

- `.gitignore`
- `_config.yml`
- `_pages/about.md`
- `_sass/custom.scss`
- `assets/css/main.scss`
- removes the unused duplicate `assets/css/custom.scss`

## Apply to your existing repository

From the extracted `academicpages-fix-overlay` folder, run:

```bash
cp -R . /Users/atulanurag/academicpages-full/
cd /Users/atulanurag/academicpages-full
rm -f assets/css/custom.scss
find . -name '.DS_Store' -delete
find . -name '.Rhistory' -delete

git status
git add -A
git commit -m "Clean website styles and fix mobile navigation"
git push origin academic-pages
```

Netlify will build automatically after the push.
