Day 1: It was mainly about the basics of Machine Learning (ML).
First, what is Machine Learning (ML)?
Machine Learning is a way of teaching computers to learn patterns from data and make decisions or predictions.

Next, why is Machine Learning needed?

It simplifies human work

Learns from past data

Improves performance automatically over time

Refines the model by learning from failures

Types of Machine Learning:

1. Supervised Learning:
Learns from labeled data (input + output).
Example: A model trained on emails labeled as Spam or Not Spam.

2. Unsupervised Learning:
Learns from unlabeled data.
Example: A shopping website understanding different types of customers without predefined categories.

3. Reinforcement Learning:
Learns through trial and error using rewards and penalties.
Example: A car learning how to drive by interacting with the environment.

Basic ML Workflow:
Problem → Data → Model → Prediction

Define the problem

Collect and prepare data

Train the model

Make predictions or decisions

Task 1: Simple definition of ML
Machine Learning is a technique where computers learn from data to make predictions or decisions on their own.

Task 2:
Predicting future product demand in a store.

Task 3: Problem Breakdown

Problem Statement:
Predict how many units of a product will be sold tomorrow.

Input Data:

Past sales data

Date/day

Price

Promotions

Expected Output:
Number of units to be sold (demand prediction).




Day 2: Dataset Collection & Understanding

Today’s focus was on understanding data, datasets, and how they are used in Machine Learning.

What is Data?
Data refers to raw facts or values such as numbers, text, dates, etc.

What is a Dataset?
A dataset is a structured collection of data used for analysis or training a model.
For example: Daily sales records of a product stored in a file.

What are Features?
Features are independent variables (inputs) used to make predictions.
For example: Date, price, promotions, past sales.

What is a Target Variable?
The target variable is what the model predicts (output).
For example: Units sold tomorrow.

Types of Datasets

Structured Datasets

Organized in rows and columns

Easy to analyze
For example: CSV, Excel files

Unstructured Datasets

No fixed format
For example: Images, videos, text, audio

For my problem statement, I am using a structured dataset.

Common Dataset Format
CSV (Comma-Separated Values) is the most commonly used format in ML because it is lightweight and easy to load using Python (pandas).

Tasks Completed

Task 1: Dataset Selection
I explored multiple datasets and selected the Retail Sales and Customer Demographics Dataset, as it best fits my project.

Task 2: Features and Target Variable

Features: Date, Price, Product Category, Age, Gender, Total Amount

Target Variable: Quantity

Task 3: Dataset Observations

Dataset Size
The dataset contains 1000 rows and 9 columns, suitable for a basic ML model.

Columns Present
Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount.

Possible Data Issues

Date column needs conversion to datetime format

Categorical features require encoding

No direct label for “tomorrow’s sales”; data must be grouped by date

Possible outliers in Quantity or Total Amount

Correlation between Quantity and Total Amount
