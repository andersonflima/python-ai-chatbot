# Python IA chatbot

This is a chatbot made in python that, using the information provided in the intents.json file, can interact with a user

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
python  ^3.8
numpy  ^1.19.4
nltk  ^3.5
tensorflow ^2.4.0
Poetry 1.1.4
pip 20.0.2
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

You can install the dependences with pip 

```
pip install -r requirements.txt
```

or you can use poetry

```
poetry install
```

## Run

To run the chatbot first, you need to generate the files needed to do this, you must run "training.py" first

'' '
python traning.py
'' '

This command will generate files of 3 (three) words.pkl, classes.pkl and chatbot_model.h5
After that, you can run "chatbot.py"

'' '
python chatbot.py
'' '

This command will start the chatbot after execution, you just need to type a few words to speak to the AI

The words must be in the intents.json file.
Make sure to add more if you want 


## Authors

* **Anderson F lima**

## Acknowledgments

* This code is for self-improvement only

