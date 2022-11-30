## Sentiment analysis

Sentiment analysis using TfidfVectorizer and Multinominal Naive Bayes classifier from the twitter data. The data is preprocessed and cleaned using the following steps:

1. Remove special characters
2. Remove numbers
3. Remove stopwords
4. Remove short words
5. Lemmatize the words
6. Tokenize the words
7. Convert the words to lowercase
8. Remove the words that are not in the english dictionary
9. Remove the words that are in the english dictionary but are not in the nltk corpus
10. Remove the words that are in the nltk corpus but are not in the english dictionary

The data is then split into training and testing data. The model is trained on the training data and tested on the testing data. The accuracy of the model is calculated and the confusion matrix is plotted. The model is then used to predict the sentiment of the given text.
