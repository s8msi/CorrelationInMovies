# CorrelationInMovies
This project is an analysis on the dataset of a few movies to find out patterns and relations between the different variables in various movies.
--------

In this project we go through the dataset of a few movies. We try to find if there is any relation between the variables in the dataset.

Initially, we change the data types of a few variables to simplify the analysis.

Then we try and clean the data by removing the faulty rows and dropping the duplicate values.

After that we plot a few variables to see if we can see any sort of relation between them.

Since, that didn't work. We make the Correlation matrix and plot the Correlation Matrix on a HeatMap. To check in detail we convert all the columns to numerical values and make a Correlation Matrix of them and plot that on a HeatMap.

We can see that there is Correlation between a few variables in the dataset. So, we unstack the variables from the dataset, sort them and pass a condition to only display the variables with correlation more than 0.75 to view the variables with Correlation between them.

Thank you!
