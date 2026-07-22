# Chicago Tech Circle — Curriculum Resources

A simple static site: a landing page with four module cards, plus one page per
module. Styled to match the Chicago Tech Circle color scheme. No login, no
dropdowns, no filters — just the four modules.

**Live site:** https://Tomas-Malik.github.io/CTC_S26_v2/

## Files

- `index.html` — landing page with the 4 module cards
- `module-1.html` … `module-4.html` — one placeholder page per module
- `style.css` — shared styling for every page (colors, fonts, layout)

## Adding materials to a module

Open the relevant `module-N.html` file and replace this block:

```html
<div class="placeholder-note">
  Materials for this module haven't been added yet...
</div>
```

with whatever you want that module to hold — a list of links, an embedded
Google Slides iframe, a PDF, a video, etc. The header, back link, and footer
around it don't need to change.

## Publish it on GitHub Pages

1. Create a new repository on GitHub (public repos get free Pages hosting).
2. From this folder, push it up:
   ```bash
   git init
   git add .
   git commit -m "Initial curriculum resources site"
   git branch -M main
   git remote add origin https://github.com/Tomas-Malik/CTC_S26_v2.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`, then **Save**.
5. Give it a minute, then visit `https://Tomas-Malik.github.io/CTC_S26_v2/`.

## Customizing

Every color and font is a CSS variable at the top of `style.css`:

```css
:root {
  --magenta: #a5228e;       /* CTC's brand color, pulled from ctc.uic.edu */
  --magenta-dark: #7c1c6b;  /* hover/active state */
  --ink: #201a1e;           /* body text */
  --ink-muted: #6b6270;     /* secondary text */
  --paper: #fbf8fa;         /* page background */
  --card-bg: #ffffff;       /* card background */
  --border: #ece6ea;
}
```

Retune any of these in one place and every page picks it up. Fonts are
Space Grotesk (headings) and Inter (body text), loaded from Google Fonts in
each page's `<head>`.
