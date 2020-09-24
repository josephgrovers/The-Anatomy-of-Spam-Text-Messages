# **The Anatomy of Spam Text Messages**

---

This is a topic chosen for Project 4 on Unsupervised Learning & NLP, for the Metis Data Science Bootcamp - Summer 2020 Cohort.

## Context

Spam messages and emails is an annoying part of the reality of having instant text communication. An important component present in most messaging services is the spam filter. What does spam look like?

## Objective

Learn what causes SMS messages to be tagged as spam. Use unsupervised learning to cluster messages, and find the distinct differences between how spam is structured compared to ham.

## Findings
Creators of spam messages don’t seem to be very creative. Spam messages seem to generally follow a formula, and don’t stray too far away.

There do seem to be distinct differences between how spam messages are put together, compared to ham. This is as far as words used or not used, and word associations within spam message structure.

# Methodology

## Gathering data:

UCI Machine Learning's SMS Spam Collection Dataset was downloaded from [Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset/notebooks).

Columns in data were renamed and organized, then pre-processed.

## Exploring and modeling data:
Data was cleaned and tokenized for use in word-processing.
Word2Vec was used for word embeddings then document embeddings.
Dimensionality reduction was done with t-SNE, then average word embeddings were used before making a document vector again with t-SNE.
After clustering, the texts and cluster assignments per text were re-joined with the spam/ham labels to see how much of each cluster was spam. 
After this, I hand-picked some text selections to explain a few parts of the cluster map.


* [Full data and analysis](data_and_analysis)
  * [Part 1 - Pre-Processing](data_and_analysis/Project_4_-_Part_1_-_Pre-Processing.ipynb)
  * [Part 2 - Modeling](data_and_analysis/Project_4_-_Part_2_-_Modeling.ipynb)
* Presentation Deck
  * [PDF version](presentation/Joseph_Grovers_-_Project_3_-_The_Anatomy_of_Spam_Text_Messages.pdf.zip)
  * [Google Slides version](https://docs.google.com/presentation/d/1e6EABpbx1CqDCQ3UL5VzrSUne7YrF41TbQcQ9ofR55Y/edit?usp=sharing)
  * [PPT version](presentation/Joseph_Grovers_-_Project_3_-_The_Anatomy_of_Spam_Text_Messages.pptx.zip)

### [Joseph Grovers GitHub](https://github.com/josephgrovers)

## Technologies Used

* Jupyter Notebook
* Python

* NLTK

* gzip

* Gensim

* Logging


* Word2Vec

* re

* SKLearn

* wordcloud

* Pickle

* Matplotlib

* Seaborn

* SKLearn

* Numpy

* Google Slides

* Microsoft Excel

## Presentation Materials Used

* Slidesgo - Template
* Flaticon - Icons
* Freepik - Infographics & images