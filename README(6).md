# Finance Analytics Dashboard — Basic to Intermediate

## Project overview
This project demonstrates a Python-based finance analytics workflow using a generated sample dataset for 12 months (January–December 2025) and five departments: Technology, Marketing, Operations, Human Resources, and Finance. It covers data preparation, financial KPI calculations, monthly trend analysis, department performance, budget comparisons, visualisation, and CSV export.

> **Data note:** The figures are synthetic sample data generated in the notebook, not real company financial results. Insights below describe this sample dataset only.

## Tools and libraries
- Python
- Pandas — data cleaning, grouping, and summaries
- NumPy — calculated fields and conditional logic
- Plotly Express — interactive charts
- Matplotlib — plotting library imported in the notebook
- ipywidgets — imported for interactive filter exploration

## Main workflow
1. Import the analysis and visualisation libraries.
2. Generate sample monthly revenue, expenses, and budget values for five departments.
3. Inspect data types, missing values, and duplicate rows; convert data types and clean the records.
4. Calculate Profit, Profit Margin, Budget Variance, and Budget Status.
5. Calculate overall financial KPIs.
6. Analyse monthly revenue, expenses, and profit, including a three-month rolling revenue average.
7. Compare department-level revenue, expenses, profit, and profit margin.
8. Compare actual expenses with budgets.
9. Export the analysed dataset and department summary to CSV.

## Key results from this sample dataset
- Total revenue: ₹7,360,289
- Total expenses: ₹4,804,832
- Total profit: ₹2,555,457
- Overall profit margin: 34.72%
- Department-month records above budget: 28 out of 60
- Highest total-profit department: Operations (₹662,705)
- Lowest total-profit department: Marketing (₹361,323)
- Highest-profit month: November 2025 (₹331,694)
- Lowest-profit month: September 2025 (₹39,982)

## Output files
- `Finance_Analytics_Dashboard_Original.ipynb` — original notebook and code
- `Original_Notebook_Code.md` — code listing in Markdown
- `finance_data_analysed.csv` — row-level analysed sample data
- `department_finance_summary.csv` — department-level summary
- `budget_summary.csv` — department-level budget comparison
- `screenshots/` — dashboard visual references

## How to run
1. Open Google Colab or Jupyter Notebook.
2. Upload `Finance_Analytics_Dashboard_Original.ipynb`.
3. Run the notebook cells from top to bottom.
4. If using Jupyter locally, install the required libraries if they are not already available: `pandas`, `numpy`, `matplotlib`, `plotly`, and `ipywidgets`.

## Limitations
The dataset is randomly generated and does not represent real financial statements. The notebook is a learning project; any business decisions would require validated real data and additional context.
