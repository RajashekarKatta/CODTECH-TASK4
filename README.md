Project Overview: Automated Sales Report Generation
This project involves creating an automated report generation system using Python, which reads data from a CSV file, processes the data, generates a bar chart, and compiles everything into a PDF report.

Key Objectives:
Data Handling:

The script reads sales data from a CSV file (sales_data.csv), which contains sales data by product, and processes it to summarize the total revenue by product.
Data Visualization:

A bar chart is generated to visually represent the revenue of different products. The chart is saved as an image file (bar_chart.png).
PDF Report Generation:

The report is created using the FPDF library in Python. It includes:
A title.
The generated bar chart.
A summary of revenue by product.
The report is saved as a PDF file (sales_summary_report.pdf).
Workflow:
CSV File: The script loads the CSV file, which contains two columns: Product and Revenue.
Data Processing:
The script groups the data by Product and calculates the sum of the Revenue for each product.
Chart Generation:
A bar chart is generated using the Matplotlib library, displaying the total revenue for each product.
PDF Creation:
A PDF report is generated using the FPDF library. The bar chart is inserted into the report, followed by a list of revenue summaries for each product.
Final Output:
The output includes two files:
bar_chart.png – The visual chart.
sales_summary_report.pdf – The comprehensive PDF report with the summary and chart.
Technologies Used:
Python Libraries:

Pandas: To read and process the CSV data.
Matplotlib: To create the bar chart for visual representation.
FPDF: To generate the PDF report.
File Formats:

CSV: Used to store the raw data.
PNG: Used for saving the chart image.
PDF: Used for creating the final report.
