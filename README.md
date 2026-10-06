# Edexy website

GitHub Pages publishes the root of this repository's `main` branch at
https://www.edexy-learn.com/. The `CNAME` keeps the existing custom domain;
https://edexy-learn.com/ redirects to the `www` address.

## Pango Land

The generated Pango Land landing page is served at
https://www.edexy-learn.com/pangoland/.

Its editable Vite source lives in `landing/` in the
[`EDEX-LEARNING/languagegaming`](https://github.com/EDEX-LEARNING/languagegaming)
repository. To update it, run `npm ci`, `npm test`, and `npm run build` there,
then replace only this repository's `pangoland/` contents with the complete
`landing/dist/` output. Commit and push to `main` to deploy through the existing
GitHub Pages build. Keep the root homepage, legal pages, and `CNAME` in place.
