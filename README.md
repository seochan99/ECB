# Exposing Blindspots Project Page

This repository hosts the project page for **“Exposing Blindspots: Cultural Bias Evaluation in Generative Image Models.”**

## Quick Links

- Website: https://cmubig.github.io/ECB/
- Paper (PDF): `static/pdfs/Exposing Blindspot.pdf`
- arXiv submission: https://arxiv.org/submit/6893026/view
- Code & evaluation assets: https://github.com/cmubig/ECB
- Dataset & figures: https://huggingface.co/datasets/seochan99/ecb-datasets

## Local Preview

```bash
python3 -m http.server
```

Open `http://localhost:8000` and navigate to `index.html`.

## Structure

- `index.html` – landing page content
- `static/css` – styling (Bulma + custom tweaks)
- `static/images` – figures used on the site
- `static/pdfs` – paper and supplementary PDFs
- `static/js` – JavaScript helpers (carousel, copy button, etc.)

## Deployment

Push changes to the default branch and enable GitHub Pages:

1. Repository → Settings → Pages  
2. Source: “Deploy from a branch”  
3. Branch: `master` (or `main`) / root  
4. Save and wait for the build to finish

## Contact

Questions? Ping `chans@andrew.cmu.edu`.
