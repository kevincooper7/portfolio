# Revenue Cycle Process Automation Opportunity

## Objective
To identify inefficiencies and high-friction areas in the revenue cycle and propose automation opportunities.

## Dataset
Generated sample data of 1,500 revenue transactions:
- `transaction_id`
- `department`, `process_step`
- `manual_touch` (1/0)
- `processing_time_min`
- `error_flag` (1/0)
- `timestamp`

## Key Metrics
- Manual vs automated rate
- Error rate per process step
- Processing time distributions

## Tools Used
- Python (pandas, seaborn)
- Power BI (process analysis dashboard)

## Results
- 48% of steps still manual
- Manual steps take 3x longer on average
- Error rate: **manual = 12%**, **automated = 2%**

## Insights
Focus automation efforts on **claims validation** and **billing adjustments**. High time and error rates indicate priority.

## Dashboard Features
- Touchpoint analysis
- Department and step-level filtering
- Time and error trends

## Files
- `revenue_automation_pipeline.ipynb`: EDA and summary
- `revenue_reporting_dashboard.pbix`: Visual insights
- `revenue_data.csv`: Synthetic transaction data
