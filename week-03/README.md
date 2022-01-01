The following folder contains the assignment for week 03.

<h3>Given:</h3>

In this assignment, we will use data from Mashable (www.mashable.com). Mashable is an online magazine that focuses on producing viral content. 
You may wonder: what makes an article go viral? That’s what you will be trying to find out!

You use linear regression to predict the (log) number of shares from the other variables. 
Note that all variables can be calculated before an article is put online. Thus, Mashable could use your model to predict the (log) number of shares.

<h3>Objective</h3>

  - Build a linear regression model to predict the log number of shares an article received.
  
Important note: beause the number of shares has a very right-skewed distribution, a log transformation has been made of the number of shares. 
This makes it easier to work with linear regression. Predict the shares_log variable.

Write a Jupyter Notebook report documenting your investigation.

Data set

The data comes from a study by Fernandes, Vinagre and Cortez (2015). The data set consists of over 30,000 articles with associated variables such as the title length, the article category and the weekday on which it was published. 
For simplicity, some variables have been deleted from the original data file, which can be found on Kaggle (a platform for machine learning).

Included in your Jupyter Notebook

Please add sufficient comments: not just explaining what you are doing, but why you are doing it.

  - Explain briefly in your own words how linear regression works.
  - Your pre-processing steps.
  - The head() of the resulting data frame.
  - Split the dataset into a training and test set.
  - Select exactly 5 variables (collections of dummy variables, such as weekday_is_monday, weekday_is_tuesday, etc. count as 1 variable).
    - Explain why you selected those variables.
    - Make plots of the relation of your selected variables with the target.
    - Comment on the linearity of the relationships.
  - Fit a linear regression model to predict the number of shares (using the training data. Give the equation of the model (please use Markdown formulas).
  - Evaluate the model on the test data.
    - Predictive power of the model (R2, RMSE).
    - Investigate the residuals.

