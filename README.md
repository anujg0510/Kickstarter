A take on data wrangling and machine learning concepts with the Kickstarter projects dataset available on Kaggle.

The datasets can be accessed online via this URL - https://www.kaggle.com/kemical/kickstarter-projects

There are two .csv files attached to the project, dated December 2016 and January 2018 respectively. The files present a snapshot of all the Kickstarter projects as on the respective dates. 

The attached notebook endeavours to apply data wrangling, statistical inferences and machine learning concepts to the datasets.

Key undertakings in this notebook, from a learner's perspective, are:
  - Data cleaning - commas in the name column add unintended right-ward shifts in the columns to the right (it's a CSV file). This anomaly has been taken care of by     reversing this shift with the help of loops
  - Reading currency conversions from an online source (av-forex) and incorporating in the dataset
  - Merging two semi-overlapping datasets and deleting the duplicates
  - Encoding categorical variables
