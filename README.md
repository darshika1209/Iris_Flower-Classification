# Iris Flower Classification using Machine Learning

## Overview
This project uses supervised machine learning to classify Iris flowers into three species based on their physical measurements.

## Dataset
The dataset contains 150 samples with four input features:
- Sepal length
- Sepal width
- Petal length
- Petal width

**Target variable:** Species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)

The `Id` column is excluded from model training because it serves as an identifier rather than a flower measurement.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Workflow
1. Loaded and inspected the dataset.
2. Checked for missing values and duplicate rows.
3. Explored feature relationships and species distributions using visualizations.
4. Split the data into training and testing sets.
5. Trained three classification models:
   - Decision Tree
   - Logistic Regression
   - Random Forest
6. Evaluated the models using accuracy, a classification report, and a confusion matrix.
7. Tested the model on a new flower measurement sample.

## Results
All three models achieved **100% accuracy on the 30-sample test set**.

This result applies to the selected test set and does not guarantee perfect performance on unseen data.

## Project File
`iris_model.ipynb` — Jupyter notebook containing the implementation, evaluation, and visualizations.

## Future Improvements
- Evaluate generalization using cross-validation.
- Test the models on additional unseen samples.
- Improve the notebook's documentation and visualizations.
