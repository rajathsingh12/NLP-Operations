# NLP-Operations
This is a small project which comprises few important Natural Language Processing operations that are needed to performed on the raw dataset.


# These are following steps that are necessary to be performed on a dataset to process it for sentiment analysis.

1) Remove all HTML characters in the data.

2) Remove all website links from the data of form www.xyz.com

3) Convert major emoticons to their respective emoticons such as, '😊' to ‘happy’, '😔' to 'sad', '🤣' to 'laugh'.

4) Remove all punctuations except fullstop(.), exclamation (!) and comma (,).

5) Remove major stopwords.

6) Lemmatize all the words.

7) Tokenize the data.

8) Finally, convert the data into vector forms using Word2Vec with vector size of 20.
