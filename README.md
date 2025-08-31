CSE 572: Data Mining - Homework 1
This repository contains the complete implementation and analysis for Homework 1 of CSE 572 (Data Mining), focused on predictive modeling using the Titanic dataset.

Repository Structure
.
├── titanic-data-science-solutions.ipynb   # Baseline notebook based on Kaggle Titanic solution
├── updated.ipynb                          # Modified notebook with improved preprocessing
├── titanic/
│   ├── gender_submission.csv
│   ├── test.csv
│   └── train.csv
├── hw1.pdf                                # Assignment description
├── titanic.zip                            # Compressed dataset files
└── .conda/                                # Local Conda environment directory (excluded from Git)

Environment Configuration
All code is written in Python and intended to be run within a local Conda environment.

Create and Activate Environment
conda create --prefix ./CSE-572/.conda python=3.9
conda activate ./CSE-572/.conda

Required Libraries
Ensure the following packages are installed:

pandas

numpy

matplotlib

seaborn

scikit-learn

Install them via:
pip install pandas numpy matplotlib seaborn scikit-learn

Usage Instructions
Clone the repository:
git clone https://github.com/MohakSharma2507/CSE-572-Data-Mining-HW1.git

Navigate to the project directory and activate the Conda environment:
cd CSE-572-Data-Mining-HW1
conda activate ./CSE-572/.conda

Launch Jupyter Notebook or your preferred IDE to open and run updated.ipynb.

Deliverables
The updated.ipynb notebook includes:

Reproduction of baseline model results for all nine classification models mentioned in the assignment.

Improved preprocessing strategies based on class learnings.

A comparative performance analysis of the following classifiers:

Support Vector Machines

K-Nearest Neighbors

Logistic Regression

Random Forest

Naive Bayes

Perceptron

Stochastic Gradient Descent

Linear SVC

Decision Tree

All results are evaluated based on their classification accuracies.
