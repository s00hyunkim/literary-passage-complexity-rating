# MSCI 546 (W2023): ML Models for Quora Insincere Questions

> **Author: Team 2**  
> Ashba Adil, Soohyun Kim, Janice Mak, Sharon Wu

## Introduction

![Quora Logo](./images/quora-logo.png)  

Our team's primary objective is **to develop Machine Learning models that identify and flag insincere questions** in Quora.  

We have used 5 different Machine Learning models, including a neural-network based model, to help Quora uphold their policy of "Be Nice, Be Respectful" and continue to be a place for the world to share knowledge.  

To gain a better understanding of our project, please refer to the following documentation and slides:
* [Project Proposal](https://docs.google.com/document/d/13cpXKZvZLVEbxLRvQ2M6xRziCUPR0a3-YB-31aGaTR8/edit?usp=sharing)
* [Presentation Slide Deck](https://docs.google.com/presentation/d/1OfoQqIQrCjAHgOVKa_SjFPxrHhJUXerAx2IpKoCI0Zo/edit?usp=sharing)

## Data

We have chosen the ["Quora Insincere Questions Classification"](https://www.kaggle.com/competitions/quora-insincere-questions-classification) competition dataset from Kaggle.  

This dataset contains **1,306,122 rows** of data with no null or duplicate values. It has **3 data fields** which are:
* `qid`: Unique question identifier
* `question_text`: Question text from a Quora user
* `target`: Binary label for a question with 0 being `sincere` and 1 being `insincere`

For the exploratory data analysis, we referenced the code written by [Ane and Rahul](https://www.kaggle.com/code/anebzt/quora-eda) in Kaggle.

## Model

For this **binary classification task**, the following Machine Learning models have been created:
* Logistic Regression _(Referenced code written by [Lonnie Qin](https://www.kaggle.com/code/lonnieqin/quora-text-classification-with-sklearn/notebook))_
* Naive Bayes
* Decision Tree
* Random Forest _(Referenced code written by [Viraj Bagal](https://www.kaggle.com/code/virajbagal/eda-tsne-traditional-vs-neural-models-nlp))_
* Neural Network _(Referenced code written by our TA, Eddie Park)_

To take a look at the code, please refer to 5 different folders created in this repository.

## Instructions

1. Clone this repository by running the following command in the terminal:
    ```
    git clone https://github.com/s00hyunkim/quora-insincere-questions.git
    ```
2. Visit each folder created for a Machine Learning model and access the `.ipynb` file to run the code.