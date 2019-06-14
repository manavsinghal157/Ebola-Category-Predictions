# Ebola-Category-Predictions
## Description
To predict the category to which a Tweet on Ebola belongs to from data mined from Twitter.
This was done as part of my Summer Internship at CNeRG, IITKGP.
## Neural Networks Architectures used:
* LSTM
* Stacked LSTM
* Bidirectional LSTM
* Stacked Bidirectional LSTM
( For all these the 200D twitter GloVe embeddings of Standford NLP was used)
* Multi Layer Perceptron ( For this Universal Sentence Encoder was used instead of GloVe embeddings)
## Results
The maximum test accuracy of 65% was achieved in Stacked Bidirectional LSTM followed by 60% in case of Multi Layer Perceptron using Universal Sentence Encoder.
