# SentimentAnalysis
Product Sentiment Analysis with TuriCreate.
Sentient Analysis with TuriCreate and Python was one of the most interestiing projects as I got an indepth first-hand experience to how a machine processes and understands human sentiment.

Using TuriCreate's _.count_words()_ function in the _.text_analytics_ package, we can count the number of words each sentence has. In this case each person has a review on a particular product. Using the above functions and packages we realize the actual number of words from which a true meaning of the review can be deduced. For example, if a review has the word amazing used 5 times and the word bad used twice, we can understand that the person is happy about the recieved product and thus the review could be deemed as positive.

Using an **ROC_curve** (which is like a Sigmoid Function) we can get a probability of the review which is then stored as a sentiment. On co-tabulating with the reviews we could see that those reviews which are a 5-star or 4-star have high values while the other reviews have decreasing values.

We can also use some specific words, and based on these words a model could be trained. Values for each of these special words can be tabulated and based on these words as features, a Machine Learning model can be created.

The model used to classify a positive or negative review is a **_Logistic Regression Classifier_**.
