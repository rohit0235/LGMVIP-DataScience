
---

# Iris Flower Classification

## Description

This project demonstrates the classification of Iris flower species using a Support Vector Machine (SVM) algorithm. The code utilizes the Iris dataset, a popular dataset for machine learning, to perform classification based on the sepal and petal lengths of Iris flowers. The project includes data visualization and the evaluation of the SVM model's performance.

## Features

- **Data Loading**: Loads the Iris dataset from scikit-learn.
- **Data Visualization**: Plots scatter plots of sepal length vs. petal length.
- **Model Training**: Trains an SVM model with a linear kernel on the dataset.
- **Model Evaluation**: Evaluates the model's performance on test data and visualizes decision boundaries.

## Installation and Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/rohit0235/LGMVIP-DataScience.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd iris-flower-classification
   ```

3. **Install the required dependencies**:

   Make sure you have the required Python libraries installed. You can install them using pip:

   ```bash
   pip install numpy pandas matplotlib scikit-learn mlxtend
   ```

4. **Run the project**:

   Execute the Python script to run the classification and visualization:

   ```bash
   python iris_classification.py
   ```

## Code Overview

- **Data Loading**: The Iris dataset is loaded and converted into a DataFrame.
- **Data Visualization**: Scatter plots are created to visualize sepal length vs. petal length.
- **Feature Selection**: The features used are sepal length and petal length.
- **Model Training**: An SVM classifier with a linear kernel is trained on the data.
- **Model Evaluation**: The model's accuracy is evaluated on both the training and test sets.
- **Decision Boundaries**: Decision regions are plotted to visualize the classifier's decision boundaries.

## Technologies Used

- **Python** (Programming Language)
- **NumPy** (Numerical computing)
- **Pandas** (Data manipulation)
- **Matplotlib** (Data visualization)
- **Scikit-learn** (Machine learning)
- **mlxtend** (Plotting decision regions)

## Results

- **Test Accuracy**: 96.67%
- **Training Accuracy**: 95%

## Future Improvements

- Experiment with different kernels and hyperparameters for the SVM.
- Use additional features or perform feature engineering to improve model performance.
- Implement cross-validation to better assess model performance.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
