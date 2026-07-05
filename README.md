# All Roads Lead Home — street-graph tiles

Static street-graph tiles + manifests consumed by the **All Roads Lead Home** iOS app (on-demand street completion). Served via GitHub Pages.

- Tiles: `/<region>/14/<x>/<y>.tile.gz` — compact binary street-graph tiles (z14 grid), format v2
- Manifest: `/<region>/<region>.manifest.json` — per-region countable totals (the completion-% denominator)
- Regions: `nyc` (New York City) — more to come

## Data & license

Derived from [OpenStreetMap](https://www.openstreetmap.org/) data, © OpenStreetMap contributors, available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/). This derived database is likewise made available under the ODbL. Source extract: Geofabrik; bake pipeline: the app repo's `tools/streetpack`.
