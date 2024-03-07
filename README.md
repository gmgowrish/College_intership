# Human Activity Recognition (HAR) using wearable sensor data.

It includes several steps:

### Import libraries:

This section imports necessary libraries like pandas, matplotlib, scikit-learn, etc., for data manipulation, visualization, and machine learning tasks.

### Load data: 

Download The DataSet: https://www.kaggle.com/code/abheeshthmishra/predictions-of-human-activity-recognition-96/input

The code loads the training and testing data from CSV files assumed to be located in the "Dataset" folder.

### Data exploration: 

It performs some basic data exploration by displaying the first few rows of the data and visualizing the distribution of activity labels.

### Feature analysis:

The code counts the occurrences of features related to accelerometers, gyroscopes, and other sensors to understand the feature distribution.

### Time series analysis:

It analyzes the time series data for the "STANDING" activity by creating a new column indicating the time window for each data point based on subject changes.

### Visualization:

The code generates several visualizations, including:

A bar chart showing the distribution of activity labels in the training data.

A pie chart showing the same distribution in a different format.

A bar chart showing the number of features related to accelerometers, gyroscopes, and other sensors.

A line plot visualizing the "angle between X and mean Gravity" vs. time for different subjects.

### Machine learning:

The code trains and evaluates four different machine learning models (Support Vector Classifier, Logistic Regression, K-Nearest Neighbors, and Random Forest) for activity classification and prints their accuracy scores.

### Visualization:

Finally, it creates a bar chart to compare the accuracy scores of these models.
