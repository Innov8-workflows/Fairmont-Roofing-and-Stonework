# Fairmont Roofing and Stonework

**Staging preview of the full site build-out.** 52 pages.

Served from a GitHub Pages project subfolder, so this build carries
`noindex,nofollow` on every page and a `robots.txt` that disallows everything -
a preview must never compete with the client's live WordPress site in search.

**Never hand-edit anything here.** This folder is build output. The source lives in
the monorepo at `Claude v4/Fairmont Roofing & Stonework`:

```
node generate.js                                        -> _site/     (production, base /)
STAGING_BASE=Fairmont-Roofing-and-Stonework node generate.js -> _staging/ (this)
```

URLs mirror the live WordPress site at fairmontroofingandstonework.co.uk so nothing
that currently ranks 404s at switchover.
