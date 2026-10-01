# Credit Card Customer Churn and Engagement Analysis

An Excel project exploring customer churn, transaction activity, inactivity, and opportunities for retention review.

## Dataset
- 10,127 customers
- 1,627 churned customers
- 8,500 existing customers
- Overall churn rate: 16.07%

## Tools and Methods
Microsoft Excel, conditional aggregation, percentile calculations, array formulas, customer segmentation, and charts.

## Analysis
- Compare churned and existing customers by spending, transaction frequency, inactivity, product relationships, and utilization.
- Explore differences across income groups and card categories.
- Apply a rule-based watchlist to prioritize existing customers for review.

## Key Findings
- Churned customers averaged about 45 transactions, compared with 69 for existing customers.
- Churn rate was approximately 5.08% among customers inactive for 0–1 months, compared with 24.56% among those inactive for 4+ months.
- The retention rule flagged 3,404 existing customers, including 1,120 high-priority cases.

## Retention Indicators
Each customer receives one flag for each condition:
1. At least 3 inactive months.
2. Q4/Q1 transaction-count ratio below 0.617.
3. Q4/Q1 transaction-amount ratio below 0.643.
4. Total transaction count below 54.
5. Two or fewer product relationships.

The percentile thresholds come from existing customers.

- Watchlist: at least 2 flags.
- High priority: at least 3 flags.

## Interpretation
These flags support exploratory retention prioritization. They are not validated predictions or evidence of customers retained.

The data contains annual and Q4/Q1 indicators, not a month-by-month transaction history. Associations do not establish causation.

## How to Explore
Download `BankChurners.xlsx` and open it in Microsoft Excel:
- `BankChurners`: source data.
- `Churn Analysis`: metrics, comparisons, retention rules, and charts.

## Next Steps
Validate the rules on additional data and evaluate retention actions before operational use.
