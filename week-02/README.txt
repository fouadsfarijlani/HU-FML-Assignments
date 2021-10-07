Objective

Exploring a numerical variable and its interaction with multiple variables, both numerical and categorical. 
Make a Jupyter Notebook, put it on GitHub and make a link to it.

Dataset

For a study in France, over 900 volunteers received a Fitbit Zip (a clip-on activity tracker) and recorded their daily steps, distance and calories.

Assignment

Make a Notebook with the following elements. Please add sufficient comments: not just explaining what you are doing, but why you are doing it.
Tip: copy and adapt last week's assignment.

  - Your data pre-processing steps
  - Create the variable mean steps per participant. Hint: combine Pandas .loc and .mean() with the right axis argument (axis=....) for mean(). Look up the documentation of .loc and Pandas .mean() if you're unsure. 
  - The head() of the resulting data frame
  - The relation of mean_steps per participant with at least 2 other numerical variables (e.g., how are steps related to weight, height).
    - Scatter plot matrix including all 3 variables.
    - Scatter plots of your variable with the 2 other variables (2 scatter plots in total).
    - Pearson’s correlation for the 2 relations.
    - Verbal description of the relations, including strength of the association, linearity, etc.

  - The relation of mean steps per participant with a categorical variable with two levels (e.g. gender, weekday vs weekend).
    - Graphs of the relation (e.g. histogram, violin plot, bar plot).
    - Verbal description of the relation.
  - The relation between two categorical variables.
    - Graphs of the relation (e.g., bar plot).
    - Cross table with relevant percentages.
    - Verbal description of the relation.

