# crownfusion.github.io

Project page for **CrownFusion: 3D Dental Crown Generation Using Geometry Images and Latent Diffusion** (MICCAI 2025).

Live at <https://crownfusion.github.io>.

## Structure

```
_config.yml              site metadata + link URLs
_layouts/default.html    page shell (all CSS lives here)
index.md                 page content
static/                  figures
```

## Editing

- **Links** (paper / arXiv / code / dataset): edit the `*_url` values in `_config.yml`.
  `#` means "not published yet" — the button renders but goes nowhere.
- **Content**: edit `index.md`. It is HTML inside a Markdown file, so Jekyll passes it through untouched.
- **Figures**: drop PNGs in `static/` and reference with
  `{% raw %}{{ '/static/name.png' | relative_url }}{% endraw %}`.

## Local preview

Requires Ruby:

```sh
gem install jekyll bundler
jekyll serve
```

Then open <http://localhost:4000>.
