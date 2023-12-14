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

Summary of findings:
Final analysis reveals that Kendra Garrett with a client id of 24741 made a 
total profit of $36.58 Million selling 239,862 items.  Her sales show her to be 
an outlier compared to the following four clients being ahead of them by at 
least $33.31 Millon.  Alexandra Young with a client id of 38378 could improve 
her total profit if she brings her shipping cost down.  She sold less than 
Bryan Myers with a client id of 46820 but had a higher shipping cost of 114% 
in comparison.

References:
Pandas. (n.d.). Pandas documentation. https://pandas.pydata.org/docs/reference/frame.html