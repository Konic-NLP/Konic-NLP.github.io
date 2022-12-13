---
permalink: /
title: "About me([Curriculum Vitae](https://Konic-NLP.github.io/files/CV-full.docx.pdf))"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---  
  
&nbsp;

A self-driven explorer of NLP and related skills with a strong passion for ML/DL, and software development. I immerse myself in the challenging journey with thorns to enrich my CS skills since I am not a CS guy originally. I love fantastic techniques which bring me instant feedback and a sense of accomplishment.
Right now I am working with Prof. Martha Palmer for the AIDA/KAIROS project to compute the similarity of the events based on Wikidata and [UMR writter](http://umr-tool.cs.brandeis.edu/)(an annotation tool for [Uniform Meaning Representation](https://umr4nlp.github.io/web/index.html))

Now I am a student of [Computational Linguistics, Analytics, Search and Informatics Professional Master’s Degree (CLASIC) program](https://www.colorado.edu/linguistics/graduate-program/computational-linguistics-clasic-ms) at [The University of Colorado-Boulder](https://www.colorado.edu/).  Such an interdisciplinary degree is offered jointly by The [Departments of Linguistics](https://www.colorado.edu/linguistics/) and [Computer Science](https://www.colorado.edu/cs/). I got a B.A. degree in the department of Chinese language and literature at Shanxi University (Major in Chinese language and literature) and M.A. degree from Nanjing Normal University(Major in Linguistics and Applied linguistics). 

I have 4 years+ of Python experience and 2 years+ of NLP research experience. My past work focused on lexical analysis (i.e token classification/sequence labeling tasks like named entity recognition and word segmentation, etc); corpus construction(high-quality annotation for text dataset, especially for semantic role labeling, like [Chinese Abstract Meaning Representation corpus](https://www.cs.brandeis.edu/~clp/camr/camr.html) and Chinese FrameNet), and digital humanities(I explore how to structurally represent the meaning of literature like ancient Chinese poems as much as possible).
  
  
Before entering CU-Boulder, I worked as a product manager intern at Beijing Lingosail company(China), designing and upgrading the product ['Termbox'](http://termbox.lingosail.com/) for term extraction.


**My major technical stacks**:  
 - Programming languages: ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) ![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
  - ML/DL: ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)  ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 
  - Web development: ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)	![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 


**Application&Products**


- [**UMR-writer**](http://umr-tool.cs.brandeis.edu/): An annotation tool for Semantic Roles Labeling with Uniform Meaning Representation. ![commit](https://img.shields.io/github/last-commit/jinzhao3611/umr-annotation-tool/master)


- [**Termbox**](http://termbox.lingosail.com/): A term-extraction and translation tool for Computer-Aided Translation.

Selected Publication
=======
## paper

Ning Cheng, Bin Li, Liming Xiao, Changwei Xu, **Sijia Ge**, Xingyue Hao, Minxuan Feng. Integration of Automatic Sentence Segmentation and Lexical Analysis of Ancient Chinese based on BiLSTM-CRF Model. *Proceedings of LT4HALA 2020 - 1st Workshop on Language Technologies for Historical and Ancient Languages*. Marseille, France,2020:52-58. [[pdf]](https://aclanthology.org/2020.lt4hala-1.8.pdf) 

*****  

Xingyue Hao, **Sijia Ge***, Yang Zhang, Yuling Dai, Peiyi Yan, and Bin Li. The Construction and Analysis of Annotated Imagery Corpus of Three Hundred Tang Poems. *J.-F. Hong et al. (Eds.): Proceedings of the 20th Chinese Lexical Semantics Workshop (CLSW 2019)*, LNAI 11831, pp. 517–524, 2020.   [[pdf]](https://link.springer.com/content/pdf/10.1007%2F978-3-030-38189-9_53.pdf)
  
******  
Li  Song, Yuan  Wen,  **Sijia  Ge**,  Bin  Li,  Junsheng  Zhou,  Weiguang  Qu  and  Nianwen  Xue. An  Easier  and  Efficient Framework to Annotate Semantic Roles: Evidence from the Chinese AMR Corpus.*The 13th Workshop on Asian Language Resources on LREC 2018*. Miyazaki, Japan, May 07, 2018:29-35.   [[pdf]](http://lrec-conf.org/workshops/lrec2018/W29/pdf/15_W29.pdf)
  
  
## patent 
A  Method  and  System  of  Automatic  Lexical  Analysis  for  Ancient  Chinese.  (the  3 rd   applicant).2019. No.CN201910085019.3 


<br>Code projects on Github
=======
## Natural Language Processing 

- Text classification with XLNET, logistic regression, BI-LSTM/SVM with embeddings. The data including a hotel reviews and SemEval shared task 4 for 'Don't Petronize Me' detection. The implementation with pytorch, keras, tensorflow, sklearn.
[[repo]](https://github.com/Konic-NLP/text-classification)


- Name Entity Recognition with token-based tagging(BIO/BIOE)
  - NER with BERT, which loaded the pre-trained model from huggingface[[repo]](https://github.com/Konic-NLP/BERT-NER/blob/main/copy_of_ner_bert.py)
  - BI-LSTM implementation with tensorflow, can choose BI-LSTM or IDCNN as the model architecture, IDCNN is faster. [[repo]](https://github.com/Konic-NLP/NER/blob/main/NER-BERT.py)
  - CRF++(C++ source)/CRFsuite implementation, the feature template can be edited by the users. [[repo]](https://github.com/Konic-NLP/NER) 

***********
## Machine Learning
- Course Project: The bigger, the better? [[Poster]](https://konic-nlp.github.io/files/final_poster_5622.pdf)
  - compare the performance of image classification task on CIFAR-19 dataset between a vanilla CNN and a CNN including ResNet-50 pretrained models.
  - The experiments show that after preprocessing like Deep-Image-Prior(DIP) on the nosiy data, the perfomance on a vanilla CNN can perform in the similar level to that on a complicated CNN leveraging ResNet-50 without denosing. The vanilla CNN trains faster, less weights.
  - Also find variables such as optimizer, upsampling impact differently on different CNN.   
- Kaggle competition: Bike shared count[[Kaggle page]](https://www.kaggle.com/competitions/csci-5622-ps4-22-fall/overview) [[Code Link]]()
  - leverage Exploratory Data Analysis, feature engineering for handling data format features, feature transformation&normalization, and XGBoost with Parameter Gridsearch
  - Rank #3/52 in Public leaderboard with R^2=0.935 and #9/52 in Private Leaderboard with R^2=0.939

***********
## Computer Vision

- MNIST recognition with scikit-learn [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment1_.ipynb)
- Cifar-10 image classification with Keras(using regularization L2/Batch Normilization/Drop out) [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment2.ipynb)
- Viz-Wiz challenge: VQA for blind people, extracting questions and image features via BERT and VGG-16, then feed the flatten feature vector into a MLP. [code](https://github.com/Konic-NLP/5922-deep-learning/blob/main/lab_assignment4.ipynb)

**************

## Software Development and Object-Oriented Design

- A music store simulation, including the functionality like placing an order, checking the inventory, sell the items, buying items and so on. Injecting design patterns into the code, including factory, strategy, decorator, command, observer, singleton. Design with class UML, state diagram and sequence diagram. The language we use Java.[repo](https://github.com/Konic-NLP/OOAD-project)

- A online e-commerce shopping website development. Implementing with Django 2,  we use JS and Jquery for front end and Django-admin for backstage management.[repo](https://github.com/Konic-NLP/final-project-OOAD)


****************

## Coding Practice 

- Python Data sturcture and Algorithms.[repo](https://github.com/Konic-NLP/Data_sturcture_algorithms)  ![update](https://img.shields.io/github/last-commit/Konic-nlp/Data_sturcture_algorithms/main?label=last%20update&style=plastic)

- Java Learning with UCB CS 61B. [repo](https://github.com/Konic-NLP/Java-learning)
- Machine Learning(implemented with *Machine Learning in Action*).[repo](https://github.com/Konic-NLP/Machine_Learning) 




<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html). -->
