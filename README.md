# Iris Species Classification
# Inter ID: CITS9173
## Project Overview

This project uses machine learning to classify Iris flowers into three species based on their sepal and petal measurements.

The three species are:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## Dataset

The dataset contains 150 observations with four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable is the flower species.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Load the dataset
2. Understand the dataset
3. Check for missing values and duplicates
4. Perform exploratory data analysis
5. Visualize feature relationships
6. Prepare features and target
7. Split the dataset into training and testing sets
8. Scale the features
9. Train a Logistic Regression model
10. Make predictions
11. Evaluate the model
12. Analyze the confusion matrix
13. Test the model with new flower measurements

## Machine Learning Model

Logistic Regression was used as the classification algorithm.

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Key Insights

* The dataset contains 150 Iris flower observations.
* Each species contains 50 observations.
* Petal measurements provide useful information for distinguishing between species.
* Iris Setosa is relatively well separated from the other species based on petal measurements.
* The Logistic Regression model achieved high classification accuracy on the test dataset.

## Project Files

```text
dataset/
    iris.csv

iris_species_classification.ipynb
requirements.txt
README.md
```
