# Hamdy Arkoub Personal Website

This repository contains the source files for my personal academic website:

**Website:** [https://hamdyarkoub3.github.io](https://hamdyarkoub3.github.io)

The website highlights my research in computational nuclear materials, molten salt corrosion, multiscale modeling, and my broader interest in the history of Egypt.

---

## Website Overview

The website is built as a simple static site using:

- HTML
- CSS
- JavaScript
- GitHub Pages

No external website builder or paid hosting service is used.

---

## Main Pages

### Home / About

**File:** `index.html`

The homepage introduces my academic profile, research vision, education, research themes, visual research highlights, and my personal historical framework for understanding Egypt as a long-term continuum.

Main sections include:

- Summary
- Education
- Research Vision & Themes
- Research Highlights slider
- History of Egypt as a multiscale continuum

---

### Research Projects

**File:** `research.html`

This page provides more detail about my main research directions, including:

- Molten salt corrosion
- Reactive interfaces
- Chemical ordering and alloy degradation
- Multiscale modeling
- Future work in fusion systems and engineering-scale modeling

---

### Research Outputs

**File:** `outputs.html`

This page lists my scholarly outputs in two sections:

- Journal Publications
- Presentations

Each publication includes citation information and DOI links when available.

---

### History of Egypt

**File:** `history.html`

This page presents my personal interest in Egyptian history.

The main idea is to connect the history of Egypt across multiple eras, including ancient, Greek, Roman, Islamic, Ottoman, modern, and contemporary periods, as one continuous historical system.

---

### Gallery

**File:** `gallery.html`

This page contains images related to:

- Research activities
- Academic milestones
- Conferences
- Historical interests

Images are stored in:

```text
assets/gallery/
```

---

### Contact

**File:** `contact.html`

This page includes links to my academic and professional profiles, including:

- GitHub
- Google Scholar
- ORCID
- LinkedIn
- Email link

---

## Repository Structure

```text
HamdyArkoub3.github.io/
|
├── index.html
├── research.html
├── outputs.html
├── history.html
├── gallery.html
├── contact.html
├── sitemap.xml
├── README.md
├── Hamdy_Arkoub_CV.pdf
├── google92185493536fff2f.html
|
└── assets/
    ├── style.css
    ├── script.js
    ├── profile.jpg
    ├── nav-icon.png
    ├── favicon.ico
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    ├── apple-touch-icon.png
    ├── pennstate.png
    ├── alexandria.png
    ├── theme.png
    ├── reactivity.png
    ├── fusion.jpg
    ├── history.png
    |
    ├── gallery/
    │   ├── research-1.jpg
    │   ├── conference-1.jpg
    │   └── history-1.jpg
    |
    └── publications/
        ├── acs-omega-2026.jpg
        ├── corrosion-science-2026.jpg
        ├── acs-ami-2025.jpg
        ├── cms-2025.jpg
        ├── applied-surface-science-2024.jpg
        └── scripta-2023.jpg
```

---

## Design

The website uses a dark academic theme with:

- Navy background
- Light text
- Blue accent color
- Serif headings
- Modern sans-serif body text
- Profile sidebar layout
- Card-based sections
- Graphical abstract slider for publications

The main design file is:

```text
assets/style.css
```

---

## JavaScript Features

The website uses a small JavaScript file:

```text
assets/script.js
```

This controls:

- Mobile navigation behavior
- Automatic year in the footer
- Publication graphical abstract slider

The slider shows graphical abstracts of selected publications. Each image links directly to the corresponding DOI or paper page.

---

## Google Search Console

The website was added to Google Search Console using the HTML file verification method.

Verification file:

```text
google92185493536fff2f.html
```

A sitemap was also added:

```text
sitemap.xml
```

The sitemap helps Google discover the main pages of the website.

---

## How to Update the Website

### Editing text

Most website text is inside the HTML files.

For example:

- Edit homepage content in `index.html`
- Edit research details in `research.html`
- Edit publications and presentations in `outputs.html`
- Edit history content in `history.html`

After editing, commit the changes to the `main` branch.

---

### Updating images

Most images are stored inside the `assets/` folder.

Examples:

```text
assets/profile.jpg
assets/history.png
assets/theme.png
assets/reactivity.png
assets/publications/
assets/gallery/
```

When replacing an image, keep the file name the same unless the HTML is also updated.

---

### Updating the CV

The CV file is:

```text
Hamdy_Arkoub_CV.pdf
```

To update it:

1. Delete or replace the old PDF.
2. Upload the new PDF with the same file name.
3. Commit the change.

---

## Deployment

The website is deployed using GitHub Pages.

Any change committed to the `main` branch is automatically deployed to:

```text
https://hamdyarkoub3.github.io
```

Deployment usually takes less than a few minutes.

---

## Notes

This website is intended to serve as a professional academic portfolio and personal intellectual space.

It highlights both my research identity in computational nuclear materials and my broader interest in understanding Egyptian history as a connected, long-term historical continuum.
