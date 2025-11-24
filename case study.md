## Promotion Bump Assignment

Write code in **R**, **Python**, **SAS**, **MATLAB**, or the software of your choice to analyze the provided sales and promotion data.

### Data Sets
- **Assignment4.1a.csv** – Daily sales of sample items across several stores from 2015-01-01 to 2015-08-01.
  - Negative quantities represent returns.
  - Each row is a sale (or return) for an item in a store on a specific day.
  - If a store–item pair is missing for a date, assume zero sales for that day.
- **Promotiondates.csv** – Start and end dates for six promotions in 2015.

### Part A: Modeling Promotion Effects
- Use **Assignment4.1a.csv** and focus on the **first four promotions**.
- Cluster both **products** and **stores** into three groups (Fast / Medium / Slow) based on average weekly sales per store during non-promotion periods. Grouping parameters are up to you.
- Address the following questions:
  1. What are your criteria for separating Fast, Medium, and Slow items? Why?
  2. What are your criteria for separating Fast, Medium, and Slow stores? Why?
  3. Which items experienced the largest sales increase during promotions?
  4. Are there stores with stronger promotion reactions?
  5. What factor best explains sales change during promotions?
  6. Is there a significant difference between promotion impacts on Fast vs. Slow items?
  7. Is there a significant difference between promotion impacts on Fast vs. Slow stores?

### Part B: Forecasting on New Data
- **Assignment4.1b.csv** – Daily sales for sample items and stores after the initial period, enabling evaluation of model predictive power.
- Using the model from Part A, forecast the effect of **promotion 5** on sample store–item pairs and compare forecasts to observed sales.
- Consider:
  - Which goodness-of-fit measure will you use? How well does the Part A model perform?
  - What issues cause poor fits? What would you change in Part A?
  - (Note: You are not judged on the absolute goodness of fit in Part A.)

### Report Guidelines
- Write a concise report that helps the client understand product and store reactions to promotions and quantifies promotion effects.
- Include:
  - Your methodology and code.
  - Recommendations.
  - Model statistics.
  - Interpretation of results.
  - Additional datasets you would like to use, how you would obtain them, and why.

### Bonus
- Investigate whether item return rates change significantly after promotions.
- **Assignment4.1c.csv** provides product categorizations. *ProductGroup1* is the higher hierarchy (e.g., `Top Clothing`), and related *ProductGroup2* values (e.g., `T-shirt`, `Shirt`) can inform your analysis and report.
ProductGroup2s can be 'T-shirt', 'Shirt' etc. This data can be useful in the analysis and report.
