# NLP-Notes-Deeplearning.ai
My own notes For Natural Language Processing Specialization by deeplearning.ai [VISIT!](https://www.coursera.org/specializations/natural-language-processing)  
It will contain also another resources for NLP aka BIG-NLP  
Hello there.  
Like to share my experience and notes as well as a review for the new NLP specialization on Coursera.  
I have finished first course of it and i will update this repository incrementally.  
### 1- Natural Language Processing with Classification and Vector Spaces [VISIT!](https://www.coursera.org/learn/classification-vector-spaces-in-nlp)  
I have included its labs in the first folder C01 directory in the repository it contains each week's labs W0X as a Jupyter Notebook files.

### 2- Natural Language Processing with Probabilistic Models [VISIT!](https://www.coursera.org/learn/probabilistic-models-in-nlp)  

# Table of Contents of Tricks
1. [Overview](#Overview)
2. [Prerequisites](#Prerequisite)
3. [Classification and Vector Spaces <sup>C01</sup>](#C01)
4. [Probabilistic Models <sup>C02</sup>](#C02)
5. [Acknowledgement](#ACKNOWLEDGEMENT)
6. [Authors](#AUTHORS)

## Overview
Natural Language Processing (NLP) uses algorithms to understand and manipulate human language. This technology is one of the most broadly applied areas of machine learning. As AI continues to expand, so will the demand for professionals skilled at building models that analyze speech and language, uncover contextual patterns, and produce insights from text and audio.


## Prerequisite
## C01
- a) Perform sentiment analysis of tweets using logistic regression and then naïve Bayes, 
- b) Use vector space models to discover relationships between words and use PCA to reduce the dimensionality of the vector space and visualize those relationships, and
- c) Write a simple English to French translation algorithm using pre-computed word embeddings and locality sensitive hashing to relate words via approximate k-nearest neighbor search.
### WEEK 01 
<b>Problem definition</b> : you have an input vector X aka feature vector and to this input you have a corresponding label or output for this features.  
e.g in Problems at CF/HackerRank, you have samples of inputs and its outputs to help you figure the pattern you need to solve it.  
So far the following context was about the <b>Supervised learning</b> and you are trying now to get the best fit for the mapping between [X] and [Y] vectors.  
<b>How to solve it?</b>  
The best mapping between those vectors you need to minimize the difference between the true labels or vector [Y} and your outcome from input features [X}  
for example you have built your outcome function f(x) = ....   
you apply it on you [X] vectors and get output. the output you get we will compare it with the real output or true labels [Y].
lets call the f(x)= ... output is [Y_pred] and the real output we know before already is [Y] as it was no changes.  
the solution is to minimize the difference between |Y_pred - Y} to make them nearly close to each other.  
To solve it we need to find a function to measure the distance or difference between those two vectors or two outputs, this function is called cost function/loss.  
<b>Types of problems</b> We have two kinds of problems in Supervised learning   
1) Classification . absolute output and expected e.g. one of a list of known outputs  
e.g. at Sentiment analysis you need to classify "Twitter tweet" is it positive or negative?  
e.g. is this picture for a cat or no?  
1- Logistic regression classifier / Logistic classification   
2) Regression  
## C02

###

###
## ACKNOWLEDGEMENT
This Specialization is designed and taught by two experts in NLP, machine learning, and deep learning. Younes Bensouda Mourri is an Instructor of AI at Stanford University who also helped build the Deep Learning Specialization. Łukasz Kaiser is a Staff Research Scientist at Google Brain and the co-author of Tensorflow, the Tensor2Tensor and Trax libraries, and the Transformer paper.
Many thanks to those people.  

## AUTHORS
1- [MOKHTAR](https://github.com/mohamed-mokhtar)
