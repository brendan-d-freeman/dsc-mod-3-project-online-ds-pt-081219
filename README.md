
# Module 3 Final Project

This project is centered around statistical analysis and experience using SQL databases. The following packages are used:
- Pandas
- Numpy
- SQLite
- Scipy Stats
- Seaborn
- Matplotlib
- Statsmodels

The data used is a fake dataset based on the sales of a company called Northwind.

The first hypothesis I tested is whether the discount of an item has a significant impact on the quantity of the item ordered. The null hypothesis was that the item discount has no impact on the quantity of items ordered. To test the null hypothesis I used a t-test and Mann-Whitney test, both of which had p-values below the alpha .05. Therefore, I was able to reject the null hypothesis and conclude that discount did have an impact on quantity purchased.

I then used Cohen D to try to evaluate the power of the impact the discount has on the quantity of items ordered.