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

-----------------------------------

# Day 7:-

Today I completed kaggle's deep learning track. https://www.kaggle.com/learn/deep-learning

I also tried my hands on Embedding track, but I found it some difficulty in that, so dropped that for the day. Maybe 2,3 days.

Got a project idea, an chrome plugin for controlling youtube via hand gestures. Mainly next/play/pause etc. So took few pics for it of myself. I know it can be done, but exactly how to approach it, is unknown to me yet. I also thought to first make it locally, and not on the browser, since that will be slow. Tommorow I will implement tiny yolo on my machine and try to do that. 

-----------------------------------

# Day 8:-

Today I failed at what I initially tried to do, so I had a lot to learn today.

Today I extended the project idea from yesterday and got on a result that the problem is an classification one, and not an object detection. What I mean by above line is that, classification can solve it more easily than implementing YOLO.

I never went ahead from classifying digits and letters, and when I did that, I straightaway implemented VGG16, a heavy network(in comparison to what I was trying to do, running on a browser through tensorflow JS). So I assumed that I can achieve the same by using mobilenet. And I took my pics and tried to classify the same through mobilenet. It was bad, like really bad. 

The max accuracy I obtained by mobilenet is 32.XX% (in 400 epochs). So for reference I ran the same images as input in VGG16, and in 15 epochs I was able to get 90+% accuracy. 

# Learning from today:-

Now I get why there are not so many AI apps that run live(on browser). Because its not easy to process millions of calculation at a given time, and that too on browsers. Its easy to do it into a backend where we can theoritically have unlimited processing power. But with advancement of technology(especially hardware), it will happen in next 3,4 years, we will have more on browser AI apps than now.

-----------------------------------

# Day 9:-

Today was the day of theorotical learning. 

I am not much familiar with NLP, so I thought to learn basic concepts behind NLP. My field of interest is Computer Vision, but I think I should also know basics of NLP, the most used ML technique ever. If you, by any chance, find this resource by a google search, its NLP in action. Basically anything that has words to do with it, its probably NLP. Like, "Alexa whats the weather now?", the first step is ofcourse converting the speech to text, but after that, understanding whats the meaning of this, both are an example of NLP.

I got an awesome resource I can refer to(thanks to the person who refered me this resource). 

https://www.stitcher.com/podcast/ocdevel/machine-learning-guide

This is a resource I would refer to, when they would say, tell me a resource which is exciting and no distractions. Its an audio resource(podcast), so if you want to like jog and still be connected to ML, this is the one.

-----------------------------------

# Day 10 & 11:-

I implemented an LSTM based RCNN model for sentiment analysis built on top of classical imdb movie review database.

I also tried to implement a text generation model, just like https://github.com/mtobeiyf/keras-flask-deploy-webapp. But didn't got any ideas so as to make it some kind of unique. I also explored the possibilities of implementing the same in different languages, like hindi. Read few articles for that also.

# Project Ideas

I got an rather interesting idea of an AI automated youtube live stream. Searched some resources for that and came to a conclusion that this is a very big project and would take lots of work. Kind of, side project once I get a job. It will take a lot of combination of models and lot of which will be NLP, which I currently know very little about.

Nice idea, but not achievable at this point. 

-----------------------------------

# Day 12:-

Today I worked on model deployment issue.

I always wanted to know how to deploy a model, but I somehow skipped it just by seeing terms like docker, flask, etc. But after committing that I will write an article on how to deploy, yesterday, somehow today I tried it, and after several attempts and 3 hours of efforts, I failed at it.  

Now I am continuously serching for a good article and following every steps, and when I will achieve that, I will write a simple step by step guide to deploy.

-----------------------------------

# Day 13:-

Having failed at building a pipeline to deploy the DL model using docker. Today I wrote an article on how to deploy small ml/dl models serverlessly using TFJS. Working on where to publish it.

Today I also gave an test for NLP engineer at vahan. It was quite tough, and also out of syllabus according to my current skillset(I am more like a computer vision engineer than nlp engineer). Also it made a point to revise some basic concepts like bias, variance, precision, recall. That test was only of 15 questions, but tested the indeapth knowledge for any NLP engineer. I might not crack this test, but it gave me a good learning topics for the next day. 


-----------------------------------

# Day 14:-

Today I intended to have a hands on experience with semantic segmentation architecture. Upon reading several articles it became clear that UNet is a clear winner in this category. So after going through several articles about that, I decided to have a look at a video explaination, the first video sugegstion from youtube was from a very famous instituation, fastai. 

Now, I knew that fastai's course is a good resource, the only fact that they use their own library stopped me from taking their course. But today 2 things changed my perspective. First, it says "Practical Deep Learning For Coders" and when read about the review, it seemed that its a right claim, and I actuyally hate math(until I know where and why exactly its used), so this seemed the perfect course for me. Second reason that forced me to literally take this course was, the founder, Jeremy Howard is a kaggle winner for 2 years(I tried to find the source but didnt find) and definitely I can have something from him. There are 14 lectures, I completed 1st one today, 13 more are left, I expect to complete all in next 10 days. 

Regarding UNet, if you want to learn about how to optimize it, have a look at this link, its a real time competiotion winner's experience and definitely more to learn from this very personal experience. https://towardsdatascience.com/image-segmentation-kaggle-experience-9a41cb8924f0

-----------------------------------

# Day 15 - 20 :-

I've completed 5 lectures of fastai. The course has much more to offer than I thought. Since Jeremy is a machine learning practitioner, it gives a much more deapth for me as an aspiring machine learning engineer. Like cyclic lerning rate, and why it works, and why we should use it. At first I thought that I would complete the whole course in 7 days, but I was wrong, the course, seeing its notes, reading articles all these activities are taking so much time that its better to slow a bit and understand it fully and then proceed to next lecture. 

In these days, I also gave the first round of 3 internships, all assignments. And I failed to even manage to complete two of these. One dealt with time series predictions, I have never encountered this problem before, so most of the allotted time was gone in grabbing the knowledge about the same, after failing in this I now know how hard is for trading/algorithmic trading predictions. Its much more complex, and nobody can predict it exactly, while going through some code examples, I saw them extracting and using google news feed and oberving its effects on prices and I never expected that to be of any use(I am not into trading in any means), but somehow it worked and somehow this is the new feature engineering, such creative job this is, I just hope I would somehow learn all these in few years.

I also got to know a new course on coursera about Serverless Machine Learning with Tensorflow on Google Cloud Platform, this is a new addition to my learning section, again thanks to Daniel Bourke(If you are reading it in medium seriess, this series is also inspired from his series, https://medium.com/series/bf23b507fc77 , dont sue me for copying you idea man[ofcourse, I am kidding {but I also fear, cause I can't afford my legal fees :-D}]).
