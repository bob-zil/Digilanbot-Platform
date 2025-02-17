# Telegram Chatbot for Digital Transformation in Cambodia

This is a production-ready Telegram chatbot built using PyTorch and BERT/mBERT. It assists users with digital transformation and banking-related queries in Cambodia.

## Features
- Intent classification (greeting, banking, out-of-domain).
- Banking-specific question answering.
- Dynamic greetings.
- 3 model to integreted in telegram bot.

## Clearify
1. In data folder are stored all of dataset include greeting data , banking data , and out of field dataset to train intents classification model and we have faqs dataset to trining Banking Question-Answer also. More over we have QA_greeting that contain 2 column as well like question and answer. 
--> for the finals_data in here is the concat of greeting , banking and out of domain.

2. In each dataset in intents classification there are 2 column . The first one is text and second one is intents.

3. In QA_banking there are 2 column as well. The first one is Question and the second one is Answer.

4. In notebook folder include 5 notebook. About EDA is Exploratary Data Analysis that created to explore , understanding and combine data and play around to got the lastest version of dataset to store in data folder. And 3 more notebook such as faqs_training, greeting_training , and intents_classifier is using to train model . And the last 1 is integreted to integreted 3 model into telegram bot.

5. We use Pytorch framwork and we implement with mBERT/BERT architecture to built these 3 model .


## How to train
1. go to EDA.ipynb to see and explore about dataset. Make sure it is the right directory and right name of dataset.
2. When all of dataset is stay on the right place we can go to greeting_training.ipynb to train dynamic greeting respond.
3. Then we can go through to intents_classifier.ipynb to train intents model.
4. After that we go to faqs_training to train Questions-Answers dataset.
(Make sure 2,3,4 is load the right dataset) 
5. After we have already had all these model we can run integreted.ipynb to launch the bot . that's it !!

***Noted***

(Make sure if you change dataset, the dataset should be corrected as these structure like column , format or flow to train) !!!