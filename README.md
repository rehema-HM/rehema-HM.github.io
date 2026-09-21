# Scientific LaTeX Technical Writing Sample

This is an original, non-confidential portfolio sample prepared to demonstrate scientific and technical LaTeX writing skills.

## Files

- `scientific-latex-sample.pdf` — compiled portfolio sample
- `scientific-latex-sample.tex` — complete LaTeX source
- `references.bib` — reusable BibTeX reference database
- `latex-sample-preview.png` — first-page preview for a web portfolio card

## Demonstrated skills

The sample includes mathematical notation and multi-line equations, automatic cross-references, algorithm pseudocode, a professional `booktabs` table, a vector workflow figure created in TikZ, citations and bibliography management, technical prose, and a reproducibility checklist.

## Build

The distributed PDF is self-contained and uses a manual bibliography so that it can compile without a BibTeX executable. The separate `references.bib` file is included to demonstrate a reusable BibTeX workflow for publisher-specific templates.

Run LaTeX twice so that cross-references settle:

```bash
pdflatex scientific-latex-sample.tex
pdflatex scientific-latex-sample.tex
```

## Portfolio note

The numerical values in the illustrative results table are synthetic and are explicitly identified as such in the document. This sample is not presented as a new empirical research study.
