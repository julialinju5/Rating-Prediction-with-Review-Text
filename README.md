# Rating-Prediction-with-Review-Text


This research reveals how sentiment analysis on review text could predict user rating on a purchased product using bag-of-words technique to process text data into unigrams and bigrams and using their TF-IDF values and word counts of the most popular 1000 words as features. Comparing the prediction results of different linear models with respective MSE values and a baseline model using global average as a constant predictor, the result shows that ridge regression on unigram TF-IDF features has the best prediction results. It achieves 0.8380 MSE on the test set, which is 28.95% lower than the global average rating of the training set baseline.

*This project is for academic purpose and is a group work for 'CSE258: Web Mining and Recommender Systems' in UCSD*
