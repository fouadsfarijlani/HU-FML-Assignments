The following folder contains the assignment for week 05.

Given:

In this assignment, you are going to apply what you learned about machine learning to a dataset of your choice on Kaggle (Links to an external site.).
Kaggle is an online platform where data scientists can find datasets and enter competitions to predict certain outcomes. 
In these competitions, Kaggle users can download data and create their model.

Objective

Predict the outcomes in a data set using either Random Forest, Decision Tree or k-NN. Write a Jupyter Notebook report documenting your investigation.

Dataset

You can choose from the following data sets:

  - Speed dating experiment (Links to an external site.): predict the variable dec_o (decision by partner).
  - Gender recognition of voice (Links to an external site.): predict the variable label (male or female).
  - FIFA 18 (Links to an external site.): predict the first item from the variable Preferred Positions (remember the method .split() for strings?).
  - Secondary school students (Links to an external site.): predict the variable romantic (has a romantic interest). Use the file student-por.csv, not the other one.
  - Employee attrition (Links to an external site.): predict the variable attrition.
  
Tips

  - Cut down the data set down to size. Though not strictly necessary, this is strongly recommended to make it easier. 
    Select 7 variables with strong predictive value, based on your knowledge of the topic (domain knowledge) and/or correlation. 
    Remember to subset the data with df[[‘column 1’, ‘column2’, ‘column3’]]. Don't spend too much time on this step. 
    It's supposed to make the assignment easier, not harder.
    
  - If you find the dataset is too big and calculations take too long, 
    take a random sample with the Pandas method .sample() and run the analysis with the entire data at the end.
    
Included in your Jupyter Notebook

Please add sufficient comments: not just explaining what you are doing, but why you are doing it.

  - Which dataset and variables you selected and why.
  - Your pre-processing steps (e.g., transformations of variables).
  - The head()of the resulting data frame.

Classification

  - Choose one of the following: k-nearest neighbor, decision tree or random forest.
  - Explain briefly in your own words how the algorithm works.
  - Split the data set into a training and test set.
  - Train the model.
  - Evaluate the predictive performance of your model on the test set

Please provide a link to your Notebook on GitHub. Make sure the GitHub folder includes the data file so the Notebook runs without problems.
