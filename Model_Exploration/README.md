As my current capstone is intended towards sentimental analysis from Reddit data, I have explored the current research and models for sentimental analysis and NLP. 
For these areas, I have explored the below models:
BERT
ChatGPT

BERT(Bidirectional Encoder Representations from Transformers):
Most of the recent literature for sentimental analysis has been using BERT. Google’s BERT model is a DL transformer language model that has been pretrained on English Language Wikipedia. 
One main difference from the original transformer model is that BERT does contextual encoding in both forward and reverse directions in a text(hence bi-directional).

For Bert Model, I used the below Bert based models through the transformers package from HuggingFace to see how they perform on sample data from Reddit:

Distilbert-base-uncased.
Roberta
Berttweet-base model

Each model above had a different classification accuracy with ‘distilbert-base-uncased’ having the best accuracy.

ChatGPT:
ChatGPT is a large language chat model from OpenAI. I tried to use ChatGPT to see if it can do sentimental analysis for the data. 
But, the model is mainly a chat model and provides instructions on how to do sentimental analysis. THe model on its own can't be trained to perform tasks like text prediction or sentimental analysis. 
From chatting about the sentimental analysis, it provided very accurate answers on how to proceed with sentimental analysis.
