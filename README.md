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

# [Project 1: Local Music Store Sales Analysis and Forecasting]([insert_link](https://github.com/JJB249/Business-Analytics-Practices))

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





