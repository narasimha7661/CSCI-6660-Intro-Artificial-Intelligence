# Building a Simple Chatbot from Scratch in Python (using NLTK)(Model2)

This model contains:

Chatbot Model 2.ipynb - A Interactive Notebook version of ChatBot

chatbot.txt - Explores requirements to run the project
Reading in the corpus
For our example,we will be using the Wikipedia page for chatbots as our corpus. Copy the contents from the page and place it in a text file named ‘chatbot.txt’. However, you can use any corpus of your choice.


## BlogPost
For detailed overview, here is the accompanying blog titled:**[Building a Simple Chatbot in Python (using NLTK)](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)**


## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run

To run this application you can use jupyter notebook and open this file with jupyter notebook. Execute each cell to see the final result.
