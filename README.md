# Empirical Response Exponents and Geometric-Medium Information in Galaxy Rotation Curves

This repository contains the public manuscript archive for:

**Mohammed Messaoudene, "Empirical Response Exponents and Geometric-Medium Information in Galaxy Rotation Curves."**

The paper presents an empirical, falsifiable response-framework analysis of galaxy rotation curves. It tests whether residuals at fixed baryonic acceleration contain information tied to baryonic composition and profile geometry. The manuscript is intentionally framed as an empirical response model, not as a completed self-consistent physical theory.

## Contents

- `GMR_EMPIRICAL_RESPONSE_MANUSCRIPT.pdf` - compiled manuscript.
- `GMR_EMPIRICAL_RESPONSE_MANUSCRIPT.tex` - LaTeX source.
- `GMR_EMPIRICAL_RESPONSE_REFERENCES.bib` - bibliography.
- `figures/` - manuscript figures.
- `aastex631.cls`, `aasjournal.bst` - LaTeX support files used for this build.

## Build

The manuscript was built with:

```powershell
pdflatex -interaction=nonstopmode GMR_EMPIRICAL_RESPONSE_MANUSCRIPT.tex
bibtex GMR_EMPIRICAL_RESPONSE_MANUSCRIPT
pdflatex -interaction=nonstopmode GMR_EMPIRICAL_RESPONSE_MANUSCRIPT.tex
pdflatex -interaction=nonstopmode GMR_EMPIRICAL_RESPONSE_MANUSCRIPT.tex
```

## Data Availability Boundary

This archive does **not** redistribute raw SPARC, LITTLE THINGS, THINGS, or author-supplied component tables. Original survey data should be obtained from the cited source papers and public survey archives. Additional THINGS/LITTLE THINGS component tables supplied by S.-H. Oh are treated as source material for validation and are not redistributed here.

Only the manuscript, figures, references, and publication metadata are included.

## Scope

The manuscript reports an empirical channel-separation signal and a compact transition prescription for response-exponent phenomenology. It does not claim a derivation of the dark-matter phenomenology from first principles, a complete covariant action, or a closed relativistic/lensing theory.

## License

Unless otherwise noted, the manuscript text and original figures in this repository are released under the Creative Commons Attribution 4.0 International license (CC BY 4.0). Third-party LaTeX class/style files retain their original upstream licenses.
