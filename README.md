##Welcome to My Open The Iris project

##Description
The code in this repository performs the following tasks:

Loading Dataset: The dataset is loaded from an online source using pandas.
Summarizing Dataset: Summary statistics and class distribution of the dataset are printed to provide an overview.
Univariate Plotting: Histograms are plotted for each attribute in the dataset to visualize their distributions.
Multivariate Plotting: Scatter matrix plots are generated to visualize the relationships between attributes.
Model Evaluation: Several machine learning models are trained and evaluated on the dataset using cross-validation. The following models are evaluated:
Decision Tree
Gaussian Naive Bayes
K-Nearest Neighbors
Logistic Regression
Linear Discriminant Analysis
Support Vector Machine

##Task
In Data Science, the winning combo is pandas (and/or numpy), matplotlib, sklearn (and/or keras). In this project, we will use:

pandas to load the data matplotlib to do the visualization sklearn to do the prediction Load dataset url = "URL" dataset = read_csv(url) Summarizing the dataset A - Printing dataset dimension

print(dataset.shape) B - It is also always a good idea to eyeball your data.

print(dataset.head(20)) C - Statistical Summary The statistical summary includes the count, mean, the min and max values, and some percentiles.

print(dataset.describe()) D - Class Distribution Group by to see how our data are distributed.

print(dataset.groupby('class').size())

##Installation & Usage
pip install pandas pip install matplotlib pip install sklearn

jupyter-notebook --no-browser
