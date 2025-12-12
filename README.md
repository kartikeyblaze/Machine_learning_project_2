# ML Course Project 2

This repository contains code and notebooks for two classification tasks:

1. Smoker status prediction using biosignals (Kaggle dataset).
2. Forest cover type classification (Kaggle Covertype dataset).

## How to run

1. Create conda env:

conda env create -f environment.yml
conda activate mlproj


2. Place the Kaggle `train.csv` and `test.csv` files in `data/`.

3. Run the notebooks in `notebooks/` or the scripts in `src/`.

# ML Classification: Smoker Status & Forest Cover

## Project Overview
This project evaluates three machine learning models—Logistic Regression, SVM, and MLP—on two datasets:
1. **Smoker Status Prediction** (Binary Classification)
2. **Forest Cover Type** (Multi-class Classification)

## Results
- **Forest Cover:** Optimized MLP achieved **90.88%** accuracy.
- **Smoker Status:** Optimized MLP achieved **75.5%** (replace with your actual smoker result).

## Technologies
- Python, Scikit-Learn, Pandas, NumPy
- LaTeX (for report generation)
