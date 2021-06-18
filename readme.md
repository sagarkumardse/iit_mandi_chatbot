## Idea
Every year, a new batch of enthusiastic students join college. These students are now very excited to team up in college and be a part of the campus as soon as possible. Every student has doubts, what to bring, how's the campus, etc. Now, considering the average strength of a batch to be 100+, there for sure is going to be redundancy in questions asked. So to answer their basic queries, we created a chatbot that answers such basic queries.

## Overview
A deep learning sequentail model is used for training the model. The data used in intents.json file has a defined structure on which we train our Sequential model. In training phase, first step was the open and read the dataset, then using tokenizer, we are seprating each word which finally gives us a set of words(set i.e. no defined pattern, words doesn't really make any sense here), finally in training phase, model learns how to map the given patterns to particular 'tags' given in the dataset. 
Now when we ask any query, the model try n find the tag related to it, then randomly choose the answer belonging to that perticular tag.

## Where to find the actual running version?
Just to telegram and search "__Gideon__", inspired by Flash's interactive AI consciousness. 
## Sample Respones of Bot to different queries
<img src="Screenshot from 2021-06-18 14-14-03.png" alt="chat"  />
<img src="Screenshot from 2021-06-18 14-14-18.png" alt="chat" />


Note : This bot is designed specially for 1st yearites joining IIT Mandi.
