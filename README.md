# HR Analytics Dashboard | Excel Project

An end-to-end HR analytics portfolio project built in **Microsoft Excel**, using a **synthetic dataset of 500 employees across 7 departments**. The workbook brings together data-quality checks, KPI calculations, departmental summaries, dashboard charts, and business recommendations.

## Project Goals

- Explore workforce composition and department-level differences.
- Track employee status, compensation, and payroll metrics.
- Compare the share of employees who left across departments, satisfaction groups, and overtime groups.
- Present findings in an Excel dashboard and business report.

## Tools and Methods

- **Microsoft Excel**: formulas, data validation, conditional calculations, and charting
- **Functions**: `COUNTIF`, `COUNTIFS`, `SUMIF`, `AVERAGEIF`, and related calculations
- **Analysis**: KPI reporting, pivot-style summary tables, and data visualization
- **Reporting**: dashboard and written business recommendations

## Dataset

The synthetic dataset contains **500 employee records**. Fields cover employee demographics, department, job title, location, hire date, employment type, salary, performance, satisfaction, overtime, training, promotion, and attrition status.

> **Note:** These are simulated records, not confidential employee information.

## Key Performance Indicators

| Metric | Value |
|---|---:|
| Total employees | 500 |
| Active employees | 448 |
| Employees who left | 52 |
| Share who left | 10.40% |
| Active employee share | 89.60% |
| Average monthly salary (active employees) | 721,629 AMD |
| Total monthly payroll (active employees) | 323,290,000 AMD |
| Departments | 7 |

The **10.40%** figure is the proportion of records marked as having left; it should **not** be interpreted as an annual employee turnover rate.

## Dashboard Visualizations

The `HR_Dashboard` worksheet includes six KPI cards and charts for:

1. Active employees by department
2. Average salary by department
3. Active versus left employees
4. Share who left by department
5. Share who left by satisfaction level
6. Share who left by overtime level

## Selected Findings

- **IT** has the highest average salary among active employees, while **Customer Support** has the lowest.
- **Sales** has the highest department-level share of employees who left (**18.03%**).
- The workbook's **Low Satisfaction** group shows a **0.00%** share who left under its current grouping and calculation.
- The **High Overtime** group (more than 20 hours per month) shows a **19.51%** share who left.

These findings describe the synthetic dataset. They do not establish cause-and-effect relationships.

## Business Recommendations

- Review workload distribution and overtime practices.
- Gather employee feedback to understand satisfaction drivers.
- Evaluate salary competitiveness before making compensation changes.
- Investigate the comparatively high share of employees who left in Sales.

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `Employees` | Source records and calculated employee attributes |
| `Departments` | Department reference information |
| `Data_Dictionary` | Explanation of dataset fields |
| `Project_Tasks` | Analysis tasks and workflow |
| `Data_Quality` | Data-quality checks |
| `KPI_Analysis` | HR KPI calculations |
| `Pivot_Analysis` | Pivot-style analysis summaries |
| `Chart_Data` | Data used by charts |
| `HR_Dashboard` | KPI cards and visualizations |
| `Business_Report` | Executive summary, findings, and recommendations |

**Important:** `Pivot_Analysis` contains summary tables; these are not native, interactive Excel PivotTables.

## Open the Project

**[Download the Excel workbook](HR_AnalyticsProject.xlsx)**

1. Download the `.xlsx` file from the link above.
2. Open it in Microsoft Excel.
3. Start with `HR_Dashboard` for an overview.
4. Explore `KPI_Analysis` and `Pivot_Analysis` for supporting calculations.
5. Read `Business_Report` for conclusions and recommendations.

## Limitations

- The dataset is synthetic and is intended for practice and portfolio demonstration.
- Attrition measures are shares of records by status, not time-based turnover rates.
- The summary tables are pivot-style outputs, not interactive PivotTables.
- Differences between groups are descriptive and do not demonstrate causation.

## Author

**Anna Yeghiazaryan**  
Data Analytics Portfolio Project  
**Tools:** Microsoft Excel
