## EPITA Paris - NLP2 Lab 1 - Text Processing and Embeddings

This repository contains the materials and exercises for the first lab session of the Natural Language Processing (NLP) course at EPITA Paris. This lab focuses on fundamental concepts in text processing, including keyword extraction and word and sentence embeddings.

**Lab Structure**

The lab is divided into three main parts:

**Part 1: Keyword Extraction**

* This section explores different techniques for extracting keywords from text documents. 
* You will experiment with three methods:
    * Raw counts: Identify the most frequent words in a document.
    * TF-IDF (Term Frequency-Inverse Document Frequency): Weight keywords based on their importance within a document and across a collection of documents.
    * KeyBERT: Utilize a pretrained KeyBERT model to extract informative keywords.

**Part 2: Word Embeddings**

* This section introduces the concept of word embeddings, which represent words as vectors in a high-dimensional space. 
* You will explore two approaches:
    * Co-occurrence word embeddings: Learn word embeddings based on how often words appear together in a corpus.
    * Introduction to GloVe: Briefly discuss the GloVe (Global Vectors for Word Representation) algorithm for word embedding generation.

**Part 3: Sentence Embeddings**

* This section explores the concept of sentence embeddings, which represent entire sentences as vectors. 
* We will discuss two approaches:
    * Averaging token embeddings: Create a sentence embedding by averaging the word embeddings of its constituent words.
    * Sentence Transformers (BERT-like models): Briefly introduce pre-trained sentence transformers like BERT (Bidirectional Encoder Representations from Transformers) that are specifically trained to capture sentence meaning. 

**Getting Started**

* Clone this repository to your local machine.
* Ensure you have Python and the required libraries installed (refer to the provided instructions).
* Follow the instructions in each part of the lab to complete the exercises.

**Lab Deliverables**

* Complete the provided Jupyter Notebooks for each section.
* Answer the questions posed throughout the lab exercises.

**Learning Outcomes**

By completing this lab, you will gain hands-on experience with:

* Essential text processing techniques like keyword extraction.
* The concept of word embeddings and their creation using co-occurrence methods.
* Sentence embeddings and how they differ from word embeddings.
* An introduction to pre-trained models for sentence embeddings.

**Additional Notes**

* This lab assumes a basic understanding of Python programming.
* Resources and references for further exploration will be provided throughout the lab.
* Feel free to ask questions or seek clarification during the lab session.
