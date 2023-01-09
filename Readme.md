# Disaster tweets


## Topic

* In the event of an emergency, people can use their smartphones and tweet in real time to alert the emergency services and get them to respond more quickly.
* It is thus legitimate to distinguish between tweets that relate to real disasters and tweets that look like them but describe something else.
* This is a Kaggle competition, you can find more details by clicking [here](https://www.kaggle.com/c/nlp-getting-started/overview/)
* This is clearly an application of natural language processing (NLP).


## Objective 

* Our goal is to build a supervised learning model capable of predicting whether a tweet is about a real or fake disaster.
* This model should be able to identify tweets about real disasters: we will seek to minimize the Type II error so as not to miss a real catastrophe.
* To do so, we can rely on a dataset containing 10 000 tweets describing a real or fake disaster, divided into a training set and a test set. 


## Issues

* Here, Data Preparation is a long phase: we need to carefully pre-process the data before implementing any model.
* Recurrent neural networks are the preferred tool for building a prediction model in NLP: a multitude of architectures is possible and a compromise will have to be made between the efficiency of the model and the number of network parameters.


## Technologies

* To prepare the data, I mainly use Pandas and another python package, Spacy, specialised in text processing.
* I worked on Google Colab for the Modeling phase in order to be able to use remote computing resources to train the different models.