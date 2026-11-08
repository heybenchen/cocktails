# The Evening Edit

An illustrated home bar collection with twenty cocktail recipes, randomized recommendations, ingredient search, mood and spirit filters, saved favorites, and serving and measurement controls.

## Run locally

Serve `dist/` using any static HTTP server, for example:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Deploy

Import this repository in Vercel. The included `vercel.json` serves `dist/` with no install or build step. Pushes to `main` deploy automatically once connected.

## Source

- `dist/index.html`: page structure
- `dist/style.css`: responsive styling
- `dist/app.js`: interactions and recommendations
- `dist/recipes.json`: recipe data
- `dist/assets/`: cocktail illustrations

Saved favorites stay in each visitor’s browser. Recipe content is a snapshot and is not automatically synchronized with external documents.
