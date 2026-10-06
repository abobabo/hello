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
then copy `landing/dist/assets/`, `landing/dist/favicon.png`, and
`landing/dist/index.html` into this repository's `pangoland/` directory.
Commit and push to `main` to deploy through the existing GitHub Pages build.
Keep the root homepage, legal pages, and `CNAME` in place.

## Jobs

https://www.edexy-learn.com/jobs/ uses the same globe banner followed by the
marketing internship posting and footer. Edit `landing/jobs.html` in the source
repository and run the same build. Copy `dist/assets/` and `dist/favicon.png` into
`jobs/`, then copy `dist/jobs.html` to `jobs/index.html`. Each page includes its own
asset snapshot, so updating one does not break the other.
