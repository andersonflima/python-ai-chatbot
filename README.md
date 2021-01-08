# Python AI chatbot

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
python  ^3.8
numpy  ^1.19.4
nltk  ^3.5
tensorflow ^2.4.0
Poetry 1.1.4
pip 20.0.2
```

# Description
This is a chatbot made in python that, using the information provided in the intents.json file, can interact with a user

The words must be in the intents.json file.
Make sure to add more if you want 

### Installing

```
python -m poetry install
```
This command will generate a virtual env for this project

## Run

To run the chatbot first, you need to generate the files needed to do this, you must run "training.py" first

```
poetry run python traning.py
```

This command will generate files of 3 (three) words.pkl, classes.pkl and chatbot_model.h5
After that, you can run "chatbot.py"

```
poetry run python chatbot.py
```

This command will start the chatbot after execution, you just need to type a few words to speak to the AI

## Authors

* **Anderson F lima**

## Acknowledgments

* This code is for self-improvement only

