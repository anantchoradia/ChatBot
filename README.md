# Chatbot
The repository contains code for implimentaion of a chatbot using **Recurrent Neural Network** with the help of **Attention Mechanism** to imporve accuracy of the bot

## Contents
- [Introduction](#introduction)
- [Prerequesites](#prerequesites)
- [Installation Steps](#installation-steps)
- [Data Used](#data-used)
- [Model Training](#model-training)
- [Chat with Bot](#chat-with-bot)
- [Current Status](#current-status)
- [Future Prospects](#future-prospects)

## Introduction
Natural Language Processing is one of the most upcoming sectors of machine learning because of its innate connectivity with human use. So many times has there been a need for language translation that it is has been a pinch-point for a long time. Now, using one of the most modern forms of machine learning researchers have tried to resolve this problem.



### Prerequesites

This project to apply the skills I learnt while working on the course [Deep Learning for Natural Language Processing](http://web.stanford.edu/class/cs224n/) taught by Stanford Professors, Christopher Manning and Richard Socher. I suggest you go through this course in order to understand about Bi-directional Recurrent Neural Networks, Embeddings and Attention Mechanism in Seq2Seq models.

## Installation Steps
To use the chatbot that is created by this repository you need to have [Python 3.5](https://docs.python.org/3.5/) or higher verisons and some other Python Packages also need to be added. It is suggested to create a [virtual environment](https://docs.python.org/3/tutorial/venv.html) so that it does not interfere with your other systems. Run the following commands to start the installation
```
cd path/to/your/folder
git clone https://github.com/anantchoradia/Chatbot.git
cd Chatbot
virtualenv -p python3.5 venv
source venv/bin/activate
pip install -r requirements.txt
```

Now you are ready to work with the Chatbot.

## Data Used
The data that was used to train the chatbot was taken from  [Cornell Movie Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html). Download the data from this [link](http://www.cs.cornell.edu/~cristian/data/cornell_movie_dialogs_corpus.zip) and extract **movie_conversations.txt** and **movie_lines.txt** to ./data folder. Other files in this zip folder are optional and please read through them to understand more about the data.

## Model Training

## Chat with Bot

## Current Status

## Further Steps
