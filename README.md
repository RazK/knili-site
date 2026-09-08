# knili-site — retired

The landing page moved into the product repo and is served by GitHub Pages from
[`RazK/knili`](https://github.com/RazK/knili) at `main` → `/docs`.

This repo existed for one reason: `knili` was private, and GitHub Pages will not
serve a site from a private repo on the free plan. It was never authored here —
a script rsynced `docs/` across and committed the result, which is why thirty of
its commits say "Update the landing page".

Now that `knili` is public, there is nothing left for this repo to do. `index.html`
is a redirect so old links keep working. Archive it once you are happy the new
URL is live; do not delete it, or the redirect goes with it.

**Do not edit anything here.** The page is generated — see `content/copy.json`
and `build/render.js` in the product repo.
