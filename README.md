# learnIAD-MA

Interactive R/learnr tutorial for individual animal data meta-analysis (IAD-MA).

## What's here
- `online script.Rmd`: main learnr tutorial (shiny_prerendered) covering IAD theory, data prep, two- and single-stage analyses for continuous/binary outcomes, and meta-regression; uses `IADdata.Rds` with packages like `dplyr`, `metafor`, `lmerTest`, `brms`, `mice`, `gtsummary`, etc.
- `online-script.html`: rendered tutorial output.
- `sketchpad.Rmd`: exercise + solution running regressions per study.
- `www/`: video assets embedded in the tutorial.
- `learnIAD-MA.Rproj`: RStudio project; `.gitignore` only ignores `.Rproj.user`.

## Run locally
1. Open `learnIAD-MA.Rproj` in RStudio.
2. Install required packages (e.g., `dplyr`, `metafor`, `lmerTest`, `brms`, `mice`, `gtsummary`, `learnr`, etc.).
3. Knit or run `online script.Rmd` as a learnr tutorial (shiny prerendered) to explore the content.
