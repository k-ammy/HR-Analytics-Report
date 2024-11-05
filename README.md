# HR Analytics Report

## Report Overview
This repository contains an HR analytics report focused on key employee metrics, including attrition rates, turnover rates, and employee counts by department, using Excel and Power BI.

## Table of Contents
- [Overview](#overview)
- [Structure](#structure)
- [Employee Metrics](#employee-metrics)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Structure
- `data/`: Contains the datasets used for analysis.
- `analysis/`: Excel and Power BI files for data analysis.
- `visualizations/`: Graphical representations of the data.
- `reports/`: Summary reports of the findings.

## Employee Metrics
- **Total Employees by Department**: The number of active employees in each department.
- **Turnover Rate**: The percentage of employees that left the organization during a specific period.
- **Attrition Rate**: The percentage of employees who resigned.

## Getting Started
data/employee_data.xlsx
Create an Excel file named employee_data.xlsx with the following sample data:

|Header 1| Header 2| Header 3| Header 4| Header 5| Header 6|
|Employee ID|	Name |	Department|	Date Joined|	Date Left|	Status|
|1|	John Doe|	Sales|	2020-01-15|		Active| | 
|2|	Jane Smith|	HR|	2019-03-22|	2023-05-15|	Resigned|
|3|	Alice Brown|	IT|	2021-07-10|		Active| |
|4|	Bob White|	Sales|	2018-09-30|	2024-01-05|	Terminated|
|5|	Chris Black|	HR|	2020-11-11|		Active| |
|6|	Anna Green|	IT|	2020-05-25|		Active| |
|7|	Mark Grey|	Sales|	2021-06-12|	2023-12-01|	Resigned|
|8|	Lisa White|	Marketing|	2022-02-10|		Active|
|9|	David Blue|	Marketing|	2019-08-15|		Active| |
|10|	Emily Red|	HR|	2021-11-01|		Active| |

3. Analysis/HR_Analysis_Excel.xlsx
In this Excel file, perform the following analyses:

Total Employees by Department: Use a PivotTable to summarize the active employees per department.
Turnover Rate: Create a new column to calculate turnover and another PivotTable for the rates.
Attrition Rate: Summarize the number of resignations and calculate the attrition rate.

4. analysis/HR_Analysis_PowerBI.pbix
In Power BI, create a report with the following visualizations:

Bar charts for:
Total Employees by Department
Turnover Rate by Department
Attrition Rate by Department
You can set these up using the data imported from employee_data.xlsx.

5. visualizations/
Save the charts you create in Excel and Power BI as images in this folder. Name them as follows:

attrition_rate_by_department.png
turnover_rate_by_department.png
employee_count_by_department.png
6. reports/HR_Analysis_Report.pdf
Compile your findings into a PDF report, summarizing:

Total employees per department
Turnover and attrition rates
Insights and recommendations based on your analysis

## Usage
Open `HR_Analysis_Excel.xlsx` for Excel analysis or `HR_Analysis_PowerBI.pbix` for Power BI visualizations.

## License
This project is licensed under the MIT License.
