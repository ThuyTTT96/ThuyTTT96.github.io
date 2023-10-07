---
layout: page
title:  "Portfolio Projects"
permalink: "/portfolio/"
---

### 1. NLP data prediction models
***If you are interested in this work, please find the code <a href = "https://github.com/ThuyTTT96/Data-Prediction-Models-and-NLP"
title = "Title">here.</a>***
<figure class="aligncenter">
	<img style="width:1166px; height:250px;" src="https://raw.githubusercontent.com/ThuyTTT96/ThuyTTT96.github.io/350993dc6e9e692f2d82af2a489042be04b16604/images/download.svg" />
	<figcaption class="aligncenter"> </figcaption>
</figure>
In this project, I apply machine learning techniques to amazon's customer review dataset to classifier whether their reviews are positive or negative.
The observation is each row in the review of amazon's customer and is not labeled yet.
 - Data cleansing:
The *bag of words* technique and *count vectorize* are applied to tokenize the text and stop the useless words in **review** observation.
The class of each observation is defined by the corresponding score (from 1 to 5). The lower scores are labeled at 0; the higher scores are labels at 1, the neutral ones are deleted from the dataset.
- Prediction model and training process:
I use the Scikit-learn model to slip the data set into 70% for training and 30% for testing and the TF-IDF to extract the feature from the text.
The logistic regression models are applied to classifiers the customer's review into two classes: 0 - not helpful and 1 - helpful.
The result shows that logistic regression can reach 9x.xx% accuracy in this data set.


### 2. Deep Learning and Computer vision

#### 2.1.  People search in surveillance camera network

<iframe width="1166" height="656" src="https://www.youtube.com/embed/Ko8M0Uao6FE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 

*This project is the capstone project for the Bachelor of Computer Science at the University of Information Technology, Vietnam National University
The project was built in 6 months by my partner and me under the supervisor's guides.*

This project aims to retrieve people in the school camera system by applying deep learning and machine learning to image/video processing. MTCNN, KNN, CNN, Yolo were applied for face detection, face clustering, people, attribute detection, and pedestrian detection consequently in this project.



#### 2.2. Image style transfer
***If you are interested in this work, please find the code <a href = "https://github.com/ThuyTTT96/Deep-Learning-Models"
title = "Title">here.</a>***
<figure class="aligncenter">
	<img src="https://github.com/ThuyTTT96/ThuyTTT96.github.io/blob/main/images/stytransfer.png?raw=true" />
	<figcaption class="aligncenter"> </figcaption>
</figure>
In this project, I use the vgg19 pretrained model to extract some of the layers in this network to define the representation of content and style from the image. 
After the content and style features are extracted, those features are trained in VGG Network by using the torch library



#### 2.3. Face recognition

***If you are interested in this work, please find the code <a href = "https://github.com/ThuyTTT96/Deep-Learning-Models/tree/main/facialrecognition"
title = "Title">here.</a>***  

<figure class="alignleft">
	<img src="https://github.com/ThuyTTT96/Deep-Learning-Models/blob/main/facialrecognition/imageBasic/result2.png?raw=true" />
	<figcaption class="aligncenter"> </figcaption>
</figure> 
In this project, I did real-time face recognition with only one image required in the database for each person.
The model can detect and locate the face and embed the located face done with OpenCV libraries. It provides the pre-trained model used to generate 128 measurements for each input face. The network generates nearly the same numbers when looking at two different pictures of the same person else it generates different numbers when there are two different pictures of a different person.


