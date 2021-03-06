<!-- ---
layout: Post
date: 2021-08-15 17:01
title:  "Project"
mood: neutral
category: 
- docs
--- -->

---
layout: page
title:  "Portfolio"
permalink: "/portfolio/"
---
### 1. Smart Learning: student engagement prediction based student emotions and their eye gazes.
*My currently project as research assistant in Research Center for Computing and Multimedia Studies, Hosei University.*

The project aim to develope a system that predict student engagement in online classes by analyzing their emotions and their eye gazes. It was building by 3 member-team. My role is using deep learning and machine learning technique to build the face recognation for identifying student ID in class. I process and analyze the after class dataset resulting in clearly explained to stake holder.

<figure class="alignleft">
	<img width="1166" height="250" src="https://github.com/ThuyTTT96/ThuyTTT96.github.io/blob/main/images/StudentEL.png?raw=true">
</figure>

***If you are interested in this work, please find the code <a href = "https://github.com/ThuyTTT96/Engagement_Detection_Framework"
title = "Title">here.</a>***

### 2. NLP data prediction models
### In this project, I apply machine learning techniques to amazon's customer review dataset to classifier whether their reviews is positive or negative.
The observation is each row in the review of amazon's customer and is not labeled yet.
 - Data cleansing:
The *bag of words* technique and *count vectorize* are applied to tokenlize the text and stop the useless words in **review** observation.
The class of each observation is defined by the corresponding score (from 1 to 5). The lower scores are labled at 0, the higher scores are labels at 1, the neutral one are deleted from the dataset.
- Prediction model and training process:
I use the sklearn model to slip the data set in to 70% for training and 30% for testing and the TF-IDF to extract the feature from the text.
The logistic regression models are applied to classifier the customer's review to 2 classes: 0 - not helpful and 1 - helpful.
The result shows that logistic regression can reach 9x.xx% accuracy in this data set
<figure class="aligncenter">
	<img style="width:1166px; height:250px;" src="https://raw.githubusercontent.com/ThuyTTT96/ThuyTTT96.github.io/350993dc6e9e692f2d82af2a489042be04b16604/images/download.svg" />
	<figcaption class="aligncenter"> </figcaption>
</figure>

### 3. Deep Learning and Computer vision

#### 3.1.  People search in surveillance camera network

*This project is the capstone project for the Bachelor of Computer Science at the University of Information Technology, Vietnam National University
The project was built in 6 months by me and my partner under the supervisor's guides.*

This project aims to retrieve people in the school camera system by applying deep learning and machine learning to image/video processing. MTCNN, KNN, CNN, Darknet Yolo were applied for face detection, face clustering, people attribute detection and pedestrian detection consequently in this project.

<iframe width="1166" height="656" src="https://www.youtube.com/embed/Ko8M0Uao6FE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### 3.2. Image style transfer

In this project, I use vgg19 pretrained model to extract some of the layers in this network to define the representation of content and style from the image. 
After the content and style features are extracted, those features are trained in VGG Network by using torch library 

<figure class="aligncenter">
	<img src="https://github.com/ThuyTTT96/ThuyTTT96.github.io/blob/main/images/stytransfer.png?raw=true" />
	<figcaption class="aligncenter"> </figcaption>
</figure>
