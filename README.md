# Analyze A/B Test Results
This project was completed as part of Udacity's Data Analyst Nanodegree Program certification in December 2020.

# Summary
The statistical analysis performed helps to understand the results of an A/B test run by an e-commerce website. This project is aimed at helping the company understand 
whether they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision. Two statistical techniques were used to 
achive results. A/B Testing and Regression approach.
The datasets for this project, were provided by Udacity as part of the Data Analsis Nanodegree Program.

# A/B Testing Approach 
- Start A/B testing by making a claim (setting up hypothesis testing)
- Simulate the values of the statistic that are possible from the null by bootstrapping sampling distributions and p-value calculations
- Make a decision based on the likelihood the data came from the null hypothesis considering the type I error threshold
- Performing z-test

# Logistic Regression Approach
- Statsmodels used to fit the regression model specified to see if there is a significant difference in conversion based on which page a customer received
- Assessment of how well the model is performing using a variety of metrics, like countries the users are from and the interactions among variables

# Technologies Used
- Python, Numpy, Pandas, Matplotlib, proportions_ztest, StatsModels
- LaTex
- Jupyter Notebook

# Results
- There is not sufficient evidence to predict that the new page results in more conversions than the old page.
- There is not enough evidence to suggest that country of the user has an effect on the conversion rate.

# Resources

### [Mastering Dates and Timestamps in Pandas (and Python in general)](https://towardsdatascience.com/mastering-dates-and-timestamps-in-pandas-and-python-in-general-5b8c6edcc50c)

### [Extracting days from a numpy.timedelta64 value and calculating the duration](https://stackoverflow.com/questions/18215317/extracting-days-from-a-numpy-timedelta64-value)

### [Join columns of another DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.join.html)

### [The Advantages & Disadvantages of a Multiple Regression Model](https://sciencing.com/advantages-disadvantages-multiple-regression-model-12070171.html)

### [What is a p-value and how do you calculate it?](https://rebeccaebarnes.github.io/2018/05/01/what-is-a-p-value)

