# AI semi-intelligent chat bot
## Instructions
The bot is already trained with basic data, such as answering simple questions such as it's name "Nucleus" and pretend to be a small shop bot that sells merchendise.  

To run, simply run the Chat-bot python file from command line, and have a conversation!  
Please view the preview images for more details.

Currently, only trained attributes include  
* Greeting
* Introduction
* Salutations
* Information about opening hours
* Information regarding merchandise  
To change the bot to accustom to your needs, you may edit the intents.json file that consists of well, intentions.  

# Required libraries
* nltk
* tensorflow
* numpy
* pickle
* json
* random

# How does it work?

The program uses lemmatisation and groups the words you speak to it into groups and then compares those words with its training data and answers back with the class where those words appear the most.
For example, the word "what" appears most often in the class "Prodcut information" as when referring to an object people are more likely to use the word "What".

# Preview
![img](https://github.com/ali207715/AI-Chat-bot/blob/main/1.PNG?raw=true)

