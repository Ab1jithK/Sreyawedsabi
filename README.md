# Sreya weds Abi 💍

Wedding invitation website.

## 🔗 Live site

**https://ab1jithk.github.io/Sreyawedsabi/**

## About

- Exported from Framer and hosted on GitHub Pages (deployed from the `main` branch, root folder).
- `index.html` is the page; `assets/` holds the images, fonts and scripts; `f2c-sw.js` is a service worker that serves Framer asset requests from the local `assets/` folder.

## Updating the site

1. Edit or replace the files (e.g. a fresh Framer export).
2. Commit and push to `main`:
   ```sh
   git add -A
   git commit -m "Update invitation"
   git push
   ```
3. GitHub Pages redeploys automatically within a minute or two.

> If you re-export from Framer, re-apply the subpath fixes: register the service worker with
> `new URL("f2c-sw.js",location.href)` in `index.html`, use `new URL(n,self.location.href)` in
> `f2c-sw.js`, and point the `og:url` / `og:image` / `twitter:image` meta tags at the GitHub Pages URL.
