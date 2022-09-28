# **Exploratory data analysis of the real estate in St. Petersburg and nearby settlements**



### In this jupyter notebook I use Python Pandas & Python Matplotlib to analyze and answer business questions about months worth of sales data. The data contains thousands of real estate purchases broken down by month, size, cost, location, etc.

___

### I start by cleaning our data. Tasks during this section include:


+ *Drop NaN values from DataFrame*

+ *Removing rows based on a condition*

+ *Change the type of columns (to_numeric, to_datetime, astype)*

+ *Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:*
   * **What city sold more apartments?**
   * **Which apartments sold the most? Why do you think it sold the most?**
   * **What factors affect the sale of apartments**
  
  


___
### To answer these questions we walk through many different pandas & matplotlib methods. They include:

+ *Concatenating multiple csvs together to create a new DataFrame (pd.concat)*
  
+ *Adding columns
Parsing cells as strings to make new columns (.str)*

+ *Using the .apply() method*
  
+ *Using groupby to perform aggregate analysis*
+ *Plotting bar charts and lines graphs to visualize our results*
+ *Labeling our graphs*


