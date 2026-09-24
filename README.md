# urosavurdic.github.io

Source for <https://urosavurdic.github.io>.

One self-contained page: `index.html` carries its own CSS, its own SVG figures
and a little JavaScript for the theme toggle, the project filter and the
scroll-spy. No build step, no dependencies, no framework.

It is generated, not hand-edited. The content lives in `content/master.json` in
a separate working repo and is rendered by `build/portfolio.py`; editing
`index.html` here would be overwritten on the next build.

| Path | What it is |
|---|---|
| `index.html` | the page |
| `assets/` | rendered pages of the EESTEC recommendation letter |
| `Uros_Savurdic_Resume.pdf` | the two-page CV the page links to |
| `eestec-recommendation-letter.pdf` | the signed letter the page links to |
