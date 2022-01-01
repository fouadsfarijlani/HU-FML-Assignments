The following folder contains the assignment for week 01.

<h3>Objective<h3>

Learning how to clean data and to investigate distributions. Make a Jupyter Notebook, put it on GitHub and make a link to it.

Dataset

For this assignment, we are going to explore data from activity trackers. 
Activity trackers are applications that track your activity using your smartphone, a smartwatch, wrist band or a clip-on device. 
Popular applications include Steps (iPhone), Apple Watch, Fitbit and Jawbone. 
For a study in France, over 900 volunteers received a Fitbit Zip (a clip-on activity tracker) and recorded their daily steps, distance and calories.

The data were simulated from the actual data to conform to the GDPR law. 
So these are not the real data, but the distributions of the variables and the relations between them are very similar.

Citation:

Hermsen, S., Moons, J., Kerkhof, P., Wiekens, C., & De Groot, M. (2017). 
Determinants for sustained use of an activity tracker: observational study. JMIR mHealth and uHealth, 5(10).

Assignment

Make a Notebook with the following elements. Please add sufficient comments: not just explaining what you are doing, but why you are doing it.

- Your data pre-processing steps.
- The head() of the resulting data frame.
- An analysis of one quantitative variable (e.g. mean steps per participant), including:
  - 2 graphs of the distribution (e.g., histogram, box plot, density plot, violin plot)
  - Summary statistics (measure of central tendency and variation, e.g., mean, median, variance)
  - Verbal description of the distribution, including an investigation into its normality, skewness, outliers, etc.
  
- Extra challenge: a plot of a time series of your choice, e.g. mean steps per day over all participants. Tip: use built in .mean() method in Pandas.

Tip: you will encounter some common problems with these data files, such as: 
American and European CSV formats, faulty data entry, impossible values (wrong entries?).
