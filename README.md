E-Commerce Sales Analysis: Optimizing Marketing and Growth

I start the project by importing 12 monthly csv files into python. I used glob package for this. 

This project analyzes 12 months of sales data from an e-commerce store to answer key business questions and uncover actionable insights. Tasks during this section include:

1. Dropping NaN values from my DataFrame
2. Removing rows based on a specific condition
3. Changing the type of columns (using to_numeric, to_datetime, astype)

Once I've cleaned up my data, I move on to the data exploration section. Here, I explore five high-level business questions related to the data:

1. What was the best month for sales? How much was earned during that month?
2. Which city sold the most product?
3. What time should I display advertisements to maximize the likelihood of customers buying products?
4. Which products are most often sold together?
5. What product sold the most? Why do I think it sold the most?

Technical Stack:
1. Python, pandas, matplotlib
2. Data cleaning methods: pd.dropna, DataFrame.query, astype
3. Data exploration methods: pd.concat, custom functions with .apply, groupby, visualizations

To answer these questions, I utilize various methods, including:

1. Concatenating multiple CSVs together to create a new DataFrame (using pd.concat)
2. Adding new columns
3. Parsing cells as strings to create additional columns (using the .str accessor)
4. Applying custom functions to elements using the .apply() method
5. Performing aggregate analysis using groupby
6. Creating bar charts and line graphs to visualize the results
7. Labeling the graphs for clarity
