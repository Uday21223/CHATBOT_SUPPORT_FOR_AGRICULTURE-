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

Now for deployment follow my tutorial to implement `app.py` and `app.js`.


## Note
In the video we implement the first approach using jinja2 templates within our Flask app. Only slight modifications are needed to run the frontend separately. I put the final frontend code for a standalone frontend application in the [standalone-frontend](/standalone-frontend) folder.

## Credits:
This repo was used for the frontend code:
https://github.com/hitchcliff/front-end-chatjs
