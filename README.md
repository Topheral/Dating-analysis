# Welcome to dating-analysis repository

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which explores the mystery behind finding a romantic patner, using a [dataset](https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment) compiled by professors Ray Fisman and Sheena Iyengar from Columbia Business School. For detailed walkthrough, please view the source code in order from:


1. [Data Extraction and EDA](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)
  
## Contributors

- @topheral - Neural Networks, Data Resampling, Data Extraction
- @TCaken - Logistic Regression
- @coolcoolwhat - Data Visualization, Data Extraction

## Problem Definition

- what makes a person successful in finding a significant other?
- Are we able to predict if a person is getting a follow-up date after the first date?
- Which model would be the best to predict it?

## Models Used

1. Logistic Regression
2. Neural Networks

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References

- <https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment>





