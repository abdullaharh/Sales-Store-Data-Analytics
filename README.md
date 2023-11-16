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



In conclusion, this thorough analysis using Python's Pandas and Matplotlib equips us with actionable insights to inform strategic business decisions and optimize future sales strategies.
