Sales Data Analysis 📊

In this Python Pandas and Matplotlib-based analysis, we delve into 24 months of sales data (spanning 2020 to 2021) to derive insights and address key business questions. 

The dataset encompasses a substantial volume of transactions from an electronics store, detailing information such as  product types, costs, purchase addresses, and product quantities.

The initial step involves consolidating all individual files into a unified dataset through the concatenation of multiple CSV files using pd.concat.

Following this, a meticulous data cleaning process ensues:

- Removal of NaN values from the DataFrame.
- Elimination of repeated headers.
- Identification and handling of duplicates.
- Elimination of rows containing exclusively NaN values.
- Conversion of the datetime column to the appropriate data type using to_datetime.

Feature engineering is then employed, involving the addition of new columns, parsing cells as strings to create additional columns using .str, and applying functions to each data row through the .apply() method. 

Groupby operations facilitate aggregate analysis.

The results are visualized through the creation of bar charts and line graphs, providing a comprehensive understanding of the sales trends and patterns.

With the data now scrubbed, we proceed to explore it, addressing four pivotal business-related questions:

Best Month for Sales: Determining the highest-performing month and quantifying the earnings for that period.

Top-Selling City: Identifying the city that recorded the highest sales volume.

Optimal Advertisement Timing: Establishing the most effective time to display advertisements or offer promotions to enhance the likelihood of customer purchases.

Most Frequently Sold Product: Identifying the product that experienced the highest frequency of sales.


Power BI Integration:

- Following the initial Python-based preparation, the data is seamlessly integrated into Power BI, where the analysis continues.

- High-level business-oriented questions are addressed using DAX measures and Power BI visualizations.

- Bar charts and line graphs are plotted to visually represent the results.
  
This integrated approach, combining Python for initial data preparation and Power BI for visualization and further analysis, ensures a robust exploration of the sales data. It empowers stakeholders with actionable insights for strategic decision-making and offers a dynamic dashboard for ongoing monitoring and analysis.
