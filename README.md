# Empirical Response Exponents and Geometric-Medium Information in Galaxy Rotation Curves

This repository contains the files for the preprint:

**Empirical Response Exponents and Geometric-Medium Information in Galaxy Rotation Curves**  
Mohammed Messaoudene

## Status

This is an arXiv-ready preprint prepared for author review and public circulation. It is **not** presented as a final journal-accepted version.

The manuscript keeps the claim boundary explicit:

- SPARC and the direct LSB component sample favor the fixed \(p \simeq 0.298\) comparison branch.
- LITTLE THINGS proxy and vector-recovered subsets lean toward \(p=0.5\), without decisive significance.
- The result is not a universal exponent claim and not a dark-matter solution.
- Direct component evidence and proxy/vector-recovered evidence are kept separate.

## Repository contents

- `manuscript/R145_MANUSCRIPT.pdf`: compiled manuscript.
- `manuscript/R145_MANUSCRIPT.tex`: LaTeX source.
- `manuscript/R145_REFERENCES.bib`: BibTeX references.
- `figures/`: figures used in the manuscript.
- `tables/R142_LT_VECTOR_VALIDATION_TABLE.csv`: LITTLE THINGS vector-validation table.
- `docs/`: brief quality-control note.
- `arxiv_upload/`: files prepared for arXiv upload.

## Compile

The manuscript is written in AASTeX 6.3.1. Compile from the repository root so the `figures/` paths resolve:

```bash
tectonic --outdir manuscript manuscript/R145_MANUSCRIPT.tex
```

The `arxiv_upload/R145_ARXIV_SOURCE.zip` file contains the TeX, references, figures, and table needed for arXiv upload.

## Remaining journal-grade work

Before a prestige-journal submission, the following upgrades remain necessary:

1. Free-\(p\) fits with uncertainty intervals for each data set.
2. Error-weighted residual or reduced-\(\chi^2\) checks using radial velocity uncertainties.
3. Bootstrap intervals for the principal RMSE comparisons.
4. Broader direct-component external validation.
5. DOI-backed reproducibility archive.

## License

Manuscript text, figures, and derived tables in this repository are released under CC BY 4.0 unless a third-party data source states otherwise. Original survey products remain with their respective archives and should be cited through the original SPARC, LITTLE THINGS, and LSB source papers.
