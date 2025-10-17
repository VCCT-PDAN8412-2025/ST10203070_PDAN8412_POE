# ST10203070_PDAN8412_POE
## Author: Maximilian Walsh
## Student Number: ST10203070

This repository contains the submission for PDAN8412 Part 1 and 2. The part 1 builds and evaluates an LSTM model for multi-class text classification using the Spooky Author Identification dataset for Part 1. Part 2 builds and evaluates a Logistic Regression model for binary classification using the Best Books Ever dataset (available in the add-dataset branch or downloadable here: https://www.kaggle.com/datasets/pooriamst/best-books-ever-dataset/data)

## Contents
ST10203070_PDAN8412_Part1.ipynb – Jupyter Notebook with preprocessing, model training, evaluation, and retraining PART 1.

ST10203070_PDAN8412_Part1_Report.docx / .pdf – Full written report for PART 1.

train.csv – PART 1 dataset with text excerpts (text) and corresponding authors (author: EAP, HPL, MWS).

ST10203070_PDAN8412_Part2.ipynb – Jupyter Notebook with preprocessing, model training, and evaluation PART 2.

ST10203070_PDAN8412_Part2_Report.docx / .pdf – Full written report for PART 2.

books_1.Best_Books_Ever.csv – Part 2 dataset with book metadata (in the add-dataset branch).

README.md – Repository overview.

## How to run Part 2

1. Clone the repository to ensure that both the jupyter and dataset files are available. (The dataset file books_1.Best_Books_Ever.csv is stored in the add-dataset branch and managed via Git LFS)
   
3. Open the Jupyter Notebook ST10203070_PDAN8412_Part2.ipynb in VS Code and ensure it points to the correct CSV file path books_1.Best_Books_Ever.csv.

4. Run all cells from top to bottom. Outputs may vary slightly, but model performance metrics should closely match those reported. 
