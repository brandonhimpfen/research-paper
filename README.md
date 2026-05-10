# Research Paper Boilerplate

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
