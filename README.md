# Likelihood figures

Code to reproduce the figures for [link to paper].

## Repository structure

```
Likelihood_figures/
├── analysis.Rmd   # Main R Markdown source file
├── data/          # Place raw data files here (not tracked by git)
└── README.md
```

## Requirements

- R (≥ 4.0)
- The packages listed in the `packages` chunk of `analysis.Rmd`

Install dependencies from within R:

```r
install.packages(c("tidyverse", "ggplot2"))
```

## Reproducing the figures

Open `analysis.Rmd` in RStudio and click **Knit**, or run from the R console:

```r
rmarkdown::render("analysis.Rmd")
```

This produces `analysis.html` with all figures embedded.

## Data

Place the required data files in the `data/` directory before knitting.
See [`data/README.md`](data/README.md) for details.
