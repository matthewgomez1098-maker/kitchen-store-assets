# kitchen-store-assets

Product photography for the kitchen store Shopify catalog.

`images/` holds 54 JPEGs at 2048×2048 — Shopify's recommended maximum. These are
AI-restaged product photos built image-to-image from supplier reference photos,
so the product itself stays accurate while the lighting and staging are
consistent across the catalog.

Naming: `<SKU>.jpg` is the hero. `<SKU>-2` / `-3` / `-4` are the additional
gallery images, in display order (angle, detail, lifestyle).

These are referenced by URL from the Shopify product import CSV, e.g.

    https://raw.githubusercontent.com/matthewgomez1098-maker/kitchen-store-assets/main/images/BURR-CONE-01.jpg

Once a product is proven, re-upload its images to Shopify Files so the storefront
does not depend on an external host.
