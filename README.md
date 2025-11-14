# Mortgage Approval Disparities: Racial Equity Analysis

Statistical analysis of mortgage approval rates across racial groups using real HMDA data.

## Overview

This project examines racial disparities in mortgage lending using 2023 California data from the CFPB. The analysis controls for income, loan amount, and other financial factors to identify potential systemic bias.

## Key Findings

- Significant approval rate gaps exist across racial groups
- Disparities persist even within same income brackets
- Differences remain statistically significant after controlling for financial factors
- Suggests systemic bias beyond creditworthiness

## Tech Stack

Python | pandas | NumPy | Matplotlib | Seaborn | scikit-learn | SciPy

## Quick Start
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scipy scikit-learn requests jupyter

# Run notebook
jupyter notebook mortgage_analysis.ipynb
```

The notebook automatically fetches real HMDA data from the CFPB API. If the API is unavailable, it uses sample data.

## Analysis Includes

1. Overall approval rates by race
2. Income-stratified analysis
3. Statistical significance testing
4. Loan-to-income ratio comparisons
5. Multivariate logistic regression

## Data Source

- **HMDA (Home Mortgage Disclosure Act)** public data
- **API:** https://ffiec.cfpb.gov/v2/data-browser-api/
- **Coverage:** California, 2023
- **Loan type:** Conventional home purchase, first lien

## Future Extensions

- Multi-state analysis
- Temporal trends over multiple years
- Lender-level comparisons
- Geographic mapping
- Correlation with historical redlining

## License

MIT




---

*Educational project analyzing public HMDA data to identify lending disparities*
