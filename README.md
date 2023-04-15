# Welcome to dating-analysis repository

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which explores the mystery behind finding a romantic patner, using a [dataset](https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment) compiled by professors Ray Fisman and Sheena Iyengar from Columbia Business School. For detailed walkthrough, please view the source code in order from:


1. [Data Extraction and EDA](https://github.com/Topheral/Dating-analysis/blob/main/Data%20Extraction%20and%20EDA.ipynb)
2. [Data Visualization](https://github.com/Topheral/Dating-analysis/blob/main/Data%20Visualisation.ipynb)
3. [Machine Learning (....) ](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)

  
## Contributors

- @topheral - Neural Networks, Data Resampling, Data Extraction
- @ - Logistic Regression
- @ - Data Visualization, Data Extraction

## Problem Definition

- what makes a person successful in finding a significant other?
- Are we able to predict if a person is getting a follow-up date after the first date?
- Which model would be the best to predict it?

## Models Used

1. Logistic Regression
2. Random Forest
3. XGBoost

## Conclusion

Although this was slightly disappointing, it looks like there still is no real answers to the secret of love. It's not interests or hobbies, it's not attractiveness or intelligence or other traits. Really it's just how much someone likes you. Who would have thought?

On the other hand, we did learn a thing or two. To summarize:

- Take your date out to the cliche dinner and a movie because both genders are likely to enjoy it
- Dating is tougher for men (perhaps women can be more selective?)
- More participants experienced unrequited love than those that found love -- so don't feel too bad
- People get their heartbroken regardless of their personal traits like attractiveness, so if you strike out, it's not you that is the problem
- Your impression of yourself is often wrong
- There is no one trait that makes you likeable
- Being likeable is important for securing that second date!

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





