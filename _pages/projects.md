---
layout: archive
title: "Code Projects"
permalink: /projects/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<br>Code projects on Github
=======
## Natural Language Processing 
#### mainly from *CSCI 5832 Natural Language Processing* and previous research
- Text classification with XLNET, logistic regression, BI-LSTM/SVM with embeddings. The data including a hotel reviews and SemEval shared task 4 for 'Don't Petronize Me' detection. The implementation with pytorch, keras, tensorflow, sklearn.
[[repo]](https://github.com/Konic-NLP/text-classification)


- Name Entity Recognition with token-based tagging(BIO/BIOE)
  - NER with BERT, which loaded the pre-trained model from huggingface[[repo]](https://github.com/Konic-NLP/BERT-NER/blob/main/copy_of_ner_bert.py)
  - BI-LSTM implementation with tensorflow, can choose BI-LSTM or IDCNN as the model architecture, IDCNN is faster. [[repo]](https://github.com/Konic-NLP/NER/blob/main/NER-BERT.py)
  - CRF++(C++ source)/CRFsuite implementation, the feature template can be edited by the users. [[repo]](https://github.com/Konic-NLP/NER) 

***********
## Machine Learning
#### mainly from *CSCI 5622 Machine Learning*
- Course Project: The bigger, the better? [[Poster]](https://konic-nlp.github.io/files/final_poster_5622.pdf) [[email me to access the code]](sijia.ge@colorado.edu)
  - compare the performance of image classification task on CIFAR-19 dataset between a vanilla CNN and a CNN including ResNet-50 pretrained models.
  - The experiments show that after preprocessing like Deep-Image-Prior(DIP) on the nosiy data, the perfomance on a vanilla CNN can perform in the similar level to that on a complicated CNN leveraging ResNet-50 without denosing. The vanilla CNN trains faster, less weights.
  - Also find variables such as optimizer, upsampling impact differently on different CNN.   
- Kaggle competition: Bike shared count[[Kaggle page]](https://www.kaggle.com/competitions/csci-5622-ps4-22-fall/overview) [[email me to access the code]](sijia.ge@colorado.edu)
  - leverage Exploratory Data Analysis, feature engineering for handling data format features, feature transformation&normalization, and XGBoost with Parameter Gridsearch
  - Rank #3/52 in Public leaderboard with R^2=0.935 and #9/52 in Private Leaderboard with R^2=0.939
- Implementation from scratch with numpy to mimic scikit-learn: KNN, Naive Bayes, Decision Tree, Bagging&Boosting, K-means, logistic regression, MLP[[email me to access the code]](sijia.ge@colorado.edu)
***********
## Computer Vision
#### Mainly from *CSCI 5922 Neural Networks and Deeplearning*
- MNIST recognition with scikit-learn [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment1_.ipynb)
- Cifar-10 image classification with Keras(using regularization L2/Batch Normilization/Drop out) [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment2.ipynb)
- Viz-Wiz challenge: VQA for blind people, extracting questions and image features via BERT and VGG-16, then feed the flatten feature vector into a MLP. [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment4.ipynb)

**************

## Software Development and Object-Oriented Design
#### Mainly from *CSCI 5448 Object-Oriented Analysis and Design*

- UMR writer: An Online annotation platform for UMR project, based on Flask framework, PostgresSQL as database and SQLalchemy as ORM, vanilla JS//Jquery/HTML/CSS as front-end, mainly focus on Events listener and DOM operation. The application is deployed at Heroku. [[repo]](https://github.com/jinzhao3611/umr-annotation-tool)
- A music store simulation, including the functionality like placing an order, checking the inventory, sell the items, buying items and so on. Injecting design patterns into the code, including factory, strategy, decorator, command, observer, singleton. Design with class UML, state diagram and sequence diagram. The language we use Java.[repo](https://github.com/Konic-NLP/OOAD-project)

- A online e-commerce shopping website development. Implementing with Django 2,  we use JS and Jquery for front end and Django-admin for backstage management.[repo](https://github.com/Konic-NLP/final-project-OOAD)


****************

## Coding Practice 
#### Mainly from self-study and Coursera
- Python Data sturcture and Algorithms.[repo](https://github.com/Konic-NLP/Data_sturcture_algorithms)  ![update](https://img.shields.io/github/last-commit/Konic-nlp/Data_sturcture_algorithms/main?label=last%20update&style=plastic)

- Java Learning with UCB CS 61B. [[repo]](https://github.com/Konic-NLP/Java-learning)
- Machine Learning(implemented with *Machine Learning in Action*).[[repo]](https://github.com/Konic-NLP/Machine_Learning)
- Different Deep Learning Framework learning and Practice including Keras, Pytorch, Tensorflow 2 with NLP/CV and deep learning basics.[[repo]](https://github.com/Konic-NLP/DLFL)

