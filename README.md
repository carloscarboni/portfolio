# Environmental Engineer and Data Analyst
##### Techical Skills: Excel, Python, SQL, GIS, R, Power BI

## Education

- Environmental Engineer | Catholic University of Argentina (_December 2021_)

## Courses
- Excel Skills for Business - Macquaire University (_2021_)
- Data Science Professional Certificate - IBM (_2023_)
- Geographic Information Systems (GIS) Specialization - University of California, Davis (_2024_)
- Advanced Data Analytics - Google (_2024_)

# Work Experience
**Critical Process Analyst @ Coca Cola FEMSA (_May 2023 - April 2024_)**
- Developed a database and an interactive visualization dashboard to monitor key parameters of the Water Treatment Plant, implementing a real-time alert system to identify out-of-range values. By tracking parameter trends and leveraging the alert system, corrective and preventive actions were taken, improving treatment efficiency by 5% and contributing to a reduction in the site's WUR.
- Developed a visualization dashboard for the effluent treatment plant, enabling real-time monitoring and achieving zero environmental fines due to parameter deviations.
- Centralized all information from the Beverage Production sector into a database and developed a visualization dashboard, enabling the identification of process deviations and the implementation of preventive actions to avoid beverage syrup waste.

**Environmental and Sustainability Analyst @ International Trade Logistics (_Aug 2021 - Oct 2022_)**
- Centralized carbon dioxide emissions data from the group's three companies into a single database and developed a visualization dashboard to monitor Scope 1 and Scope 2 emissions in compliance with ISO 14064 standards.
- Initiated data collection and database development for Scope 3 emissions, engaging with external stakeholders to ensure accurate and comprehensive information.
- Collected data and created visualizations for various reports on ESG indicators, enabling analysis and informed decision-making.

# Portfolio Projects
## SQL Projects
### HR Data Analysis

- **Code and Dashboard:** [HR Data Analysis](https://github.com/carloscarboni/SQL/tree/main/HR%20Data%20Analysis)

- **Objective:**
  - Analyze employee absenteeism data to identify trends, reward healthy behaviors, and calculate the financial impact of compensation adjustments. Present insights in an interactive Power BI dashboard for decision-making.

- **Description:**
  - The queries integrate absenteeism records, compensation data, and reasons for absence, identifying employees meeting health criteria (e.g., non-smokers, low BMI). Additionally, they calculate the budget impact for salary increases based on health metrics. The data is visualized in Power BI, showcasing key metrics such as absenteeism trends, employee demographics, and correlations between workload, transportation expenses, and absenteeism.

- **Skills:**
  - SQL for data extraction, integration, and analysis
  - Data visualization and reporting using Power BI
  - Advanced analytics with conditional logic and categorization (CASE statements)
  - Trend analysis and KPI development
- **Technology:**
  - SQL
  - Power BI for dashboard design and interactive reporting
  - Relational database systems for data storage and querying
  
- **Results:**
  - Data Insights: Key KPIs such as average absenteeism time (6.92 hours) and total absenteeism hours (5124) were calculated and visualized.
  - Employee Analysis: Pie charts categorized employees by education, pet ownership, social drinking, and smoking habits.
  - Trends and Patterns: Line charts identified absenteeism peaks by month and day of the week, revealing critical periods such as higher absenteeism in July.
  - Comparative Analysis: Transportation expenses and workload correlations were visualized to identify cost-driving factors.
  - Interactive Reporting: The Power BI dashboard provided HR teams with actionable insights for developing health and compensation policies, targeting systemic issues, and optimizing absenteeism management.

---
 
### Hotel Data Analysis

  - **Code and Dashboard:** [Hotel Data Analysis](https://github.com/carloscarboni/SQL/tree/main/Hotel%20Data%20Analysis)
 
- **Objective:**
  - Analyze revenue and operational data from hotel records (2018–2020) to identify performance trends and provide insights into revenue distribution, customer segmentation, and resource allocation. Present findings through an interactive Power BI dashboard.

- **Description:**
  - The SQL script combines data from multiple yearly datasets (2018, 2019, 2020) into a unified table, enriching it with additional information from related tables like market segments and meal costs. The integrated data is visualized in Power BI to display key metrics such as total revenue, average daily rate (ADR), and parking requirements. The dashboard also highlights revenue trends by hotel type and the contribution of each year to total revenue.

- **Skills:**
  - SQL for data integration and cleaning.
  - Data modeling and relationship handling across multiple tables
  - Dashboard creation and interactivity in Power BI
  - Trend and KPI analysis.
- **Technology:**
  - SQL (applicable to Microsoft SQL Server or equivalent)
  - Power BI for interactive reporting and visualization
  - Relational database for data storage and querying

- **Results:**
  - Data Insights: Total revenue of $10.23M with ADR of $104.47 and 367.78K total nights booked.
  - Revenue Breakdown: Pie chart reveals revenue split between City Hotels (46.38%) and Resort Hotels (53.62%).
  - Trends Analysis: Line charts display revenue performance over time, identifying seasonal peaks and periods of high demand.
  - Operational Metrics: Parking requirements and discounts are analyzed, aiding resource allocation and marketing strategies.
  - Interactive Reporting: Power BI dashboard allows filtering by hotel type, year, and country, enabling dynamic exploration of performance drivers.

---

### Spotify and Youtube Data Analysis

- **Code and Dashboard:** [Spotify Data Analysis](https://github.com/carloscarboni/SQL/tree/main/Spotify%20and%20YT%20)

- **Objective:**
  - Analyze Spotify track data to derive key insights about artist performance, track popularity, and album characteristics. Present findings through queries ranging from exploratory data analysis (EDA) to advanced metrics computation.

- **Description:**
  - The SQL script explores a dataset named `spotify` using various query levels:
    - **EDA:** Basic exploration of the dataset, including counts, unique values, and data cleaning.
    - **Easy Level:** Aggregates metrics such as top-streamed tracks, album-artist pairings, and licensed track statistics.
    - **Medium Level:** Analyzes track characteristics like danceability, energy, views, and popularity by platform.
    - **Advanced Level:** Utilizes window functions and CTEs to calculate rankings, cumulative sums, and complex ratios (e.g., energy-to-liveness).
  - These analyses enable detailed insights into track performance and user engagement across Spotify and YouTube.

- **Skills:**
  - SQL for data cleaning, transformation, and analysis.
  - Advanced SQL techniques: window functions, CTEs, and subqueries.
  - Trend analysis for features like energy, danceability, and liveness.
  - Cross-platform comparisons for popularity metrics.

- **Technology:**
  - SQL.
  - Relational database for data storage and querying.

- **Results:**
  - **Data Insights:**
    - Total tracks, albums, and distinct artists identified through EDA.
    - Tracks with over 1 billion streams identified, along with their contributing artists.
    - Album-specific trends in danceability and energy.
  - **Platform Comparisons:**
    - Tracks streamed more on Spotify than YouTube highlighted.
  - **Performance Metrics:**
    - Top 3 most-viewed tracks per artist calculated using window functions.
    - Energy-to-liveness ratios computed to identify dynamic track properties.

---

## Python Projects
### Employee Churn

- **Code and Report:** [Employee Churn Analysis](https://github.com/carloscarboni/Python/tree/main/Employee_Churn)

- **Objective:**
  - Analyze employee data to predict the likelihood of employees leaving the company (churn) using machine learning models and visualize the results in a dashboard.

- **Description:**
  - The script connects to a Google BigQuery dataset containing employee information. It uses the pycaret library to set up, train, and evaluate a classification model, specifically focusing on the "Quit_the_Company" target variable. Predictions and feature importance insights are generated, and a graphical report is created to present the results using Looker Studio. The dashboard highlights key metrics driving churn and identifies employees most at risk.

- **Skills:**
  - Data retrieval from Google BigQuery
  - Machine learning model setup and evaluation using pycaret
  - Feature importance analysis
  - Writing predictions and feature tables back to BigQuery
  - Data visualization and reporting with Looker Studio.

- **Technology:**
  - Python (libraries: google.cloud.bigquery, pycaret, pandas)
  - Google BigQuery for data storage and retrieval
  - Machine learning techniques for classification (random forest model)
  - Looker Studio for data visualization and reporting.

- **Results:**
  - Key Insights: The Random Forest model identified job satisfaction as the most critical factor in predicting employee churn. Additional important factors included tenure, the number of projects handled, average monthly hours, and performance evaluations.
  - Predictions: Employees likely to leave were identified across various departments, with actionable insights provided to HR.
  - Visualization: The Looker Studio dashboard presented churn by department, satisfaction levels, and other metrics, offering HR a clear view of factors driving churn and supporting the development of retention strategies.
  - HR Strategy: Insights guided targeted interventions to improve job satisfaction and address systemic issues such as workload balance and career development opportunities.

---
 
### Customer segmentation and clustering

- **Code:** [Customer Segmentation and Clustering](https://github.com/carloscarboni/Python/tree/main/Customer%20segmentation%20and%20clustering)

- **Objective:**
  - Perform exploratory data analysis (EDA) and cluster mall customers to identify patterns in their annual income, age, and spending scores using clustering techniques.

- **Description:**
  - The script analyzes a dataset named Mall_Customers.csv, which contains demographic and behavioral data of customers. It includes univariate, bivariate, and multivariate analyses, followed by the application of KMeans clustering algorithms to identify homogeneous groups based on key characteristics.

- **Skills:**
  - Exploratory Data Analysis (EDA)
  - Data visualization using seaborn and matplotlib
  - Clustering with KMeans
  - Data normalization and elbow graph creation to determine the optimal number of clusters.

- **Technology:**
  - Python (libraries: pandas, seaborn, matplotlib, sklearn)
  - Clustering algorithms (KMeans)
  - Categorical data processing and feature scaling.

- **Results:**
  - Identification of patterns in customer income and spending behavior.
  - Grouping of customers into different clusters based on demographic and behavioral characteristics.
  - Visual insights into distributions of gender, income, and spending behavior for each cluster.
 
---
 
## R Projects
### Distribution of Total and Per Capita Emissions in Argentina and the AMBA

- **Code and Project Repository:** [Emissions and Population Analysis](https://github.com/carloscarboni/R/tree/main/CO2-Emissions-Argentina)
- **Objective:**  
  - Analyze the spatial distribution of total and per capita CO₂ emissions across Argentina, focusing on specific regions such as Buenos Aires Province and the AMBA region (Greater Buenos Aires and Buenos Aires City). The project utilizes advanced spatial analysis and visualization techniques.

- **Description:**
  - This project examines the distribution of total and per capita emissions in Argentina, progressively narrowing the focus from a national level to Buenos Aires Province and, finally, the AMBA region. The R script integrates tools such as `tidyverse`, `terra`, `sf`, and `ggplot2`. Emissions data were sourced from the EDGAR database, and population data from the GHSL dataset.

- **Skills:**
- **Spatial Data Analysis:** Integration and processing of geospatial datasets.
- **Data Visualization:** Creation of detailed, high-resolution maps for analysis.
- **Environmental Analysis:** Interpretation of emissions and population dynamics.
- **Critical Thinking:** Identification of regional patterns influenced by industrial and urban factors.

- **Technology:**
  - **Programming Language:** R  
  - **Key Libraries:** `tidyverse`, `terra`, `sf`, `exactextractr`, `classInt`, `ggplot2`.  
  - **Data Sources:**  
    - **Emissions Data:** EDGAR database.  
    - **Population Data:** GHSL dataset.  
  - **Development Environment:** RStudio.

- **Results:**
  1. **National-Level Insights:**  
     - Total emissions are highest in densely populated and industrialized areas like Buenos Aires Province, Santa Fe, and Córdoba.  
     - Neuquén Province stands out in per capita emissions due to the industrial impact of the Vaca Muerta reservoir.
  
  2. **Provincial-Level Insights (Buenos Aires Province):**  
     - The AMBA region dominates emissions due to its urban and industrial density.  
     - Bahía Blanca (industrial hub) and Olavarría (cement industry) also exhibit significant emissions.  
     - Ramallo and Tordillo lead in per capita emissions, driven by low populations and high industrial outputs in comparison to their local community.
  
  3. **AMBA-Level Insights:**  
     - Buenos Aires City is the largest emitter in Argentina.  
     - Avellaneda contributes significantly through its petrochemical and tanning industries, as well as its large container terminal.  
     - Campana and Zárate host key factories in steelmaking, automotive, and petrochemical industries.  
     - Ensenada leads in per capita emissions due to its industrial base and low population.

