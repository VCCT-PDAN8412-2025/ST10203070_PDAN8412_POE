# ST10203070_PDAN8412_POE
## Author: Maximilian Walsh
## Student Number: ST10203070

This repository contains the full submission for PDAN8412 POE parts 1, 2, and 3. Part 1 builds and evaluates an LSTM model for multi-class text classification using the Spooky Author Identification dataset. Part 2 builds and evaluates a Logistic Regression model for binary classification using the Best Books Ever dataset (available in the add-dataset branch or downloadable here: https://www.kaggle.com/datasets/pooriamst/best-books-ever-dataset/data). Part 3 builds and evaluates a Convolutional Neural Network for multi-class image classification using the Intel Image Classification dataset (downloadable here: https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data).

---

## Contents
ST10203070_PDAN8412_Part1.ipynb – Jupyter Notebook with preprocessing, model training, evaluation, and retraining PART 1.

ST10203070_PDAN8412_Part1_Report.docx / .pdf – Full written report for PART 1.

train.csv – PART 1 dataset with text excerpts (text) and corresponding authors (author: EAP, HPL, MWS).

ST10203070_PDAN8412_Part2.ipynb – Jupyter Notebook with preprocessing, model training, and evaluation PART 2.

ST10203070_PDAN8412_Part2_Report.docx / .pdf – Full written report for PART 2.

books_1.Best_Books_Ever.csv – Part 2 dataset with book metadata, available in the *add-dataset* branch or downloadable from Kaggle: [Best Books Ever Dataset](https://www.kaggle.com/datasets/pooriamst/best-books-ever-dataset/data).

ST10203070_PDAN8412_POE.ipynb - Jupyter Notebook for Part 3 – CNN implementation for image classification.

ST10203070_PDAN8412_POE_Report.docx / .pdf - Full written report for Part 3.

intel_cnn_best.keras - Trained CNN model for Part 3.

intel_manifest.csv, train_manifest.csv, val_manifest.csv - Dataset manifests used for Part 3 training and validation.

README.md – Repository overview.

---

## How to Run the Projects

### Part 1
1. Clone the repository.  
2. Open `ST10203070_PDAN8412_Part1.ipynb` in Jupyter or VS Code.  
3. Ensure the `train.csv` dataset is in the same directory.  
4. Run all cells sequentially to reproduce results.

### Part 2
1. Checkout the `add-dataset` branch to access the dataset or download it from Kaggle.  
2. Open `ST10203070_PDAN8412_Part2.ipynb`.  
3. Update the file path for `books_1.Best_Books_Ever.csv` if needed.  
4. Run all cells from top to bottom.

### Part 3
1. Ensure the *Intel Image Classification* dataset is available (downloadable from [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)).  
2. Open `ST10203070_PDAN8412_POE.ipynb`.  
3. Confirm that `intel_manifest.csv`, `train_manifest.csv`, and `val_manifest.csv` match dataset paths.  
4. Run all cells to train or load the pretrained model `intel_cnn_best.keras`.

---

## Summary
This portfolio demonstrates progressive application of predictive analytics — from classical machine learning to deep learning — across structured, textual, and visual data domains.  
Each part contributes to understanding the scalability and adaptability of predictive modelling techniques in real-world datasets.

---
