# gigaresearch-map-icons

Route-marker icons for **GigaResearch** custom Google My Maps (`maps export --icon-style chip`).

Each icon combines a **category colour + glyph + visiting-order number** in one small PNG, referenced by
URL from exported KML so My Maps can render it; served free via jsDelivr. **Do not hand-edit** — regenerate
with `scripts/publish_map_icons.sh` in the main repo.

```
icons/<category>/<n>.png        e.g. icons/food/1.png
```

Categories: food, cafe, sight, hotel, transport, shopping, bar, nature, other. Numbers 1..99 (variant c).

CDN: `https://cdn.jsdelivr.net/gh/nekith78/gigaresearch-map-icons@master/icons/<category>/<n>.png`

Contains only generated marker graphics — no code, no secrets.
