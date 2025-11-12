README - Images and Placeholders

This file lists image assets and placeholder files used throughout the project, with paths and brief descriptions.

Folders and core assets
- assets/logo.svg
  - Primary vector logo (preferred for scalability).
- assets/logo@2x.png
  - High-DPI raster fallback for legacy use.
- assets/hero.jpg
  - Homepage hero image (recommended 1920x1080).
- assets/hero-lqip.jpg
  - Low-quality image placeholder (LQIP) for progressive loading.
- assets/backgrounds/bg-pattern.svg
  - Decorative background pattern used site-wide.
- assets/illustrations/*.png
  - Decorative illustrations; use webp/ for optimized web delivery if available.
- assets/webp/*.webp
  - WebP optimized versions of key raster images.

Icons and thumbnails
- assets/icons/search.svg
- assets/icons/menu.svg
- assets/icons/close.svg
- assets/icons/user.svg
  - Scalable SVG icon set; maintain consistent viewBox and stroke/fill conventions.
- assets/thumbnails/*.jpg
  - Content thumbnails (recommended 320x180); provide @2x where needed.

Avatars and placeholders
- assets/avatars/default-avatar.png
  - Default raster avatar used when a user has no profile image.
- assets/avatars/placeholder-avatar.svg
  - Vector avatar placeholder for lightweight display.
- assets/placeholders/image-missing.png
  - Generic "image not found" placeholder used in error states.
- assets/placeholders/transparent-placeholder.svg
  - 1x1 transparent placeholder for layout scaffolding.

Naming and usage conventions
- Use .svg for logos and icons when possible; provide .png/.jpg fallbacks with @2x suffix for high-DPI.
- Keep LQIP files in same folder with -lqip or -placeholder suffix.
- Store optimized WebP versions in assets/webp/ and serve conditionally for supported clients.
- Include meaningful alt text for all images; placeholders should indicate purpose (e.g., "default avatar").
- When adding new images, follow existing folder structure and naming conventions.

Contact / Maintenance
- Update this README when new image folders or placeholder conventions are introduced.