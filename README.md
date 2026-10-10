# Research Paper Boilerplate

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

Reusable Overleaf + Zenodo boilerplate for Brandon Himpfen research reports.

## Files

- `main.tex` - main Overleaf-ready LaTeX paper template
- `references.bib` - BibTeX references file
- `.zenodo.json` - Zenodo metadata scaffold
- `CITATION.cff` - machine-readable citation metadata
- `README.md` - usage instructions

## Workflow

1. Upload this ZIP to Overleaf.
2. Replace placeholders in `main.tex`.
3. Add references to `references.bib`.
4. Compile and export the PDF.
5. Update `.zenodo.json` and `CITATION.cff`.
6. Upload the PDF and metadata files to Zenodo.
7. After Zenodo assigns a DOI, replace `[DOI]` in:
   - `main.tex`
   - `.zenodo.json`
   - `CITATION.cff`

## Suggested Zenodo Settings

- Resource type: `Publication > Report`
- Version: `1.0`
- License: `Creative Commons Attribution 4.0 International (CC BY 4.0)`
