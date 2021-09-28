# XGBoost_text_classification
Created a simple text classification model that predicts the text into one of the 12 classes.\
Performed some data analysis : 1) Number of sample distribution across each class 2) Distribution based on text length across the 12 classes 3) number of duplicate records in each class.\
Performed text cleaning for removing the punctuation signs, stopwords and performed lemmatization on the words to convert them to thier root form.\
Tranformed the given text to feature vector using TF-IDF and used those feature vectors as a training input for the XGBoost classifier, used the traind model to predict the test file and save the corresponding result to a csv file.
