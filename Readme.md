# Data Analytics Internship Project
## Overview
This project involves analyzing an Excel file containing data from three
sheets: **UserDetails**, **CookingSessions**, and **OrderDetails**. The
goal of the analysis is to extract valuable insights regarding dish
popularity, the relationship between cooking sessions and order quantity,
demographic preferences, and trends over time.
The project is aimed at understanding customer behavior, identifying
popular dishes, and analyzing time-based trends for a better business
strategy.
## Project Structure
The project is organized as follows:
/data_analytics_intern_project/ ├── /data/ └── your_excel_file.xlsx # Excel file containing
the raw data ├── /notebooks/ └── analysis.py # Python script for data analysis ├──
/visualizations/ ├── popular_dishes.png # Visualization for popular dishes ├──
demographic_analysis.png # Visualization for demographic analysis └──
monthly_trends.png # Visualization for monthly trends ├── report.md # Report
summarizing analysis and insights └── README.md # GitHub project description
markdown
Copy code
## Requirements
- Python 3.x
- pandas
- matplotlib
- openpyxl (for reading `.xlsx` files)
You can install the required dependencies using `pip`:
pip install pandas matplotlib openpyxl
markdown
Copy code
## How to Run the Analysis
1. **Download the Excel File**: Ensure the Excel file
(`your_excel_file.xlsx`) is available in the `/data/` folder.
2. **Run the Analysis Script**: Navigate to the `/notebooks/` directory and
run the `analysis.py` script. This script will:
 - Load the data from the three Excel sheets.
 - Clean and process the data (handling missing values, duplicates,
etc.).
 - Perform various analyses, such as identifying popular dishes,
understanding the relationship between cooking sessions and orders,
analyzing demographic preferences, and observing trends over time.
3. **View the Visualizations**: After running the script, the
visualizations (bar charts for dish preferences, monthly trends, etc.) will
be saved in the `/visualizations/` folder. You can view these images to get
insights into the data.
4. **Review the Report**: The `report.md` file contains a summary of the
analysis, including key findings and business recommendations.
## Insights from the Analysis
1. **Popular Dishes**: Identifying the top 10 most popular dishes based on
order count.
2. **Cooking Sessions and Orders**: Analyzing the relationship between
cooking time and order quantity.
3. **Demographic Analysis**: Examining dish preferences across different
age groups.
4. **Time-Based Trends**: Tracking monthly trends in orders.
## Business Recommendations
Based on the analysis, you can:
- Focus on promoting popular dishes to increase sales.
- Tailor marketing campaigns to specific age groups based on dish
preferences.
- Analyze and target seasonal or monthly trends to optimize marketing and
inventory strategies.
## Contributing
Feel free to fork this project, submit issues, and contribute via pull
requests. Any suggestions or improvements are welcome!
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details.
---
**Author**: Aditya Soni
**Date**: December 2024
Key Sections in the README:
1. Overview: Explains the goal and objective of the project.
2. Project Structure: Provides a folder and file breakdown for easy navigation.
3. Requirements: Lists the required packages for running the analysis.
4. How to Run the Analysis: Detailed instructions on how to run the analysis script.
5. Insights from the Analysis: Summarizes the insights drawn from the analysis.
6. Business Recommendations: Suggests possible actions based on the findings.
7. Contributing: 