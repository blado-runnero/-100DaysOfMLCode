# #100DaysOfMLCode

My attempt for #100DaysOfMLCode.

-----------------------------------


# Day 1:-

I made a charcter recognizer. One of the most exciting project of mine yet. 
This project set the new momentum in my journey. I aimed at making 10 projects, first one is completed in the first day itself. It feels so awesome.

# Learning from today:-

Always make preprocess your data. 

I trained the model and deployed all while my training data was LR and 90 rotated. So I trained again and it correctly classified images this time. 

Link for the same is: https://blado-runnero.github.io/char.html

-----------------------------------

# Day 2:-

Read few medium articles about NLP and why its still a hard problem to solve. ( Hint :- Beacuse of the multiple meaning of the same words, especially in other languages. See this link for more, if you are indian you can understand more easily, https://inshorts.com/en/news/abhi-na-jao-cd-kar-users-claim-song-censored-on-amazon-alexa-1543404865211 )

Took few courses from kaggle, 

1. Pandas (https://www.kaggle.com/learn/pandas)
2. Machine Learning (https://www.kaggle.com/learn/machine-learning)
3. Data Visualization (https://www.kaggle.com/learn/data-visualisation) [half of it, will comlete later]

# Learning from today:-

Since I never really used pandas all by myself, without googling for it, the day felt really productive. We can think of pandas as sql in python, the underlying concept is same. Everytime I was stuck in its exercise, the first thing I thought was, How would I achieve this in sql, and after few trials I would achieve it. But combined with syntax of python, it can be done more elegantly. 

I also learnt how to plot graphs, I can now plot graphs much easily. But for more advanced graph stuff, I would retake this course later. 

I also learned the concept of imputing today, for the first time. And best practice is to impute the whole column with an marker in the name, so that the algorithm can make educated guess by looking both the columns. 

-----------------------------------

# Day 3:-

Today was the day for 2 of the most important models, xgboost and random forests. These are the two of the most used models in any kaggle competitions; dominance is however, of xgboost. 

I didn't wrote a lot of code today, because most of the time was spent understanding these two models. After dedicating a solid 3 hours for this two models also I am yet to gain a solid understanding of these two (I will revisit this topic after few days, this time not by theory, but by a practical implementation, i.e. reading kaggle kernels ), so not much to learn today. 

# Learning from today:-

Ensemble models are great, they have dont useually overfit and if they do, you can easily tune model to overcome that.

# Project Ideas

While I was having a hard time understanding xgboost, so I decided to search for some projct ideas that I can make next. I encountered this two ideas.

1. Estimating the price of a mobile from a feature list. 

2. Face recognition mobile app, by using facenet architecture. (Sounds interesting)

-----------------------------------

# Day 4:-

Today was a light day in terms of ML coding. I worked on my website, yes, from few days from now, I will not be Anshuman Patel anymore, I will become anshumanpatel.in (It already feels so proud to say that my website will be hardcoded and not some wordpress or theme stuff)

Read few kernels from kaggle. Since I am new to kaggle, I am first analyzing the style of different people and analyzing how they approach the problem, and will develop my style seeing them. (Sounds random forest, right?)

# Learning from today:-

EDA is king. (That in itself is a thousand learnings combined.)

-----------------------------------

# Day 5:-

SVM's day. I implemented a SVM classifier today. The idea is that they try to separate the labels in different hyperplanes. ALtought I am familiar with SVM, but for the first time  I learnt about gamma, margin, regularization, kernels. 

Resources :- 
https://medium.com/machine-learning-101/chapter-2-svm-support-vector-machine-theory-f0812effc72
https://medium.com/machine-learning-101/chapter-2-svm-support-vector-machine-coding-edd8f1cf8f2d

# Learning from today:-

If I plot what I learnt today on a graph, the point that this point till be plotetd will totally be an outlier. 

I was charged some $10 for static IP I used in a project weeks ago by google cloud, since the project was completed, I deleted the whole project. So the lerning will be to always close all the projects/instances/everything used in online cloud services. 

-----------------------------------

# Day 6:-

Today I learnt about transfer learning. I made a custom model based on VGG16 architecture. 

The idea behind transfer learning is that you use a pretrained model, which in this case is VGG16, a winner of imagenet challenge 2014, and remove last few layers according to your needs, which in my case was just to add a dense layer with output of 2 neurons predicting cat or dogs. The pretrained network, since it has proven its ability to identify features from an image, hence can be used to classify our images, or any data in case without making a new architecture from scratch.

# Learning from today:-

Transfer learning not only saves training time, but also reduces development efforts, resources. 

As always, it took me 3 hours to figure out how to configure my data for feeding into the models input layer. [ But here is the best part, I can use todays experience of image conversion later also. Ohhhh wait, its it Transfer Learning in real life ? :-) ]
