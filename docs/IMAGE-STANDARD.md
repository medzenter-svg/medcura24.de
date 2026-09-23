# Image standard — Medcura24

All photographic raster assets must be WebP before they are committed.

- Hero: max 1600 px wide, target <= 180 KB where quality permits.
- Content image: max 1200 px wide, target <= 120 KB.
- Card/portrait: generate the rendered dimensions needed; avoid shipping oversized originals.
- Use descriptive lowercase filenames, e.g. `klinikum-muenchen.webp`.
- Add explicit width and height in HTML to reduce layout shift.
- Use `loading="lazy"` and `decoding="async"` below the fold.
- Hero/LCP imagery must not be lazy-loaded; use fetchpriority="high" when appropriate.
- Always provide useful Russian alt text for informative images; decorative images use alt="".
- Do not commit JPG/JPEG/PNG photographs. SVG is permitted for logos and simple vector icons.
- Do not use clinic/professor photography until publication rights/source are confirmed.
