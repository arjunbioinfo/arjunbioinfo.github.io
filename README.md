# Mallikarjuna Thippana — Portfolio

Personal portfolio site for **Dr. Mallikarjuna Thippana**, computational biologist at Karolinska Institutet working on cancer gene regulation and 3D genomics (MYC/CTCF; GRO-seq, ATAC-seq, CUT&RUN, 4C-seq), cancer WGS and ecDNA, single-cell transcriptomics, and open-source computational methods.

**Live site:** [arjunbioinfo.github.io](https://arjunbioinfo.github.io/)

## Contents

Research profile and focus areas, experience, open-source code, publications (8 peer-reviewed articles + 3 preprints), skills, awards, education, conferences, and a downloadable CV (`CV_Thippana_2026.pdf`).

## Tech

Single-file HTML/CSS/JS — no build step, no framework.

- Canvas-based generative backgrounds (gene network, DNA helix, UMAP-style scatter, coverage track) that respond to the cursor; paused when the tab is hidden and disabled under `prefers-reduced-motion`
- Publication filter, accessible mobile menu, skip link and keyboard focus styles
- schema.org `Person` structured data and Open Graph tags
- Print/PDF-friendly stylesheet; fully responsive, dark theme

## Deployment

Hosted on GitHub Pages, served directly from `main` at the repo root.
