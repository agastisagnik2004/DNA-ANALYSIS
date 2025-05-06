# DNA-ANALYSIS
DNA Sequence Analysis with Machine Learning This project demonstrates how to analyze and classify chimpanzee DNA sequences using machine learning techniques in Python. The workflow covers data preprocessing, feature encoding, classification with K-Nearest Neighbors (KNN), and unsupervised clustering with K-Means, including visualization with PCA.
Features
Data Cleaning: Handles missing values and prepares the dataset for analysis.

DNA Sequence Encoding: Converts DNA sequences into numerical features using label encoding.

Classification: Implements a K-Nearest Neighbors (KNN) classifier to predict DNA sequence classes.

Model Evaluation: Provides accuracy, precision, recall, F1-score, and confusion matrix for model assessment.

Clustering: Applies K-Means clustering on PCA-reduced data for unsupervised grouping.

Visualization: Plots clusters and principal components for exploratory analysis.

Dataset
Source: chimpanzee.csv

Size: 1,682 DNA sequences, each labeled with a class.

How It Works
Preprocessing:

Loads the DNA sequence data.

Checks for missing values.

Encodes DNA sequences into numerical arrays.

Classification:

Splits data into training and test sets.

Trains a KNN classifier (n_neighbors=6).

Evaluates performance with a classification report and confusion matrix.

Clustering:

Reduces dimensionality with PCA (2 components).

Performs K-Means clustering (k=5).

Visualizes clusters and centroids on a 2D plot.

Results
KNN Classifier:

Achieved ~42% accuracy on the test set.

Detailed metrics available in the classification report.

Clustering:

PCA components explained ~27% of the variance.

K-Means clustering visualized distinct groups in reduced dimensions.

Getting Started
Clone the repository and run the provided Jupyter notebook or Python script. Make sure to have the required libraries installed (numpy, pandas, scikit-learn, matplotlib, seaborn).


# Open and run the notebook or script
Requirements
Python 3.x

numpy

pandas

scikit-learn

matplotlib
