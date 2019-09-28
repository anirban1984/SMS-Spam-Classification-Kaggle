# SMS-Spam-Classification-Kaggle
The aim of the project is to classify SMS messages into spam/ham using ML techniques. Leveraged NLTK and scikit-learn libraries to build a Naive Bayes classifier which achieves an accuracy of 97% on test dataset

# Data

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

# Data Preprocessing

We converted all the words in a message into lowercase and removed punctuation and stopwords. We tokenize the words in a message and use TFIDF scores as features to predict whether a message is a ham/spam.

# Modeling Approach

We split the dataset of 5574 messages into 4459 messages (for training) and 1115 messages (for validation). We used a Multinomial Naive Bayes classifier to predict whether a message is ham/spam. We achieve an accuracy of ~97% on the test dataset.
