# meetmoon — review draft (no photos included)

Open `index.html` in a browser to review. This draft contains **no personal portrait and no cover image**.

## Add your two untouched photographs

1. Create/keep the `assets` folder. Copy your **original** portrait into it, rename it `my-photo.jpg` (do not edit it).
2. Download a computer/workspace photo you have permission to use (e.g. from Unsplash or Pexels). Save the original as `assets/cover.jpg`.
3. In `index.html`, replace `<div class="portrait-slot" ... </div>` (the complete element) with `<img class="about-photo original-photo" src="assets/my-photo.jpg" alt="Sumaiya Akhter Moon">`.
4. In `index.html`, delete the complete `<div class="hero-placeholder">...</div>` element.
5. At the end of `style.css`, paste:

```css
.hero-photo { background: url("assets/cover.jpg") center center / cover no-repeat !important; opacity: 1 !important; }
.original-photo { width: 100%; height: auto; object-fit: contain; }
```

`object-fit: contain` and `height:auto` ensure the portrait is not cropped. Original file bytes stay unchanged.

## Education
HSC institution and dates remain **unverified placeholders**. Replace with confirmed information before publishing.

## GitHub Pages
After approval, copy these files into the local `meetmoon` repository and commit/push. Do not deploy this review draft as-is.
