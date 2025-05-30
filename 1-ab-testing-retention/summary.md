# A/B Testing for User Retention

## Objective
To evaluate whether a new onboarding experience improves user retention compared to the current process.

## Dataset
Simulated dataset of 10,000 users:
- `user_id`
- `group` (control or treatment)
- `retention_7_days` (1 if retained, 0 otherwise)
- `signup_date`
- `region`
- `device_type`

## Key Metrics
- Retention Rate (7-day)
- Uplift in retention
- Statistical significance (p-value)

## Tools Used
- Python (pandas, scipy, matplotlib)
- Power BI (retention dashboard)

## Results
- Control group retention: **38.4%**
- Treatment group retention: **41.6%**
- Uplift: **+3.2%**
- p-value: **0.0041** → statistically significant

## Insights
The new onboarding experience leads to a statistically significant improvement in user retention. Recommend full rollout.

## Dashboard Features
- Retention rate comparison
- Filter by region, device type, and signup week
- Trend line over time

## Files
- `ab_test_retention_analysis.ipynb`: Statistical testing notebook
- `retention_dashboard.pbix`: Interactive dashboard
- `user_behavior.csv`: Raw data
