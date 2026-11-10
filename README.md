# E-Commerce Sales Analysis (R)

Analysis of ~540,000 transactions from a UK-based online retailer (Dec 2010 – Dec 2011).

## Questions
1. Which products are returned the most?
2. How does UK revenue change weekly, monthly and quarterly?
3. Are orders from outside the UK significantly larger than UK orders?

## Tools
R, tidyverse (dplyr, ggplot2), lubridate

## Key findings
- Revenue pattern from UK customers
- order size comparsion between UK and other


## Data cleaning notes
- Removed warehouse adjustments (non-"C" negative quantities with no CustomerID)
- Found two very large orders that were cancelled immediately (data-entry errors)
- Last month is incomplete (data ends 9 Dec 2011)

## Data source
Daqing Chen et al., UCI Machine Learning Repository: Online Retail dataset
