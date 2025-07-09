# Financial-Loan-Analysis

Overview
The Financial Loan Dashboard is an interactive data visualization project built in Tableau with the goal of helping financial analysts and stakeholders monitor loan performance, assess risk, and make informed decisions.

The dashboard provides a centralized visual interface to:
Track loan issuance trends over time,
Compare performance across loan grades, terms, and purposes,
Segment ‘Good’ and ‘Bad’ loans,
Pinpoint high-risk regions and loan categories,
Optimize lending strategy using data-driven insights.

This project simulates a real-world use case where a loan-lending institution needs to analyze key loan metrics and build an executive-level dashboard for risk mitigation and performance management.

🎯 Problem Statement

- The lending company needs a solution to:
- Understand the overall health of their loan portfolio.
- Segment loans into good and bad categories based on borrower performance.
- Visualize bad loan patterns by purpose and location.
- Identify which loan terms and grades are riskier.
- Provide a comprehensive executive dashboard to monitor trends, draw comparisons, and support decision-making.

📂 Project Files
- File Name	Description
- Financial Loan Data.csv	Cleaned loan dataset used for dashboard analysis
- Financial Loan Dashboard.twbx	Tableau Packaged Workbook with all visuals and interactions
- Problem Statement.docx	Business objective, KPIs, and visualization requirements

📌 Key Objectives
✅ Track loan issuance metrics (number, total funded, and payments received)
✅ Split loans into Good and Bad based on payment performance
✅ Enable multi-dimensional analysis: by loan purpose, grade, state, and term
✅ Empower stakeholders to visualize financial risks and act proactively

📊 Visualizations & KPIs
📈 Visualization	💬 Description
Loan Issuance - Trend Over Time	Tracks monthly/yearly growth in loans issued
Total Funded & Payment KPIs - Summarizes aggregate funding and repayments
Good vs. Bad Loan Metrics	- Segregates loan counts and amounts into performance categories
Bad Loans by Purpose - Highlights risky loan categories such as personal or business
State-wise Loan Issued Map - Shows geographic distribution of loans across the U.S.
Term-wise Good Loan % -	Analyzes impact of loan duration (36 vs 60 months) on loan success
Grade-wise Good Loan % - Examines performance based on credit risk grades (A–G)
Purpose-wise Good vs Bad Loan % -	Compares loan performance for each category (education, car, etc.)

📈 Sample Insights
🔴 Longer loan terms (60 months) showed a higher percentage of defaults.
⚠️ Loan grades E, F, G correlated with higher risk, confirming the predictive power of credit scores.
📍 States like California and Texas had higher overall loan volumes but also revealed variance in repayment performance.
🎯 Personal loans and small business loans were among the top contributors to bad loans.
✅ Short-term, high-grade loans were most likely to be fully paid on time.

🛠️ Tools & Technologies
Tool	Role
Tableau Desktop / Public	Main BI tool used for dashboarding and interactive charts
Microsoft Excel / CSV	Used for initial data cleaning and exploration
Calculated Fields in Tableau	Built KPIs like Good Loan %, default rates, total payments
Filters & Parameters	Enabled user interaction and drill-down by category, state, term, etc.

📊 Dashboard Functionality
🔍 Filters: Interactive filters for loan term, grade, state, and loan purpose.
🧮 Calculated KPIs: Automated calculations of funded amounts, payments, and good/bad ratios.
🗺️ Geospatial Analysis: State-wise map to visualize regional loan issuance.
📊 Comparative Charts: Side-by-side breakdowns of good vs bad loans across multiple categories.

🔧 Data Preparation
- The raw data was first assessed for quality, cleaned in Excel, and imported into Tableau. Steps included:
- Dropping irrelevant or null fields
- Converting date columns to appropriate format
- Creating calculated fields for KPIs like:
- Loan Performance (Good/Bad classification)
- Good Loan %
- Total Payment = principal + interest received
- Custom aggregations for dashboards

📈 Business Impact (Simulated)
If deployed by a real-world financial firm, this dashboard would:

✅ Improve decision-making with real-time loan monitoring
✅ Enable risk managers to target high-default categories
✅ Help optimize loan offerings based on historical patterns
✅ Reduce bad debt through smarter segmentation

🌱 Future Enhancements
Feature	Description
🧠 Machine Learning Integration	Use historical patterns to build predictive loan default models
🔁 Real-Time Updates	Connect dashboard to live SQL/CSV feeds using Tableau Live
📉 Portfolio Simulation	Add simulation tools to assess impact of changing interest rates or terms
📎 More borrower data	Include credit score, DTI ratio, employment type for richer analysis


🧠 What I Learned
- Designing KPI-centric dashboards for business executives.
- Performing categorical segmentation and risk stratification using filters.
- Using Tableau’s mapping, parameter controls, and calculated fields effectively.
- Communicating insights visually through layered, user-friendly dashboards.
