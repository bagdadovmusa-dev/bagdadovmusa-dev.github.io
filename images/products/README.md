# Product Images — Placeholders

These image paths are referenced in `src/content/products/products.json`
but no real product photography exists yet. The Zod schema only validates
that the `images` field contains at least one non-empty string path — it
does not require the binary file to exist on disk, so the build is not
blocked by missing images at this phase.

No image files exist in this folder yet — not even placeholders. The paths
below are referenced by `products.json` but will 404 until real files are
added. Phase 2 must either add real product photos or generate temporary
placeholder images (square or 4:5 aspect ratio, compressed, max ~1200px per
PITFALLS.md Pitfall 4) before the catalog grid renders `<img>` tags.

Files needed (owner replaces with real photos later):
- chanel-no5-edp-100
- chanel-coco-mademoiselle-edp-50
- dior-sauvage-edt-100
- dior-jadore-edp-50
- tomford-black-orchid-edp-50
- tomford-oud-wood-edp-50
- ysl-libre-edp-90
- armani-acqua-di-gio-edt-100
