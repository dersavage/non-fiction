# Non-fiction Reviews

Hugo blog using the [Emacs](https://themes.gohugo.io/themes/hugo-emacs-theme/) theme.
Live at https://dersavage.github.io/non-fiction/.

- Posts: `content/posts/*.md` (front matter: `title`, `date`, `rating`)
- Build locally: `hugo server` (needs Hugo **extended**)
- Deploys on every push to `main` via `.github/workflows/pages.yml`
- The theme is vendored in `themes/emacs` with fixes so it works under the `/non-fiction/` subpath:
  menu and font links use subpath-aware URLs, the `g h` / `g p` shortcuts read a `site-base` meta tag,
  and the About link points to the main site; the Tags, Categories and Contact menu entries were removed
  because those pages don't exist here.
