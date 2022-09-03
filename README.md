# Youtube-Comments-Spam-Classification

## Data Set Information

The data set can be downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection).
It is a public set of comments collected for spam research. It has five datasets composed by 1,956 real messages extracted from five videos that were among the 10 most viewed on the collection period.

The table below lists the datasets, the YouTube video ID, the amount of samples in each class and the total number of samples per dataset.

| Dataset | Youtube ID | # Spam | # Ham (not spam) | Total |
| --- | --- | --- | --- | --- |
| Psy | 9bZkp7q19f0 | 175 | 175 | 350 |
| KatyPerry | CevxZvSJLk8 | 175 | 175 | 350 |
| LMFAO | KQ6zr6kCPj8 | 236 | 202 | 438 |
| Eminem | uelHwf8o7_U | 245 | 203 | 448 |
| Shakira | pRpeEdMmmQ0 | 174 | 196 | 370 |

## Machine Learning Models

*Note: The models used are not compared strictly (non-optimised).*


| Model | Accuracy |
| --- | --- |
| Linear Regression | 0.95408 |
| Random Forest Classifier | 0.96939 |
| Multi-Layer Perceptron | 0.94388 |
| XGBoost | 0.92347 |
| Naive Bayes | 0.875 |
