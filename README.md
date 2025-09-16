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


# [Project 2: Analysis of Airbnb listings in Bristol (UK, 2024)]([insert_link](https://github.com/JJB249/Analysis-of-Airbnb-listing-in-Bristol-UK-2024-))

#### **Project Overview**
This project focuses on analysing **Airbnb listings in Bristol (UK, 2024)** using **interactive dashboards** created in **Python Plotly** and **Tableau**. The objective is to to understand how listing characteristics, host reliability, and seasonal trends influence customer booking behaviour and to provide actionable insights for both users and Airbnb’s strategic teams.

#### **Key Objectives**
- Utilise a **Python Plotly dashboard** to examine the relationship between **listing price, property type, review scores, amenities, and availability**.
- Deploy a **Tableau dashboard** to evaluate **host reliability through response times, verification, biography quality, and Superhost status**.
- Identify **seasonal and geographic trends** in prices and reviews to highlight **demand fluctuations**.
- Assess **consumer preferences** for **property types and host attributes** to recommend listing and marketing **strategies**.

#### **Key Findings**
- **Geographic price variation exists**: northeast Bristol is more affordable, while listings near parks and in the southwest are more expensive.
- **Consumer preference** leans toward larger, more traditional rentals (cottages, cabins, homes) over apartments or hotel-like spaces.
- **Seasonal trends** are evident, with demand and reviews peaking in holiday months and falling in January.
- Most hosts are experienced and verified, but customer preference strongly favours quicker response times, creating a **performance gap between top-tier and weaker hosts**.
- **Superhosts** consistently provide **better customer experiences**, as indicated by higher review ratings.

#### **Project Workflow**
1. **Data Collection & Preparation:**
Airbnb listing data for Bristol was gathered and cleaned, including property, price, review, availability, and host information.

2. **Exploratory Data Analysis (EDA):**
Python Plotly dashboard visualisations (scatter maps, pie charts, heatmaps, line and bar charts) explored geographic, categorical, and temporal patterns.

3. **Regression Analysis:**
A Tableau dashboard assessed host-related metrics, such as biography length, verification status, and responsiveness, using histograms, scatter plots, and bar charts.

4. **Autoregressive Model & Forecasting:**
Visualisations were critically evaluated for their design, user-friendliness, and contribution to strategic decision-making. Insights were extracted to inform both guests and Airbnb’s operations and marketing teams.

#### **Technologies & Tools Used**
- Python (Plotly for interactive dashboards)
- Tableau (for host reliability dashboard)
- Jupyter Notebook (for Python execution)
- Airbnb dataset (filtered for Bristol 2024 listings)

#### **Outcome & Business Recommendations**
- Adopt **dynamic pricing strategies** to exploit **seasonal demand fluctuations**.
- **Encourage hosts** to **improve verification, responsiveness, and biography quality to strengthen reliability**.
- **Highlight traditional and larger rentals** in **marketing campaigns**, particularly around **holiday seasons**.
- **Promote Superhosts** and ensure **underperforming hosts** receive **targeted improvement strategies**.
- **Leverage insights from dashboards** to create **city-specific platforms** for continuous **KPI monitoring and host engagement**.


# [Project 3: Analysis of Coca-Cola's Strategy and HR Activities]([insert_link](https://github.com/JJB249/Coca-Cola-Strategic-and-HR-Analysis))

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



