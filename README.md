# finalproject

Yumin Min's final project for Harvard BST260, Fall 2026.

This repository contains an R package and its accompanying
[project website](https://mint0o01.github.io/finalproject/).
The website infrastructure is in place; the project proposal and analyses
are under development.

## Installation

```r
install.packages("devtools") # if needed
devtools::install_github("Mint0o01/finalproject")
data("waterborne", package = "finalproject")
```

## Building the website

Install the [Quarto command-line tool](https://quarto.org/docs/get-started/)
and the R packages `pkgdown` and `quarto`. From the repository root, run:

```r
pkgdown::build_site()
```

Commit the generated `docs/` directory to `main`. GitHub Pages publishes
the site from the `/docs` folder on that branch.

## Course resources

This project is based on Vincent Carey's
[BST260 project template](https://github.com/vjcitn/bst260project-template).
The instructor's [instructions](https://vjcitn.github.io/bst260project-template/articles/instructions.html)
and [project suggestions](https://vjcitn.github.io/bst260project-template/articles/stubs.html)
are retained as reference articles.

Contact: [ymin1@hsph.harvard.edu](mailto:ymin1@hsph.harvard.edu).
