I start by cleaning my data. Tasks during this section include:

Dropping NaN values from my DataFrame
Removing rows based on a specific condition
Changing the type of columns (using to_numeric, to_datetime, astype)
Once I've cleaned up my data, I move on to the data exploration section. Here, I explore five high-level business questions related to the data:

What was the best month for sales? How much was earned during that month?
Which city sold the most product?
What time should I display advertisements to maximize the likelihood of customers buying products?
Which products are most often sold together?
What product sold the most? Why do I think it sold the most?

To answer these questions, I utilize various pandas and matplotlib methods, including:

Concatenating multiple CSVs together to create a new DataFrame (using pd.concat)
Adding new columns
Parsing cells as strings to create additional columns (using the .str accessor)
Applying custom functions to elements using the .apply() method
Performing aggregate analysis using groupby
Creating bar charts and line graphs to visualize the results
Labeling the graphs for clarity
