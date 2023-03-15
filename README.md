# Chatbot Deployment with Flask and JavaScript

- followed a turotial at `(https://github.com/python-engineer/pytorch-chatbot)` 
- it was implemented with Flask and JavaScript.

Deployment options:
- Deploy within Flask app with jinja2 template


## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
To make a virtual-environment : python -m venv <env-name>

To activate : Scripts/activate.bat

To deactivate: Scripts/deactivate.bat

To delete : simply delete the folder
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```


