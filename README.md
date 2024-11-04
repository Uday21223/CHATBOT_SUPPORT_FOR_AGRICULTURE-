# Chatbot Support For Agriculture 
<img src="https://www.lifeofautomation.com/wp-content/uploads/2020/05/adobestock_194734459-1-2048x1365.jpeg" id="img" width="100%" height="auto">

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




