# Travel Chatbot on Slack

The purpose of this project is to build a simple chatbot where a user can request flight prices through conversation.

## Description
A speech intent classifier is trained by using NLP transfer learning - the Universal Language Model Fine-tuning (ULMFiT) method. I came across this approach when researching transfer learning in NLP applications since it already existed for image classification. In this work, ULMFiT was implemented by using fastai: https://docs.fast.ai/text.html. An impressive accuracy of 93% was achieved on the speech intent classifier considering my travel chat corpus has about 250 examples. The work is documented in the `chat_model.ipynb` notebook in this repo. It should be noted that the notebook was originally developed on Google Colab.


