
# Project Title

Email spam detection system is used to detect email spam using Machine Learning technique called Natural Language Processing and Python, where we have a dataset contain a lot of emails by extract important words and then use naive classifier we can detect if this email is spam or not.

# Prerequisites

This is list of required packages and modules for the project to be installed :

Python 3.x , Pandas,
Numpy ,
Scikit-learn ,
NLTK

# Dataset

The dataset used here is dowloaded from Kaggle

# Coding Section

In this part we will see the project code divided to sections as follows:

Section 1 | Data Preprocessing :
In this section we aim to do some operations on the dataset before training the model on it,
processes like :

Load dataset
Check for duplicates and remove them
Check for missing data for each column
Cleaning data from punctuation and stopwords and then tokenizing it into words (tokens)
Convert the text into a matrix of token counts
Split the data into training and testing sets

Section 2 | Model Creation :
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and thin fit it to the data.

Section 3 | Model Evaluation :
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.

# Conclusion

With an accuracy score of 97.91% spam email is detected