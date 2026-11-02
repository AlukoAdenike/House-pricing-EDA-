# House Price Dataset — Exploratory Data Analysis

## Project objective
Explore the Kaggle House Prices training dataset, understand its structure and data quality, summarize `SalePrice`, visualize patterns, and inspect correlations between numerical variables.

## Folder structure
- `Src/`: Jupyter notebook with the EDA workflow.
- `Data/`: `train.csv` dataset used in the analysis.
- `Docs/`: one-page PDF report.
- `Results/plots/`: generated visualizations.


## How to run
1. Download or clone this repository.
2. Open a terminal in the repository root.
3. Start Jupyter with `jupyter notebook`.
4. Open `Src/house_price_eda.ipynb`.
5. Run cells from top to bottom.

The notebook reads the dataset using `Data/train.csv`, so run it from the repository root. If your notebook environment uses a different working directory, update the CSV path accordingly.

## Key initial findings
- The file contains 1,460 rows and 81 columns.
- `SalePrice` has 1,460 observed values and no missing values in this file.
- Exact duplicate rows: 0.
- `SalePrice` mean: approximately $180,921; median: $163,000; range: $34,900–$755,000.
- Strong positive numerical correlations with `SalePrice` include `OverallQual` (r ≈ 0.791) and `GrLivArea` (r ≈ 0.709).

## Notes
Correlation is not causation. 