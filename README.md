# **WALMART Data Analysis & Visualization**

Here's a breakdown of the analysis:

1. **Data Import and Overview**:
   - Importing necessary libraries and reading CSV files containing data.
   - Displaying and analyzing the structure of the datasets (`train_df`, `test_df`, `features_df`, `stores_df`).

2. **Data Cleaning and Preprocessing**:
   - Converting date columns to datetime objects for temporal analysis.
   - Extracting week and year information from the date.
   - Merging relevant datasets (`features_df` and `stores_df`) to enhance analysis.

3. **Visualizations**:
   - Scatter plots to visualize weekly sales with respect to stores and departments.
   - Line plots showing weekly sales trends for each year (2010, 2011, 2012) and combined.
   - Histogram and normal distribution analysis for weekly sales.
   - Box plot to understand the relationship between store types and sizes.
   - Bar charts to visualize mean weekly sales per store and department.
   - Line plots depicting mean weekly sales for each department over time.
   - Heatmap illustrating correlations between different columns in the dataset.

4. **Insights**:
   - Store 20 has the highest mean weekly sales, while store 5 has the lowest.
   - Department 92 appears to have the highest weekly sales on average.  
   - Different departments show varying sales patterns over time, with some departments experiencing spikes during certain periods.
   - The data reveals correlations between different variables, highlighting potential feature selection considerations for modeling.

5. **Recommendations**:
   - Utilize insights from top-performing stores and departments to optimize strategies.
   - Consider seasonal trends identified in sales data for better inventory management and marketing campaigns.
   - Prioritize features with significant correlations while building predictive models and consider dropping redundant features.

Overall, the analysis provides valuable insights into Walmart's sales data, facilitating data-driven decision-making and strategy formulation for business improvement.
