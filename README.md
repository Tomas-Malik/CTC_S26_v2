# Chicago Tech Circle — Curriculum Resources

A simple static site: a landing page with four module cards, plus one page per
module. Styled to match the Chicago Tech Circle color scheme. No login, no
dropdowns, no filters — just the four modules.

**Live site:** https://Tomas-Malik.github.io/CTC_S26_v2/

## Files

- `index.html` — landing page with the 4 module cards
- `module-1.html` — Module 1 overview (Knowledge Organization) + materials, filled in
- `module-2.html` … `module-4.html` — placeholder pages, not yet filled in
- `materials/module-1/` — the actual files for Module 1 (currently: the slide deck)
- `style.css` — shared styling for every page (colors, fonts, layout)

## Adding materials to a module

`module-1.html` is now a working example of the pattern: an overview block
(TL;DR, prerequisites, what's needed, who it's for, outcomes) followed by a
**Materials** section linking to files in `materials/module-N/`.

To fill in Module 2, 3, or 4:

1. Drop the files for that module into a new `materials/module-N/` folder.
2. Open `module-N.html` and replace the `placeholder-note` block with the
   same structure `module-1.html` uses — copy its overview + materials
   markup and swap in that module's content.
3. Link to the new files with a relative path, e.g.
   `materials/module-2/whatever-the-file-is.pptx`.

The header, back link, and footer around it don't need to change.

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
  --navy: #001e62;          /* UIC Navy Pier Blue, paired with the magenta */
  --navy-tint: #e9edf6;     /* light navy background, used on module pages */
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
