# Twitter-Sentiment-Analysis-using-BERT
A massive amount of text data is generated from the internet each day and sentiment analysis provides means of analyzing sentiments, intentions on such data. In this project, we have utilized Google's BERT architecture to perform Binary classification of Twitter data.

BERT (Bidirectional Encoder Representation from Transformers)  has achieved tremendous results in a range of Natural Language Processing tasks including Question Answering and Natural Language Inference. The paper for BERT can be found here: https://arxiv.org/abs/1810.04805

# Setting up the environment

The following libraries will be required

    Pandas
    Matplotlib
    NLTK
    ktrain
    Python 3.x
    Keras
    Tensorflow
    Numpy
    seaborn
    
# Key file descriptions

sampled_data: A collection of 100,000 samples from the original dataset, spread across the two labels.

sampled_data_preprocessed: Preprocessed version of the sampled_data. It is the final dataset, used to create the train and test samples.


# Dataset

The original dataset we used for our project can be found here: http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip.

The original dataset consists of 1.6 million tweets labeled “positive (4)” or  “negative” (0) with very few of them (150) labeled "neutral". For this project, we labeled the positive tweets as 1, and negatives as 0. The  few neutral tweets are also given a label of 1, to make it a problem of binary classification and in a way, our model is specifically detecting negative tweets. Due to time and computational constraints, we used a balanced set of 100,000 samples split into training and validation data containing 80,000 and 20,000 samples, respectively.






