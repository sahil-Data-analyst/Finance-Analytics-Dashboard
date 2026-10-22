# Finance Analytics Dashboard — Insights

## Executive summary
This notebook analyses a generated sample dataset containing 60 department-month records across 12 months and five departments. Since the dataset is synthetic, the following are practice findings rather than real-world company conclusions.

## KPI snapshot
| Metric | Result |
|---|---:|
| Total revenue | ₹7,360,289 |
| Total expenses | ₹4,804,832 |
| Total profit | ₹2,555,457 |
| Overall profit margin | 34.72% |
| Records over budget | 28 of 60 |

## Findings
1. **Overall profitability:** The sample generated ₹2,555,457 profit from ₹7,360,289 revenue, producing an overall profit margin of 34.72%.
2. **Department comparison:** Operations has the highest total profit in this sample at ₹662,705. Marketing has the lowest total profit at ₹361,323.
3. **Monthly trend:** November 2025 is the highest-profit month (₹331,694), while September 2025 is the lowest-profit month (₹39,982).
4. **Budget monitoring:** 28 of 60 department-month records have expenses greater than their assigned budgets. This shows how a budget-status flag can help direct attention to possible overspending.
5. **Department budget comparison:** Departments with total expenses above their total budgets in the generated sample: Finance, Marketing.
6. **Analytical value:** Grouping by month and department makes it easier to compare trends, identify differences in profitability, and focus on budget variance instead of reviewing individual rows manually.

## Recommendations a business analyst could explore with real data
- Investigate repeated budget overruns by month, department, and expense category.
- Compare revenue and expense growth to understand what is driving profit changes.
- Add filters for department and month to make the dashboard easier to explore.
- Validate unusual values and reconcile the data with the finance system before sharing conclusions.
- Add year-over-year comparison and forecasts when enough historical data is available.

## Important caveat
The notebook creates random sample data with a fixed seed for repeatable practice. These results are not evidence about any real company or department.
