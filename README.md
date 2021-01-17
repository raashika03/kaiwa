# kaiwa
Chatbot to answer queries for future freshers of IIT Mandi
## Team Members:
Shruti Jain(B20136)\
B Keerthi(B18049)\
CHVSN Medha(B18051)\
Rashika Rathi(B18081)

Watch the project video by clicking at the link:
[Video](https://youtu.be/Ji2Y1yxRPLE)

## Prerequisites
we used some modules which you can download using the python-pip command.\
pip install tensorflow, keras, pickle, nltk

## Instructions for setup and running the chatbot
To run the chatbot, we have two main files: 
1. train_chatbot.py, and 
2. bot.py

First, we train the model using the command in the terminal:\
python train_chatbot.py

If we don’t see any error during training, we have successfully created the model. Then to run it, we run the second file.\
python bot.py

### The Dataset
The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

### File structure and the type of files we created:
Intents.json – The data file which has predefined patterns and responses.\
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.\
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.\
Classes.pkl – The classes pickle file contains the list of categories.\
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.\
bot.py – This is the Python script in which we implemented our telegram chatbot. Users can easily interact with the bot.

Features: It covers almost all the domains extensively which can be asked by a fresher willing to join IIT Mandi.


