# tongzhao1030.github.io

Personal academic homepage of **Tong Zhao** — Ph.D. student at Zhejiang University &
Westlake University, working on efficient diffusion generation.

🔗 https://tongzhao1030.github.io

## Overview

A single-page static site — no build step, no Jekyll. GitHub Pages serves the files
directly (the `.nojekyll` file disables Jekyll processing).

```
index.html            # the entire page
assets/css/style.css  # styles
images/photo.jpg      # profile photo
images/papers/        # publication teaser figures
files/                # CV and paper PDFs
```

## Editing

Edit `index.html` and `assets/css/style.css` directly. To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

To add a publication, copy one `<article class="pub"> … </article>` block in the
Publications section and drop a teaser image into `images/papers/`.
