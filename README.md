# [Project 1: Transportation Cost Analysis]([insert_link](https://github.com/JJB249/Operations-Analytics-Projects))

#### **Project Overview**
This project analyses the transportation problem faced by **Exeter Transport Company**, aiming to determine the optimal shipping strategy to **minimise transportation costs**. Various methods are tested, including heuristic approaches and a linear programming (LP) model on Excel, to **compare efficiency and cost-effectiveness**.

#### **Key Objectives**
- Model the transportation problem as a **minimum cost network flow problem**.
- Visualise supply and demand distribution using a network diagram.
- Compute basic feasible solutions (BFS) using: Northwest Corner Method, Least-Cost Method, Vogel’s Approximation Method
- Develop a linear programming model to determine the **minimum transportation cost**.
- **Compare and evaluate** the different methodologies to find the **most effective approach**.


#### **Key Findings**
- **Northwest Corner Method** resulted in a total transportation cost of **$61,000**.
- **Least-Cost Method and Vogel’s Approximation Method** both achieved a cost of **$47,500**, significantly **improving efficiency** over the Northwest approach.
- **Linear Programming (LP) Model** further reduced the transportation cost to **$43,500**, making it the **most optimal solution**.
- Since the total supply and demand are equal, this is classified as a  **balanced transportation problem**.

#### **Project Workflow**
1. **Data Visualisation:**
- Constructed a **Supply-Demand Network Diagram** to illustrate transportation routes and costs.
- Developed a **Transportation Tableau** to organize unit costs and constraints.

2. **Computing the Basic Feasible Solution (BFS):**
- Northwest Corner Method: Allocated supply starting from the top-left cell of the tableau. This method was quick but inefficient, resulting in the highest cost.
- Least-Cost Method: Prioritized shipments based on the lowest transportation costs, significantly reducing expenses.
- Vogel’s Approximation Method: Factored in cost penalties to refine allocations, yielding the same result as the Least-Cost Method.

3. **Mathematical Modelling:**
- Defined **decision variables**, an **objective function**, and **supply & demand constraints** using a Linear Programming Model.
- Used **spreadsheet modeling** to solve for the minimum transportation cost.

#### **Technologies & Tools Used**
- **Spreadsheet Modeling** for tableau representation and BFS computation.
- **Linear Programming (LP)** for optimizing transportation costs.
- **Graphical Network Analysis** to illustrate supply-demand relationships.

#### **Outcome & Business Recommendations**
- The LP model provides the **most cost-effective solution*8 and **should be prioritised**.
- The Least-Cost and Vogel’s methods serve as **good alternatives** when a **quick estimation is required**, as they yielded **near-optimal results**.
- Although minimising transportation costs is crucial, **sustainability, delivery timelines, and customer satisfaction** should also be **factored** into **decision-making**.
- Given **fluctuating transportation costs**, **multiple methods** should be considered to **adapt to market changes**.

# [Project 2: Local Music Store Sales Analysis and Forecasting]([insert_link](https://github.com/JJB249/Business-Analytics-Practices))

#### **Project Overview**
This project focuses on analysing **sales revenue trends** using a **simple regression model** and an **autoregressive model in R**. The objective is to determine how different **factors** influence sales revenue and to **forecast future sales** based on past **trends**.

#### **Key Objectives**
- Utilise a linear regression model to analyse the relationship between **sales revenue** and **independent variables**.
- Evaluate the **correlation** between store visits, social media shares, and average price per unit with sales revenue.
- Apply an **autoregressive (AR) model** to forecast future sales revenue.
- Interpret **key statistical measures** such as R-squared, standard error, and correlation coefficients.


#### **Key Findings**
- A **strong positive correlation** (0.92) exists between store visits and sales revenue.
- The linear regression model produced an **R-squared value** of 0.85, indicating that 85% of the variance in sales revenue is explained by the model.
- The **adjusted R-squared value** (0.83) further confirms the model's robustness.
- The **standard error of the coefficient** for store visits is 0.208, indicating a reliable estimation.
- The autoregressive model **predicts sales revenue** to be $19,173.81K in January 2021 and $19,277.65K in February 2021.


#### **Project Workflow**
1. **Data Collection & Preparation:**
- **Gathered** monthly sales revenue and independent variable data.
- **Cleaned** and structured the dataset for regression analysis.

2. **Exploratory Data Analysis (EDA):**
- **Plotted** scatter plots to **visualise** the relationship between store visits and sales revenue.
- Calculated correlation coefficients to measure **variable relationships**.

3. **Regression Analysis:**
- Built a linear regression model **(Y = β0 + β1X1 + β2X2 + β3X3 + ε)**.
- Analysed coefficient significance, standard error, and R-squared values.

4. **Autoregressive Model & Forecasting:**
- Applied an AR(1) model to predict future sales revenue.
- Generated sales forecasts for January & February 2021 using the **forecast package in R**.

#### **Technologies & Tools Used**
- R (for regression modeling and forecasting)
- ggplot2 (for visualization)
- forecast package (for time-series predictions)
- RStudio (for script execution)

#### **Outcome & Business Recommendations**
- Increase store visits through **marketing campaigns** as they have a strong positive impact on sales revenue.
- Enhance **social media engagement** to increase awareness and drive customer traffic.
- **Adjust pricing strategies** to balance affordability and profitability.
- **Utilise sales forecasts** for better inventory and financial planning.

![Screenshot 2025-02-06 at 18 47 00](https://github.com/user-attachments/assets/d48d2765-0b4a-4dd0-acff-674df748b7eb)

# [Project 3: Analysis of Coca-Cola's Strategy and HR Activities]([insert_link](https://github.com/JJB249/Marketing-Analytics-Projects))

#### **Project Overview**
This project involved designing a **strategic and HR analytics dashboard** tailored for **Coca-Cola Company**, aiming to address key organisational challenges and support evidence-based decision-making. An interactive dashboard was construsted that synthesises data from Coca-Cola and key competitors, enabling real-time monitoring and predictive analysis of strategic, operational, and HR metrics. It was developed as part of a coursework assignment and offers practical business intelligence tools aligned with the company's competitive landscape.

#### **Key Objectives**
- Identify Coca-Cola's strategic and HR challenges using **internal and external data sources**.
- Create an **interactive dashboard** to visualise performance metrics across multiple business functions.
- **Benchmark** Coca-Cola’s metrics **against industry leaders** including PepsiCo, Nestle, and Keurig Dr Pepper.
- Provide **predictive insights into market trends** (e.g. e-commerce, DEI, energy drinks) and **internal HR metrics** (e.g. employee turnover rate, training and development costs).
- Develop **strategic recommendations** to enhance Coca-Cola’s **competitive and operational efficiency**.


#### **Key Findings**
- Coca-Cola **outperforms** the industry average in **net profit margin** (21.2% vs. 10–12%), offering **greater reinvestment potential**.
- The company **lags in capital expenditure and e-commerce investment** relative to competitors, indicating **infrastructure gaps**.
- Despite strong DEI initiatives, Coca-Cola demonstrates **weaker transparency and representation** scores than Nestle and PepsiCo.
- Coca-Cola is **underrepresented in the energy and sports drink market**, accounting for just 5% of sales, compared to 10–15% for competitors.
- Predictive metrics such as Google Trends and CAGR data highlight **high-growth areas Coca-Cola must prioritise**: energy drinks, e-commerce, and advanced HR tech.

#### **Project Workflow**
1. **Data Collection & Preparation:**
- **Gathered** data from market, company and competitor reports.
- **Estimations** were made on information provided by market, company and competitor reports to be used as benchmarks for comparison to enhance the analsis.

2. **Data Visualisation:**
- Constructed flashcards, line charts, bar graphs, and donut charts to track Coca-Cola’s performance across HR and strategic metrics.
- Developed comparative visualisations using industry benchmarks derived from annual reports and financial data.

3. **Metric Analysis and KPI Construction:**
- Developed tailored formulas for key metrics including Employee Efficiency, Compa Ratio, Training Cost per Employee, and Turnover Rate.
- Integrated Google Trends and CAGR data to assess future market movements in health-conscious consumer segments.

4. **Predictive Analytics:**
- Designed visual components to track CapEx, DEI, advertising, and training metrics.
- Built predictive capabilities using real-time proxies (e.g. Google search scores) and dummy data templates for future use.

5. **Strategic and HR Benchmarking:**
- Benchmarked Coca-Cola’s performance against direct competitors in operational investment, gender equality, employee engagement, and e-commerce sales.
- Developed monitoring systems for DEI progression and regional/departmental employee efficiency.

#### **Technologies & Tools Used**
- Python Plotly, pandas and Matplotlib (for constructing an **interactive dashboard**)
- **Secondary research** using Statista, Google Trends, Mintel, and annual reports from Coca-Cola and competitors.
  
#### **Outcome & Business Recommendations**
- **Prioritise CapEx and e-commerce expansion**: Coca-Cola should increase capital allocation toward digital platforms and distribution infrastructure to match Nestle’s 2025 sales goals (25% e-commerce).
- **Optimise DEI strategy transparency**: Coca-Cola must enhance public reporting of DEI progress to improve stakeholder perception and competitive equity.
- **Expand product presence in high-growth markets**: With only 5% of sales in energy and sports drinks, Coca-Cola should consider acquiring or developing performance-focused brands to rival PepsiCo’s Gatorade or KDP’s C4.
- **Integrate advanced HR tech**: Tools such as VR training and AI-driven learning platforms can boost employee engagement while controlling training costs.
- **Adopt predictive KPIs**: Metrics like Pre-Hire Quality Satisfaction and Google Trend Scores offer forward-looking insights and should guide HR and product development strategies.

*You can view all of my projects at: https://github.com/JJB249?tab=repositories*



