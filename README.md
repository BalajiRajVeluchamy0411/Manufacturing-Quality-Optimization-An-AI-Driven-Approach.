# Manufacturing Quality Optimization: An AI-Driven Approach
This project demonstrates the collaboration of Project Management, Data Analytics, and Artificial Intelligence to optimize chemical product purity.

## 1. Project Management (Manage Quality)
In this phase, we simulated a Manage Quality document. We tracked five independent variables from the manufacturing process to monitor their impact on the target variable.
- Independent Variables: Temperature ($^\circ$C), Pressure (PSI), Concentration (M), Level (m), and Catalyst Composition.
- Target Variable: Product Purity (%).
- Artifact: [Process_Variables.xlsx]

## 2. Data Analytics (EDA & Insights)
We performed Exploratory Data Analysis to understand the process behavior.
- Correlation Analysis: Identification of key drivers for purity.
- Visualization: A scatter plot of Temperature vs. Purity revealed a non-linear "hill" shape, indicating an optimal operating window.

## 3. Artificial Intelligence (Polynomial Regression)
Because the relationship was non-linear, we implemented Polynomial Regression (Degree 2).
- Model Goal: Predict purity based on real-time sensor data.
- Technical Stack: Python, Scikit-Learn, Pandas.
- Outcome: The model provides a "Live Process Check" to alert operators when parameters drift away from the "sweet spot."
