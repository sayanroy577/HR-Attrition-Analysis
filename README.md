# HR-Attrition-Analysis
Project Overview
This project provides a comprehensive Human Resources (HR) attrition analysis, leveraging data to identify key factors contributing to employee turnover. By understanding these drivers, the aim is to propose actionable business recommendations to improve employee retention and foster a more stable workforce.

Problem Statement
Employee attrition poses significant challenges for organizations, including increased recruitment costs, loss of institutional knowledge, decreased productivity, and a negative impact on morale. This analysis seeks to pinpoint the primary reasons behind employee departures to enable the development of targeted and effective retention strategies.

Dataset
Source: Kaggle

Rows & Columns: 1480 rows, 38 columns

Data Types: Object, Int64, Float64

Data Cleaning
The dataset underwent the following cleaning steps:

Missing Values: Handled (details on specific handling methods would go here, e.g., imputation, removal).

Duplicates: 7 duplicate rows were identified and removed, resulting in 1473 unique employee records for analysis.

Analysis & Key Findings
The analysis was conducted using both Python for statistical insights and Microsoft Power BI for interactive visualizations.

Python Analysis Highlights:
Overall Attrition: Out of 1473 employees, 237 (16.1%) have left the company.

Marital Status: Single employees exhibit the highest attrition rate (120), despite not being the largest demographic group.

Remedy: Offer career path clarity, growth opportunities, flexible work arrangements, mentorship, and social integration programs.

Job Satisfaction: Low job satisfaction is a strong predictor of attrition. The highest attrition count (73) is at satisfaction level 3, with level 1 also showing high attrition (66 employees).

Remedy: For Level 3, focus on career development, role enrichment, and recognition. For Level 1, improve management practices, workload balance, and internal mobility.

Years at Company: Employees who left had a lower median tenure compared to those who stayed.

Remedy: Emphasize onboarding, mentorship, and engagement during the first 1-5 years. Implement structured development plans to address lack of progression.

Overtime: A strong correlation exists between overtime and higher attrition.

Remedy: Utilize time-tracking tools to flag excessive hours, ensure fair compensation or meaningful recognition for overtime.

Average Income: Employees who left had a lower average monthly income (~\$4800) compared to those who stayed (~\$6800).

Remedy: Offer bonuses, training grants, or skill-based raises for entry- or mid-level employees, and provide clear paths to better-paying roles.

Years in Current Role: Short tenure (within the first 2-3 years) in the current role is linked to higher attrition.

Remedy: Improve onboarding and first-year experience, celebrate early achievements.

Performance Ratings: Most attrition originates from average performers (rating 3).

Remedy: Provide growth paths, stretch assignments, and mentorship. Ensure "solid" employees feel valued.

Environmental Satisfaction: Low environmental satisfaction is a significant red flag for attrition.

Remedy: Understand specific causes of dissatisfaction (e.g., noise, safety, leadership, inclusiveness) and enhance the physical workspace, culture, and leadership accessibility.

Correlation Heatmap (Numeric Values):

Negative Correlations (Retention Factors): TotalWorkingYears (-0.17), YearsAtCompany (-0.14), MonthlyIncome (-0.17), YearsWithCurrManager (-0.16), Age (-0.16), JobLevel (-0.17). These indicate that experience, tenure, income, stable management, age, and higher job levels are associated with lower attrition.

Positive Correlations (Attrition Risk Indicators): NumCompaniesWorked (+0.13), DistanceFromHome (+0.03). These suggest that employees who have changed jobs more often or live farther from work are slightly more likely to leave.

Microsoft Power BI Analysis Highlights:
Department-wise Attrition: Sales (20.6%) and Human Resources (19%) departments show the highest attrition rates.

Remedy: Conduct exit interviews, analyze workloads, compensation, and engagement initiatives in these departments.

Job Role-wise Attrition: Sales Representative (39.3%), Laboratory Technician (23.8%), and Human Resources (23.1%) roles have exceptionally high attrition.

Remedy: Implement targeted initiatives like improved training, mentoring, performance incentives, and better work-life balance.

Age Group-wise Attrition: Age groups 18-25 and 26-35 show significant attrition rates.

Remedy: Investigate reasons for attrition in the 26-35 age group; implement mentorship, training, and clear advancement pathways for younger employees.

Education-wise Attrition: Education levels 1, 2, and 3 have the highest attrition rates.

Remedy: Offer opportunities for advancement and further education to align employee capabilities with employer expectations.

Distance from Office: Employees living farther from the office tend to attrite more.

Remedy: Offer transportation benefits, carpooling, subsidies, remote/hybrid work options, or relocation assistance for critical roles.

Strategic Business Recommendations for Attrition Reduction
Based on the analysis, key recommendations include:

Re-evaluate Compensation & Benefits: Targeted adjustments for lower-income roles.

Invest in Career Development: Structured career paths, enhanced onboarding, upskilling, and focus on "average" performers.

Optimize Work-Life Balance: Address overtime, promote flexible work, and analyze workloads in high-attrition areas.

Foster Positive Environment: Improve job and environmental satisfaction, strengthen management practices.

Data-Driven Talent Strategy: Refine hiring profiles, consider geographic factors, and implement continuous monitoring with feedback loops (exit/stay interviews, engagement surveys).

Technologies Used
Python: For data cleaning, statistical analysis, and correlation insights. (Specific libraries like Pandas, NumPy, Matplotlib, Seaborn would be listed here if used).

Microsoft Power BI: For interactive data visualization and dashboard creation.

How to Use/Run This Project
Clone the repository:

git clone https://github.com/sayanroy577/HR-Attrition-Analysis-.git

Navigate to the project directory:

cd HR-Attrition-Analysis-

Python Analysis:

Ensure you have Python installed.

Install required libraries (e.g., pip install pandas numpy matplotlib seaborn).

Run the Python script(s) (e.g., python your_analysis_script.py).

Power BI Dashboard:

Ensure you have Microsoft Power BI Desktop installed.

Open the .pbix file located in the Power BI folder (e.g., PowerBI/HR_Attrition_Dashboard.pbix).

Repository Structure
HR-Attrition-Analysis-/
├── data/
│   └── your_dataset.csv  (or similar data file)
├── notebooks/
│   └── python_analysis.ipynb (Jupyter Notebook for Python analysis)
├── powerbi/
│   └── HR_Attrition_Dashboard.pbix (Power BI project file)
├── README.md
└── (any other relevant files, e.g., requirements.txt)

Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License - see the LICENSE.md file for details. (If a LICENSE.md file exists)

Contact
For any questions or feedback, please contact [Your Name/Email/LinkedIn Profile Link].
