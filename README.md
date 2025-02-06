# [Project 1: Coffee company data analysis]([insert_link](https://github.com/JJB249/Operations-Analytics-Projects))

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



