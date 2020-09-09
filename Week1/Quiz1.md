# Machine Learning - Week 1 - Quiz 1 :
##### Github Repo for course: [Stanford Machine Learning (Coursera)](https://github.com/anigaundar/Coursera-Machine-Learning-Andrew-Ng)

Question 1
-------
A computer program is said to learm from experience **E** with respect to some task **T** and some performance measure **P** of its performance on **T**, as measured by **P**, improves with experiecne **E**.
Suppose we feed a learning algorithm a lot of historical weather dta, and have it learn to predict weather. What wuld be a reasonable chice for **P** ?

* The weather prediction task.
* The process of the algorithm examining a large amount of historical weather data.
* The probability of it correctly predicting a future date's weather.
* None of these.

Answer: <br/>
True/False | Statement | Explanation 
--- | --- | ---
False|The weather prediction task.| It is Task **T**
False|The process of the algorithm examining a large amount of historical weather data.| It is experience **E**.
True|The probability of it correctly predicting a future date's weather.| This can be obtained as an effect of **T** using **E**


Question 2 
-------
The amount of rain that falls in a day is usually measured in either millimeters(mm) or inches. Suppose you use a learning algorithm to predict how much rain will fall tomorrow.
Would you treat this as a classification or regression problem?
* Classification
* Regression

Answer:<br/>

Answer | Explanation
---|---
**Regression**| Here we are predicting amount of rainfall (based on the past data and weather parameters) so this is a Regression Problem. In classification we classify the data into distinct categories.
 
Quetion 3
------
Suppose you work on a stock market prediction. You would like to predict whether or not a certain company will declare bankruptcy within the next 7 days (by training on data of similar companies thathad been at risk of bankruptcy). Would you treat this as a classifiation or a regresion problem?

* Regression
* Clssification

Answer: <br/>
Answer | Explanation
---|---
**Classification**| Here we are taking the historical data of companies and based on that classified into categories - Bankrupt or not. so this is simply a classification problem.

Quetion 4
------
Some of the preoblems below are best addressed using a supervised learning algorithm, and others with an unsupervised learning algorithm. which of the following would you apply supervised lerning to? (select all that apply.) In each case, assume some appropriate data is availble for your algorithm to learn from.
* Given historical data of children's ages and heights, predict children's height as a function of their age.
* Take a collection of 1000 essays written on the US Economy, and find a way to automatically group these essays into a small number of groups of essays that are somehow "similar" ot "related".
* Given 50 articles written by male authors, and 50 articles written by female authors, learn to predict the gender of a new manuscript's author (when the identity of this author is unknown)
* Examine a lare collection of emails that are known to be spam email, to discover if there are sub-types of spam mail.

Answer: <br/>

True/False | Statement | Explanation 
--- | --- | ---
True |Given historical data of children's ages and heights, predict children's height as a function of their age.| In this prection of height is done based on the historical data of children's age and height. It is a labled data of afe and height .Clearly Supervised Learning.
False |Take a collection of 1000 essays written on the US Economy, and find a way to automatically group these essays into a small number of groups of essays that are somehow "similar" ot "related".| Here only a collection of essays is taken and asked to group them without providing any labels or samples of ways of grouping. clearly this Unsupervised Learning.
True| Given 50 articles written by male authors, and 50 articles written by female authors, learn to predict the gender of a new manuscript's author (when the identity of this author is unknown)| Here labled data of articles written by males and females is given. so based on this information we can find a way to predict the the article written by a male or female. So it is a Supervised Learning
False| Examine a lare collection of emails that are known to be spam email, to discover if there are sub-types of spam mail. | In this problem a large collection of spam emails is given and asked to discover if there are sub-types of spam mail without providing any criterion ( labeled data). So this is an Unsupervised Learning. 

Quetion 5
------
Which of htese is a reasonable definition of machine learning?
* Machine learning is the field of study that gives computer the ability to learn without being explicitly programmed.
* Machine learning is the field of allowing robot to act intelligently.
* Machine learning learns from labeled data.
* Machine learning is the science of programming computers.

Answer:<br/>

Answer | Explanation
---|---
Machine learning is the field of study that gives computer the ability to learn without being explicitly programmed.| self explanatory

