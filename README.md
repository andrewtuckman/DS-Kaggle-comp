# CS506 Midterm / Kaggle Competition

## What is this?

This is my submission for my first Kaggle competition in Fall 2021, where I placed 66th out of 170 competitors. The competition goal was to predict, with as high accuracy as possible, the star rating associated with user reviews from Amazon Movie Reviews using the available features. All of my own working code is stored under 'midterm-file.ipynb'. The link to the Kaggle page is here: https://www.kaggle.com/c/cs-506-midterm-a1-b1/overview.


## Starter Code Instructions

1. Download the `train.csv` and `test.csv` files from Kaggle into the `data/` folder
2. Run `test_setup.py` to make sure you can load the files and print the first few rows of `train.csv` and `test.csv` and view their shapes + some visualization
2. `feature_extraction.py` will help you to generate features as well as generate `X_test.csv` which is `test.csv` but with the features from `train.csv` and whatever other features you added.
3. Run `predict-constant.py` to predict the same score for all rows in the test set
5. Run `predict-knn.py` to predict the score using KNN

Good luck!
