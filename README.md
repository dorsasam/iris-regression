# Iris Classification Project
This project involves two main tasks related to the Iris dataset. 
The first task is to identify one type of Iris flower from the others. 
The second task involves encoding the Iris types and fitting a logistic regression model to the data. 
We then use a confusion matrix to examine the model's predictions and calculate precision, recall, and the F1-score.

## Dataset
The Iris dataset contains 150 samples of iris flowers, each with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset includes three types of Iris flowers:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Project Structure
**Part 1**: Identifying One Type of Iris
**Part 2**: Logistic Regression and Model Evaluation

## Part 1: Identifying One Type of Iris
In the first part of the project, we focus on identifying one type of Iris flower from the others.

### Steps:
- Loading the Dataset: The Iris dataset is loaded into a pandas DataFrame.
- Data Exploration: A brief look at the data to understand its structure and distribution.
- Feature Selection: Selecting relevant features for classification.
- Model Training: Training a classification model to identify one type of Iris flower.
- Model Evaluation: Evaluating the model's performance using appropriate metrics.

##Part 2: Logistic Regression and Model Evaluation
In the second part of the project, we encode the Iris types and fit a logistic regression model to the data. We then evaluate the model's performance using precision, recall, and F1-score.

### Steps:
- Encoding Iris Types: Encoding the categorical Iris types into numerical values.
- Splitting the Data: Splitting the dataset into training and testing sets.
- Model Training: Fitting a logistic regression model to the training data.
- Making Predictions: Making predictions on the test data.
- Confusion Matrix: Using a confusion matrix to examine the model's prediction results.
- Calculating Metrics: Calculating precision, recall, and F1-score based on the confusion matrix.

## Results
The logistic regression model's performance was evaluated using precision, recall, and F1-score.

## Installation
To run the project locally, follow these steps:

- Clone the repository:
```sh
git clone https://github.com/dorsasam/iris-classification.git
cd iris-classification
```
- Create a virtual environment and activate it:
```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
- Install the required dependencies:
```sh
pip install -r requirements.txt
```

- Run the Jupyter notebooks or scripts as needed.
