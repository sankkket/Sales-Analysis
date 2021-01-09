# Sales-Analysis
I used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Started by cleaning the data. Tasks during this section include:

Dropping NaN values from DataFrame. Removing rows based on a condition. Change the type of columns (to_numeric, to_datetime, astype)

Business Questions: 
1.What was the best month for sales? 
2.How much was earned that month? What city sold the most product? 
3.What time should we display advertisemens to maximize the likelihood of customer’s buying product? 
4.What products are most often sold together? 
5.What product sold the most? Why do you think it sold the most?

These questions are solved with many different pandas & matplotlib methods. They include:

Concatenating multiple csv's together to create a new DataFrame (pd.concat).
1.Adding columns. 
2.Parsing cells as strings to make new columns (.str). 
3.Using the .apply() method. 
4.Using groupby to perform aggregate analysis. 
5.Plotting bar charts and lines graphs to visualize results. 
6.Labeling graphs.
