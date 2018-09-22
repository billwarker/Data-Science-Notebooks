# Data-Science-Notebooks
A collection of data science exercises

## [Amazon Unlocked Phone Analysis](https://nbviewer.jupyter.org/github/billwarker/Data-Science-Notebooks/blob/master/Amazon_Unlocked_Phone_Analysis.ipynb)
- Conducted an exploratory analysis of the relationships between phone name, brand, price, and rating in over 400,000 product reviews from Amazon.com.
- Trained a random forest classifier on 90,000 reviews to achieve a 85% f1-score predicting positive, negative, or neutral sentiments.

## [Logistic Regression in Tensorflow](https://nbviewer.jupyter.org/github/billwarker/Data-Science-Notebooks/blob/master/Logistic%20Regression%20in%20TF.ipynb)
- A handmade implementation of Logistic Regression using Tensorflow and NumPy.
- Trained the classifer on a toy moons dataset and visualized its predictions.

## [Logistic Regression on the Iris Plants Dataset](https://nbviewer.jupyter.org/github/billwarker/Data-Science-Notebooks/blob/master/Logistic%20Regression%20on%20the%20Iris%20Plants%20Dataset.ipynb)
- A handmade implementation of Logistic Regression using NumPy.
- Implemented an Early Stopping algorithm during training to prevent overfiting and visualized the training and validation set errors over gradient descent iterations.
- Compared results of batch gradient descent vs. early stopping (virtually the same)

## [Spam/Ham Classification](https://nbviewer.jupyter.org/github/billwarker/Data-Science-Notebooks/blob/master/Spam_Ham%20Classification.ipynb)
- Created a text classifer to differentiate spam from ham (i.e. legitimate) emails in the Apache Spam Assassin dataset).
- Used the 'Bag of Words' method of feature extraction to create a matrix of word frequencies.
- Scored an accuracy of 99% on the testing set using a Support Vector Machine classifier.
- By examining the feature importances of a Random Forest Classifier, I was able to discover that the key word feature amongst ham emails in the dataset was the presence of the IMAP web protocol in the "received" field.


