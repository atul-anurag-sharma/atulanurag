# Academic Pages migration

This package is an **overlay for the official Academic Pages v0.9 template**. It contains your converted content and configuration, not the template engine itself.

1. Create a backup branch of the current Hugo site.
2. Use the official `academicpages/academicpages.github.io` template to create or populate a separate migration branch/repository.
3. Copy all files from this package into the root of that Academic Pages repository and replace matching files.
4. Keep the template's `_includes`, `_layouts`, `_sass`, JavaScript assets, `Gemfile`, and GitHub workflows.
5. Run `bundle install` and `bundle exec jekyll serve` for a local preview.
6. In Netlify set the build command to `bundle exec jekyll build` and publish directory to `_site`, or use the included `netlify.toml`.
7. Only point the existing Netlify production site to the Jekyll branch after previewing it. The custom domain remains attached to Netlify.

The converted content includes biography, research, publications, talks, teaching, CV, dissertation, publication PDFs, and profile image.
