# Financial Data Extraction and Analysis for Apple, Microsoft, and Tesla (2021-2023)

This repository contains a Jupyter Notebook that performs financial data extraction, analysis, and summary reporting for three major tech companies—Apple, Microsoft, and Tesla—over the fiscal years 2021 to 2023.

## Project Overview
The main objective of this project is to compute and analyze the growth rates of key financial metrics such as revenue, net income, assets, liabilities, and cash flow for the selected companies. The analysis is intended to provide insights into the financial performance and trends of these companies.

## Features
- **Data Extraction**: Extracts data from financial documents such as 10-K and 10-Q reports.
- **Growth Rate Calculation**: Computes year-by-year growth rates for revenue, net income, assets, liabilities, and cash flow.
- **Summary Report Generation**: Creates a summary CSV file (`Summary_final_report.csv`) containing the overall growth rates for each company.
- **Trend Analysis (optional)**: Analyzes trends to provide insights into the financial performance of the companies.

## Files
- `Data Extraction and Initial Analysis.ipynb`: Jupyter Notebook containing the code for data extraction, analysis, and report generation.
- `Summary_final_report.csv`: Generated CSV file summarizing the growth rates for Apple, Microsoft, and Tesla over the fiscal years 2021 to 2023.
- `final_report.csv`: CSV report containing detailed financial performance metrics for Apple, Microsoft, and Tesla.
- `final_data_report.csv`: CSV report compiling raw financial data for Apple, Microsoft, and Tesla from 2021-2023.


## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DeepanshuGarg45/data-extraction-analysis-of-financial-data.git
   ```
2. Navigate to the project folder:
   ```bash
   cd financial-data-analysis
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Data Extraction and Initial Analysis.ipynb"
   ```
4. Run the cells to extract the financial data and generate the summary report.

## Dependencies
Make sure to install the following Python packages:
- `pandas`
- `numpy`
- `matplotlib` (optional for visualizations)
  
You can install these using:
```bash
pip install pandas numpy matplotlib
```
