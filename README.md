# Automate-detection-of-different-emotions-from-textual-comments-and-feedback
Project Synopsis: 
Developing Emotion Detection and Recognition from text is a recent field of research that is closely related to Sentiment Analysis. Sentiment Analysis aims to detect positive, neutral, or negative feelings from text, whereas Emotion Analysis aims to detect and recognize types of feelings through the expression of texts, such as anger, disgust, fear, happiness, sadness, and surprise.

Data Collection:
Another challenge in emotion detection is the lack of a labeled emotion database to enable active innovation. Currently, few publicly accessible databases are available. The 2 most commonly used databases are ISEAR, which contains 2500 sentences, with 5 categories of emotions Text is extracted from a variety of sources as described below, and people can be crowdsourced to perform labeling using Mechanical Turk. A process, inspired by a DARPA translation project which is also crowd-sourced is put in place to validate the accuracy of labeling

Solution Approach: 
6 emotion categories are widely used to describe humans’ basic emotions based on facial expressions anger, disgust, fear, happiness, sadness, and surprise. These are mainly associated with negative sentiment with Surprise being the most ambiguous, as it can be associated with either positive or negative feelings. Interestingly, the number of basic human emotions has been recently reduced  or rather re-categorized to just  happiness, sadness, fear, surprise, and anger

Data visualization:
A multi-layered neural network with 3 hidden layers was used to tackle the task of learning to identify emotions from text using a bi-gram as the text feature representation. The performance metrics used here are the rates of recall, precision, and accuracy. The dataset used in this experiment consists of 784,349 samples of informal short English messages with 5 emotion classes: anger, sadness, fear, happiness, and excitement where 60% is used for training, 20% for validation, and 20% for testing

Assumptions:
Here the dataset which we have taken is the first train and then it is tested in which we firstly train 60%of the data and 20%for validation and the rest 20%for testing

Exceptions considered:
One of the biggest challenges in determining emotion is the context-dependence of emotions within the text. A phrase can have an element of anger without using the word “
anger or any of its synonyms It is difficult to anticipate the success rate of the machine learning approach without first trying

Algorithms: 
Emotion Detection in text documents is essentially a content-based classification problem involving concepts from the domains of Natural Language Processing as well as Machine Learning.  Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems

Result:
The unweighted accuracy is 85.2% while the weighted accuracy is 80.23. The confusion matrix above shows that this model can classify anger, sadness, and excitement well, but suffers when it comes to fear.

Enhancement Scope:
1. Photographs and videos may be used to expand the work.
2. Exploring additional sentiments classification tasks in different data sets
3. We will put more emphasis on using ensemble approaches to improve device efficiency
