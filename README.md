# Keyrosh Tweets Classification
 Classification of Tweets about Carlos Keyrosh

## PreProcessing

The goal is to prepare the data for further analysis or modeling. The steps involved are as follows:

+ Importing the required libraries: pandas, numpy, hazm, and sklearn
+ Reading the excel file using pandas
+ Dropping unnecessary columns from the data
+ Removing rows with missing values
+ Loading stopwords from a text file and combining it with stopwords from the nltk corpus
+ Stemming the words in the tweets using the hazm library
+ Tokenizing the tweets and filtering out the stopwords
+ Storing the processed tweets and labels in a new pandas dataframe
+ The final dataframe dataset contains the processed tweets and labels.

## Predict

We train Scikit Learn SVM model and thed classify the unlabeled tweets with it.
