# Slides for the assistant lecturer interview

This repository generates the slides for the teaching demonstration in the 2026 assistant lecturer interview (Department of Statistical Sciences, University of Cape Town).

The demonstration is a 12-minute lecture (plus 3 minutes of questions) introducing **multiple linear regression** to students who have just covered simple linear regression in STA1000.

## Contact

For more information, please contact:

- Miguel J. Rodo: miguel.rodo@uct.ac.za

## Links

- GitHub repository: <https://github.com/MiguelRodo/lectures> (branch `slides-2026-al-interview`)

## Details

- **Slides**: `IntroductionMultipleLinearRegression.qmd` (Quarto, Beamer PDF output, 16:9).
- **Data**: simulated advertising data, generated in the slides (100 markets, as in the STA2005S Week 3/4 slides). Radio spend is correlated with TV spend, but revenue depends on TV spend only. So radio looks useful in a simple regression but not once TV is included.
- **Software**: R with the packages listed in `DESCRIPTION` (install with `remotes::install_deps()`), Quarto and a LaTeX distribution.
- **Build**: the project is managed with [`projr`](https://github.com/SATVILab/projr).
  - `projr::projr_build_dev()` renders a development version.
  - `projr::projr_build_minor()` (or `_patch()`/`_major()`) renders a versioned build into `docs/`.
  - Builds do not commit or push to Git (`build: git: false` in `_projr.yml`).
- **References**: `references/` holds the STA1000 and STA2005S material the slides build on, the handwritten plan, and web research on teaching demonstrations and slide design (`references/research/`).
