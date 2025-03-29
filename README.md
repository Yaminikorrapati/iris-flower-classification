Iris Flower Classification

Project Overview

This project develops a classification model to identify Iris flowers into three species: Iris-setosa, Iris-versicolor, and Iris-virginica. The dataset includes sepal and petal measurements to train and evaluate machine learning models for species prediction.

Dataset

The dataset consists of:

sepal_length: Length of the sepal in cm

sepal_width: Width of the sepal in cm

petal_length: Length of the petal in cm

petal_width: Width of the petal in cm

species: Target variable (Iris-setosa, Iris-versicolor, Iris-virginica)


Project Structure

IRIS.csv - The dataset file

iris_classification.ipynb - Jupyter Notebook with code for data processing, model training, and evaluation

README.md - Project documentation


Installation & Requirements

Ensure you have Python installed along with the following libraries:

pip install pandas numpy seaborn matplotlib scikit-learn

Steps in the Notebook

1. Load and explore the dataset


2. Data preprocessing (handling missing values, encoding, scaling)


3. Exploratory Data Analysis (EDA)


4. Feature selection using correlation matrix


5. Model training (Random Forest Classifier)


6. Model evaluation using accuracy, classification report, and confusion matrix



Results

The trained model achieves high accuracy in predicting the correct species. Further tuning and alternative models can be explored to optimize performance.

How to Run

1. Open the Jupyter Notebook: jupyter notebook iris_classification.ipynb


2. Run the cells sequentially to execute data processing and model training.



Contributing

Feel free to improve the model or experiment with other classification algorithms. Pull requests are welcome!

License

This project is open-source and available for educational purposes.
