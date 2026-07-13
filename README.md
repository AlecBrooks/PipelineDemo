# Python-to-R Data Pipeline Demonstration

A small reproducible data analysis project built with Python, R, Quarto, and the Palmer Penguins dataset.

Python is used to download and clean the data. The prepared pandas DataFrame is then passed to R with `reticulate` for linear regression, visualization, and prediction.

## Tools

- Python
- pandas
- R
- ggplot2
- reticulate
- Quarto

## Render the report

```bash
quarto render report.qmd