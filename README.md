# Project: Generative Chatbot

Apply deep-learning knowledge and chatbot to build an open-domain generative chatbot.

## Overview

Create a generative chatbot using a stream of tweets on a particular topic.

## Setting Up

### Installing Python 3

To run/write Python on your own computer, you’ll need to install Python 3. Follow the instructions in [this article](https://www.python.org/downloads/) to install Python 3 on your computer.

### Installing Tensorflow, Keras, and NumPy

1. Install TensorFlow, the deep learning backend for Keras.
2. Install the Keras API.
3. Install NumPy using either Anaconda/Miniconda or pip:


## Set Up The Code

Download and unzip the folder for this project. You should have the following files:
- `twitter_prep.py`
- `preprocessing.py`
- `training_model.py`
- `test_model.py`
- `chat.py`

Additionally, you should have three .txt files of Twitter data: `love.txt`, `cat.txt`, and `weather.txt`.

## Preprocessing

1. Open `twitter_prep.py` and `preprocessing.py` in a code editor or IDE.
2. In `twitter_prep.py`, change `data_path` to the file path of `[your-topic].txt`.
3. At the bottom of `twitter_prep.py`, print out all the response pairs from the data to see the format they are in.
4. In `preprocessing.py`, adjust the number of lines of training data you want to work with.
5. Run `preprocessing.py` and make sure everything works error-free.

## Training

1. Open `training_model.py`.
2. Change the values for `batch_size` and `epochs` as per your preference.
3. Run the code to generate your model. You'll see a summary of the model printed out.
4. You'll also see a new file called `training_model.h5` in the directory. This is where your seq2seq training model is saved.

## The Chatbot

1. Open `test_model.py` and `chat.py`.
2. In `chat.py`, create a `ChatBot` class with methods as described in the project guidelines.
3. At the end of `chat.py`, test out the chatbot by instantiating a `ChatBot` object and calling `.start_chat()` on it.

