# Named-Entity-Recognition-Guide

## Introduction
We humans are capable of recognizing and interpreting categories/tags such as Person, Location, Date, Time etc of words given in a particular sentence or paragraph. This has proved to be  a great boon for humanity in communicating with each other. This helps us in improving teamwork skills and efficiency in completion of the job. <br>
So how great will it be if our highly intelligent computer machines would replicate our human mind tendencies to interpret a high level language such as English. To implement this we take use of computer’s Natural Language Processing(NLP) techniques to analyze natural languages. This involves techniques such as relationship extraction, speech processing, document categorization  and summarizing of text. These analytical methods are further based on fundamental techniques such as tokenization, sentence detection, classification, and relationship extraction. 

## Why is NLP Hard?
Analyzing natural language by a machine is not so easy. There are several constraints which are needed to be considered. For example, at abstract level there are hundreds of natural language each having its own rules, while at character level we need to find a way to deal with special characters, punctuations, hyperlinks etc. <br>
Most basic task in NLP is tokenization  that is process of breaking up of text into series of words. These words are known as tokens. But with languages like japanese, chinese, hindi etc it is difficult to tokenize. While in english most problems arise due to ambiguity of words for example “Georgia” can be classified as both name and location.

## Named Entity Recognition(NER)
Named Entity Recognition is a word processor which classifies text based on person, location, money, time, date etc. This technique finds its application in chat-bots, queries on wikipedia and quora, word prediction like Google search, etc. <br>
This technique can be divided into two parts: 
- Detection of entities (TOKENIZATION) 
- Classification of entities (CLASSIFIER)

Although tokenization will help us in detecting most of the words however ambiguity of word meanings can lead to failure in classification as seen in example of “Georgia”. <br>
Since machine cannot understand high level languages, we need to break down the text into chunks of words so that machine can understand it easily. The process of breaking down of sentences into array of words is known as Tokenization. To perform most of the NLP tasks discussed earlier we are required to tokenize the text for further analysis.

## Guide to NER -->
This section includes many techniques that are used to solve the problem at our hand:
- Bidirectional LSTM [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anshulp2912/Named-Entity-Recognition-Guide/blob/master/source/NER_BiLSTM.ipynb)
