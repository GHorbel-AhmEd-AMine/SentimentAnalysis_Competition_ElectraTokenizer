# SentimentAnalysisCompetition_ElectraTokenizer

# Problem Overview 
Sentiment analysis studies the subjective information in an expression, that is, the opinions, appraisals, emotions, or attitudes towards a topic, person or entity. 
Expressions can be classified as positive, negative, or neutral. For example: “I really like the new design of your website!” → Positive.

# Objective 
Building a machine learning model to predict the label of the review either positive or negative.

# Dataset Descreption
we are provided the review datasets taken from different websites like IMDB, Yelp and Amazon. 
There are two features - ‘review’ - the sentence and ‘sentiment’ - the label for the review. 1 means positive review and 0 means negative review.

# How to use this

# Requirements
The requirements.txt file, has all the packages that were in the environment at the time of training.

torch

pytorch

Numpy

scipy

nltk

transformers

# Electra 
**Overview**

The ELECTRA model was proposed in the paper ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators. ELECTRA is a new pretraining approach which trains 
two transformer models: the generator and the discriminator. The generator’s role is to replace tokens in a sequence, and is therefore trained as a masked language model. 
The discriminator, which is the model we’re interested in, tries to identify which tokens were replaced by the generator in the sequence.

# Achievements 
I have achieved an accuracy of 88.1924 % on the test set.

Claim the second position on the competition leaderboard.

