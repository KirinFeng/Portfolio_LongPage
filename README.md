# Kirin Feng · Cybersecurity Portfolio

Single-page portfolio covering application security, penetration testing, threat modeling, intrusion detection and digital forensics projects.

**Live site:** https://kirinfeng.github.io/Portfolio_LongPage/

Classic version: https://kirinfeng.github.io/Portfolio/

## Sections

About · Skills · Projects · Experience · Contact

## Project structure

```text
.
├── .nojekyll        # Publish as a plain static site (no Jekyll processing)
├── favicon.svg      # Site icon
├── index.html       # Entire page: markup, inline CSS and inline JavaScript
├── resume.pdf       # Downloadable résumé ("Download Résumé" buttons)
└── img/
    └── icon-face.jpg  # Profile photo
```

No framework, build step or dependencies. Fonts (Inter, JetBrains Mono) are loaded from Google Fonts.

## Run locally

Open `index.html` directly, or serve the folder to test the résumé download:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating the résumé

Replace `resume.pdf` with a file of the same name. The classic version keeps its own copy in the `Portfolio` repository, so update both if they should stay in sync.
