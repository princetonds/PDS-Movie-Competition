# PDS-Movie-Competition

Here's where you can access the training and test sets for the PDS Movie Competition. Good luck and have fun!

# Downloading the Data

You should download movies_data_test.csv and movies_data_public_train.csv. movies_data_public_train.csv is the training data (where we provide you the revenue values), and movies_data_test.csv is the testing data. To download the data, click on the file in the Github, and then click on "View raw". A new window will pop up with the data in your browser. You should then right click on the window and click on Save as to download the file to your computer. 

sample_submission.csv is an example of what your final submission to EvalAI should look like after predicting on movies_data_test.csv. We will be releasing a starter notebook soon with some basic code to help you get started with the competition.

# Helpful Tips

**Take a look at the starter notebook we have provided to get an idea of how to process the data and start building your models!**

### Helpful Resources for Models:

https://scikit-learn.org/stable/modules/linear_model.html   
Documentation and explanations for several linear models. 

https://scikit-learn.org/stable/tutorial/basic/tutorial.html   
Basic machine learning tutorial using scikit-learn.

https://scikit-learn.org/stable/modules/neighbors.html   
Explanation for the nearest-neighbors algorithm. 

https://www.kaggle.com/learn/intro-to-machine-learning   
Hands-on programming tutorial for machine learning.

https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/   
High-level overview of various techniques.

https://pandas.pydata.org/docs/user_guide/10min.html   
Brief intro to pandas (a very popular data analysis and manipulation tool for Python).

**Pro tip:** tree-based models like XGBoost, AdaBoost, etc. tend to work very well for these kinds of problems. Try using those and see if you get a performance boost!

### Working with Categorical Data:

We think that utilizing the textual categorical data (genres, cast, crew, etc.) as predictors will help improve your model! When we talk about a categorical variable, we mean that this data can only take on one of a fixed set of labels. The categorical variables in our dataset, such as genres or cast, are slightly more complicated in that they can take on multiple labels for each movie. For instance, there can be multiple genres for a particular movie, but these genres come from a fixed set of genres. There are multiple ways to approach this problem, which you can find in the links below. 

https://pbpython.com/categorical-encoding.html   
Guide to categorical encoding.

https://www.analyticsvidhya.com/blog/2015/11/easy-methods-deal-categorical-variables-predictive-modeling/
https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63   
Other useful links: both of these are good introductions to using categorical data in regression tasks. The second link also includes other options such as creating bins.

https://www.pluralsight.com/guides/handling-categorical-data-in-machine-learning-models
https://towardsdatascience.com/machine-learning-on-categorical-variables-3b76ffe4a7cb   
These articles describe how you could use categorical data in machine learning. The first link is more quick and to the point while the second link has more background information.


