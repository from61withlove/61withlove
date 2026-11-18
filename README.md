# 61withlove design

Portfolio site: five projects by a multidisciplinary designer (brand, web, product, objects).

A single static page with no build step: `index.html` plus the images in `img/`. The hero is a raw WebGL shader (liquid glass metaballs refracting the wordmark), with a flat fallback for devices without WebGL.

## GitHub Pages

Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`.

## Local preview

```sh
python3 -m http.server
```

Then open http://localhost:8000.
