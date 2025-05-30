# Marketing Attribution using Propensity Score Matching (PSM)

## Objective
To estimate the true incremental impact of marketing campaigns on user conversions using causal inference.

## Dataset
Synthetic dataset of 20,000 users:
- `user_id`
- `campaign_exposed` (1 or 0)
- `converted` (1 or 0)
- `age`, `gender`, `region`
- `prior_visits`, `avg_time_on_site`

## Key Metrics
- Conversion Rate
- Average Treatment Effect (ATE)
- Propensity scores
- Covariate balance

## Tools Used
- Python (pandas, sklearn, statsmodels)
- Power BI (attribution dashboard)

## Results
- Raw conversion uplift: **+4.5%**
- ATE (via PSM): **+2.1%**
- Well-balanced covariates post-matching

## Insights
Naive uplift overstates impact. PSM reveals a more realistic, still positive effect. Recommend continuing the campaign with better targeting.

## Dashboard Features
- ATE vs raw uplift comparison
- Pre/post-matching visualizations
- Breakdown by user segment

## Files
- `psm_attribution_analysis.ipynb`: Matching and inference
- `marketing_attribution_dashboard.pbix`: Attribution dashboard
- `campaign_data.csv`: Cleaned input data
