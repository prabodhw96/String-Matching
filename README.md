# String Matching in Python
## Overview
Traditional approaches to string matching are too slow for large datasets. Using TF-IDF with N-Grams as terms to find similar string transforms the problem into a matrix multiplication problem, which is computationally much faster.
## Dataset
SEC EDGAR database has 663000 companies listed, which includes all companies in the EDGAR database.<br>
Downloaded from [Kaggle](https://www.kaggle.com/dattapiy/sec-edgar-companies-list)
## Future Scope
Matches created with this method are quite good, as the strings are very similar. This method can be scaled to much larger datasets by using distributed computing environment.