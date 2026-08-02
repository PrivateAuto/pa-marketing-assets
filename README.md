# Marketing Assets — PrivateAuto & DealNow

Central home for brand assets used across marketing and inside **Helm**.
Files here are served as direct, embeddable URLs (via `raw.githubusercontent.com`),
so they can be dropped into articles, social posts, and the Helm Brand Kit pages.

> ⚠️ This repo is **public** by design (raw URLs from private repos won't embed).
> Only put brand/marketing assets here — nothing sensitive.

## Structure

```
privateauto/
  logos/        logo-color.svg, logo-white.svg, logo-horizontal.png …
  icons/        app-icon.png, favicon.png …
  social/       og-image.png, post graphics, banners …
  one-pagers/   PDFs / images meant to be shared or linked
dealnow/
  logos/
  icons/
  social/
  one-pagers/
```

Keep the two brands in separate top-level folders so filenames never collide
and every URL is self-documenting.

## Naming

- Lowercase, hyphenated: `logo-white.svg`, `app-icon.png`, `og-image-launch.png`.
- Include the variant in the name: `-color`, `-white`, `-horizontal`, `-icon`.

## Using an asset in Helm

1. Open the file here on GitHub → click **Raw** → copy the URL
   (looks like `https://raw.githubusercontent.com/<you>/<repo>/main/dealnow/logos/logo-white.svg`).
2. In Helm → **Brand Kit → Add asset** → paste the URL, pick the type and brand.
3. Direct image URLs (logos/graphics) are **embeddable** — usable inside articles.
   Big files partners download (decks, PDFs) can also live in Google Drive.
