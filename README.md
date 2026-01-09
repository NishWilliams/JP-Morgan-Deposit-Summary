# JP Morgan Deposit Summary 

Interactive dashboard analyzing branch-level deposit trends at Chase Bank in the United States, showcasing end-to-end data analysis skills.

**Project Status:** ✅ Complete - Analysis & Visualization Ready

## 📋 Overview 
This project demonstrates end-to-end data analysis skills, including data cleaning, SQL analysis, and business intelligence visualization. The interactive Tableau dashboard focuses on deposit trends and branch-level account activity, providing actionable insights to support decision-making for branch optimization.

## 🎯 Buisness Case 
JPMorgan Chase & Co. (NYSE: JPM) is a leading global financial services firm with operations in more than 50 countries. The bank sought to optimize its branch network in the U.S. T-3, a consulting company, was engaged to analyze retail deposits (checking and savings accounts) at the branch level. The goal was to develop strategies for branch optimization to support growth. 

### 📝 Situation 
Day-to-day banking (D2D), a division of retail banking, requested Branch Optimization Strategies. T-3 and other analytics specialists were provided with Chase Bank data for retail deposits. Your task was to create one interactive dashboard with the following metrics: 

| Metric Name | Description | Unit of Measure |
|-------------|------------|----------------|
| Average Deposits (2010–2016) | Average of all deposits | $ Million |
| Total Deposits (2016) | Total deposits in 2016 | $ Million |

[View Tableau Dashboard](https://public.tableau.com/app/profile/nishanee.williams/viz/J_PMorganChase-DepositSummary/MainView) 

## 🛠️ Tech Stack
- **Tableau** – visualization & dashboard creation
- **SQL** – data querying & preparation
- **Python / Data Cleaning** – analytics pipeline

## 🧹 Data Preparation Process
### Data Extraction & Cleaning 
1. Collected branch-level deposit data from the provided JPMorgan Chase dataset.
2. Reviewed and handled missing values to ensure accurate calculations.
3. Standardized numeric formats and converted dates to proper datetime types for consistency.
4. Removed deposits from the "Main Office" and any branches with zero total deposits from 2010–2016.

### Metric Calculations 
1. Calculated **Average Deposits (2010–2016)** for each branch.
2. Calculated **Total Deposits (2016)** for each branch.
3. Verified that metrics were accurate and aligned with business requirements.

### Filters & Dashboard Preparation 
1. Applied filters for **State, City, County, and Branch** to allow dynamic exploration of metrics.
2. Ensured all views in the dashboard matched the wireframe layout provided in the assignment resources.
3. Prepared the Tableau workbook for publishing to Tableau Public, maintaining interactivity and readability.

### Validation 
1. Checked for duplicate entries at the branch level.
2. Confirmed all calculations and filters were applied correctly.
3. Ensured the dashboard met the specified layout and design requirements.

## 📊 Key Analysis Areas 
1. **Branch Deposit Trends (2010–2016)** - Analyzed average deposits for each branch over time to identify growth patterns and trends.
2. **Total Deposits (2016)** - Evaluated total deposits for each branch in 2016 to determine high-performing and low-performing locations.
3. **Geographical Insights** - Used State, City, County, and Branch filters to explore deposit performance across different regions.
4. **Branch Optimization Opportunities** - Identified branches with low or stagnant deposits to provide actionable insights for branch optimization strategies.

## 🔍 Key Findings & Insights 
1. **High-Performing Branches** - Certain branches consistently showed high average deposits from 2010–2016, indicating strong customer engagement and growth potential.
2. **Low-Performing Branches** - Some branches had stagnant or declining deposits, highlighting opportunities for optimization or resource reallocation.
3. **Regional Trends** - Deposit performance varied across states and counties, suggesting that location-specific strategies may improve overall growth.
4. **Deposit Concentration** - A small number of branches accounted for a significant portion of total deposits in 2016, revealing key areas for strategic focus.

## 💡 Recommendations 
Based on the analysis, the project provides actionable recommendations for JPMorgan Chase: 
1. **Focus on High-Potential Branches** - Allocate resources to branches with consistently high deposits to maximize growth opportunities.
2. **Optimize Low-Performing Branches** - Evaluate branches with stagnant or declining deposits for targeted strategies, such as marketing campaigns or service improvements.
3. **Region-Specific Strategies** - Develop location-specific approaches based on state, city, and county deposit trends to improve overall performance.
4. **Resource Reallocation** - Consider reallocating staff or support from low-deposit branches to higher-performing or strategically important locations.

## ✉️ Contact 
Feel free to reach out for questions, suggestions, or collaborations! 

## 🔗 Data Source 
JPMorgan Chase branch-level deposit data provided as part of a course assignment. 
- **Dataset Type:** Retail deposits (checking and savings accounts)
- **Time Period:** 2010–2016 - **Provided By:** T-3 Consulting / Course Resources
- **File Format:** Excel
- **Note:** This dataset is provided for educational purposes as part of the school assignment. 

## 🎓 Project Credit 
This project is based on the JPMorgan Chase Deposit Summary assignment provided as part of the Data Analytics course at McMaster University. The business requirements and dataset were provided by T-3 Consulting / course resources, with all analysis and visualization implemented independently.

---------------------------------------------------------------------------------------------------------------------------------------- 
![JP Morgan Deposit Summary Dashboard](https://raw.githubusercontent.com/NishWilliams/JP-Morgan-Deposit-Summary/main/resources/J.P%20Morgan%20Deposit%20Summary.png)
