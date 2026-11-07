# Non-fiction Reviews

Hugo blog using the [YinYang](https://themes.gohugo.io/themes/hugo-theme-yinyang/) theme.
Live at https://dersavage.github.io/non-fiction/ once GitHub Pages is switched to "GitHub Actions".

- Posts: `content/posts/*.md` (front matter: `title`, `date`, `rating`)
- Build locally: `hugo server` (needs Hugo **extended** >= 0.158)
- Deploys on every push to `main` via `.github/workflows/pages.yml`
- The theme is vendored in `themes/yinyang` with two small fixes so links work under `/non-fiction/`
  (brand link and 404 link now use `.Site.Home.RelPermalink`).
