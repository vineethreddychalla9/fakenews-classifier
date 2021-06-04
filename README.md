# fakenews-classifier
I have created a fake news classifier. This model is capable classifying a given news article as a fake news or not with an accuracy of 95%.
Here i have used stemming to convert the sentences to the root form of the words. I have used TF-IDF vectorizer so that i can convert words to the vector form along with not losing the importance of words in the sentences.
now,to train the model i have used PassiveAggressiveClasiifier with has yeilded me an accuracy of 95%. I have also tried different techniques like MultinomialNaiveBias to train the model and also used different methods such as bag_of_words and lemmatization to preprocess the data along with training the model with both complete news and with only the title. And the noticed that using complete news is yeilding a better performance.


Dataset:https://www.kaggle.com/c/fake-news/data
