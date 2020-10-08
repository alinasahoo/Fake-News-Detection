# Fake News Detection

## **Fake News:** 
A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. 
This is often done to further or impose certain ideas and is often achieved with political agendas. 
Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

## **TfidfVectorizer:**

### TF (Term Frequency): 
The number of times a word appears in a document is its Term Frequency. 
A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

### IDF (Inverse Document Frequency): 
Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

## **PassiveAggressiveClassifier:**
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. 
Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

## Detecting Fake News with Python – Objective

To build a model to accurately classify a piece of news as REAL or FAKE. 

The dataset we’ll use for this python project- we’ll call it news.csv. This dataset has a shape of 7796×4. 
The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. 

### Python Libraries & Pre-requisites:
- Numpy
- Pandas
- Scikit-learn
- Jupyter-Notebook/Lab

## Summary:

- Learnt to detect fake news with Python. 
- Took a political dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier & fit our model. 
- Ended up obtaining an accuracy of 92.82% in magnitude.
