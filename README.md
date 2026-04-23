# assets

Static assets (images, icons, misc files) served via [jsDelivr](https://www.jsdelivr.com/) CDN for Kazuha's personal sites.

## URL pattern

```
https://cdn.jsdelivr.net/gh/KKazuhaK/assets@main/<path>
```

Pin to a tag or commit SHA instead of `@main` for stable/cached links:

```
https://cdn.jsdelivr.net/gh/KKazuhaK/assets@v1/<path>
https://cdn.jsdelivr.net/gh/KKazuhaK/assets@<sha>/<path>
```

## Layout

Top level is organized by **site**. Everything under each site is free-form per-site.

```
assets/
├── ics.uci.edu/        # https://ics.uci.edu/~kazuhak/
│   └── <course>/<week>/...
└── (other sites later)
```

## Notes

- Public repo (required for jsDelivr).
- jsDelivr hard limit: ~50 MB per file. Keep individual images well under that.
- Prefer compressed formats (WebP / optimized PNG / SVG) over raw PNGs.
