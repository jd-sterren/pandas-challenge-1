# pandas-challenge-1
Module 4 Challenge

Instead of using .head(3) to find largest quantity of category, I used .nlargest
which returns the requested number in descending order.  By tacking this onto
.value_counts(), it performs the same way as using sort_values without having
to specify ascending=False while using .head()

Instead of typing in "consumables" for the top category list to search the 
subcategory for and since the previously returned data assigned the category 
as the index, I can used .index[0] to return the category name since the data
may change over time if I were programming for reports.

References:
Pandas. (n.d.). Pandas documentation. https://pandas.pydata.org/docs/reference/frame.html