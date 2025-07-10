**Sentiment Analysis using Fine Tined BERT IMDb data set

This project fine tunes a BERT style LLM on the IMDb dataset for binary sentiment classification (Movies reviews on positive or negative). 

This was completed as part of the Research Methods (7PAM2015) module assignment.


**Objective

Explore the capabilities of BERT in understanding and classifying the sentiment of natural language text through supervised fine tuning.

**Model

Base model - Bert base uncased
Framework - Hugging face transform
Task - Binary sentiment classification
Fine tuning - 2 epochs
	      learning rate = 2e-5
	      batch size = 16


**Data set 

Source - IMBd data set from Hugging Face Datasets
Size - 50 000 labelled
Classes - Positive and negative

**Results

Accuracy = 85%
F1 score = 84%
Visualize = Confusion matrix
