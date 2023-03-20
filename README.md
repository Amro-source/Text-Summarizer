# Text-Summarizer
Python


There are different ways to build a software architecture for a Python text summarizer application. One way is to use an abstractive text summarization method that uses a deep learning model such as OpenAI’s GPT-3 to generate summaries that are not necessarily exact sentences from the original text1. Another way is to use an extractive text summarization method that identifies significant sentences from the original text and adds them to the summary2. You can also use existing Python packages such as spaCy, Gensim, or The Text API that provide text summarization functionalities3


A text summarizer application using extractive algorithm is a program that can create a short summary of a given text by selecting the most important sentences or phrases from the original document. The extractive algorithm does not generate any new words or sentences, but only extracts existing ones based on some criteria such as relevance, importance, or similarity. Some examples of extractive text summarization techniques are TextRank1, ROUGE2, and TF-IDF3.
![glasses-1052010_960_720](https://user-images.githubusercontent.com/68817735/226346467-27885eb0-d4c4-4538-97d2-a4cfc3384824.jpg)


The building blocks for extractive text summarizer application are:

A pre-trained model that can encode the input text and rank the sentences based on their importance. Some examples of such models are BERT12, DistilBART3, and Transformer4.
A pipeline that can preprocess the input text, pass it to the model, and postprocess the output summary. One example of such a pipeline is Hugging Face’s Pipeline API3 which can use any summarization model from their model hub.
A dataset that contains pairs of long texts and their summaries. Some examples of such datasets are CNN/DailyMail5, arXiv3, and Gigaword6.
An evaluation metric that can measure the quality of the summary by comparing it to a reference summary. Some examples of such metrics are ROUGE56, BLEU4, and METEOR4
