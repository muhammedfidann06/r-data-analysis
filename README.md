# 📊 Data Programming in R

Data-analysis exercises with the **tidyverse** (dplyr, tidyr, purrr, stringr, ggplot2),
written as a reproducible R Markdown report. Code comments are in **German (A2 level)**.

## Contents
1. Exploring & summarising data (`mtcars`) – grouping, ranking, linear regression
2. Reshaping with `pivot_longer` / `separate` (`iris`)
3. Writing functions, functional programming with `purrr`, one model per group (nested data)
4. String processing with `stringr`
5. Handling missing values and time series plots (`airquality`)

## Render
```r
install.packages(c("rmarkdown", "dplyr", "tidyr", "ggplot2", "purrr", "stringr", "tibble"))
rmarkdown::render("analysis.Rmd")   # creates analysis.html
```
Tip: push the rendered `analysis.html` too and enable GitHub Pages to show the report online.

## Skills
R · tidyverse · data wrangling · visualization · regression · reproducible reports
