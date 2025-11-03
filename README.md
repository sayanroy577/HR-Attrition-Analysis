# Employee-Attrition-Analysis
Brief Summary:
A data analytics project exploring employee attrition patterns to help organizations identify at-risk employees, improve retention strategies, and enhance workforce stability.

📊 Overview

This project analyzes HR data using Python and Power BI to uncover factors contributing to employee attrition. Through data cleaning, exploratory data analysis (EDA), and visualization, the project aims to deliver actionable insights to help HR leaders reduce turnover and strengthen employee engagement.

🧩 Problem Statement

Employee attrition impacts productivity, morale, and financial performance. The goal of this project is to:

Identify at-risk employees and develop data-driven strategies to reduce voluntary attrition, improve engagement, and retain top talent.

Key focus areas include age, income, job satisfaction, performance, tenure, and department-level trends.

📁 Dataset

Source: Kaggle – HR Employee Attrition Dataset
Shape: 1,480 rows × 38 columns
Data Types: Object, Int64, Float64

Data Cleaning Performed:

Removed 7 duplicate records

No missing values found

Final dataset: 1,473 employee records

🧰 Tools and Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – For data loading, cleaning, and EDA

Power BI – For interactive dashboard creation

Excel / CSV – For data handling and transformation

Jupyter Notebook – For executing and documenting the analysis

🔍 Steps Involved

Data Loading: Imported HR dataset into Python for analysis.

Data Cleaning: Checked for missing values, removed duplicates, standardized data types.

Exploratory Data Analysis (EDA):

Analyzed attrition by age, income, marital status, satisfaction level, and tenure.

Examined overtime, performance ratings, and environmental satisfaction impacts.

Visualized correlations using heatmaps and distribution plots.

Power BI Dashboard: Built an interactive dashboard to visualize department, job role, and education-level attrition rates.

Report Creation: Compiled results and recommendations in a comprehensive report.

📈 Dashboard

The Power BI dashboard provides:

Department-wise attrition rates (Sales: 20.6%, HR: 19%)

Job-role attrition (Sales Representatives: 39.3%, Lab Technicians: 23.8%)

Age group attrition (18–25 and 26–35 most affected)

Education and distance-based attrition comparisons

💡 Key Insights

High Attrition Segments: Younger, single, and lower-income employees.

Tenure Factor: Most employees leave within the first 2–3 years.

Overtime Impact: Frequent overtime strongly correlates with higher attrition.

Income Disparity: Leavers earn ~$4,800/month vs stayers ~$6,800/month.

Performance Ratings: Majority of attrition occurs among average performers.

Work Environment: Low satisfaction levels significantly increase attrition risk.

🏆 Results & Recommendations
For HR & Management

Target Early-Career Retention: Focus on engagement during the first 1–3 years.

Address Overtime & Burnout: Implement policies to reduce excessive workload.

Close Income Gaps: Review compensation for lower-income groups.

Mentorship Programs: Support average performers (rating 3) with development plans.

Enhance Work Environment: Improve conditions and satisfaction for moderate scorers.

For Organizational Strategy

Prioritize High-Risk Departments: Sales and HR teams show the highest turnover.

Invest in Learning: Provide career growth for employees with lower education levels.

Encourage Manager Stability: Consistent leadership helps retain employees longer.

🧾 Conclusion

By integrating Python-based EDA and Power BI visualizations, this project highlights key drivers of attrition and delivers actionable insights for HR decision-making.
Data-driven retention strategies can significantly improve engagement, reduce turnover costs, and foster a stable workforce.

⚙️ How to Run

In Python / Jupyter Notebook:

Load the dataset (HR_Attrition.csv).

Run all analysis cells for cleaning and EDA.

View visualizations in notebook output.

In Power BI:

Open HR_Attrition_Dashboard.pbix.

Refresh the data source to connect to the latest dataset.

Interact with filters to explore attrition patterns.

View Report:

Read the final report (HR_Attrition_Report.pdf) for summarized insights and business recommendations.
