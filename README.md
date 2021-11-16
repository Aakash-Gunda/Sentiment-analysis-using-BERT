# Sentiment-analysis-using-BERT

BERT stands for Bidirectional Encoder Representations from Transformers and it is a state-of-the-art machine learning model used for NLP tasks. We can easily load a pre-trained BERT from the Transformers library. But, make sure you install it since it is not pre-installed in the Google Colab notebook.Now that we covered the basics of BERT and Hugging Face, we can dive into this repo. We will do the following operations to train a sentiment analysis model:
1. Install Transformers library
2. Load the BERT Classifier and Tokenizer alıng with Input modules;
3. Download the IMDB Reviews Data and create a processed dataset (this will take several operations;
4. Configure the Loaded BERT model and Train for Fine-tuning
5. Make Predictions with the Fine-tuned Model

Dataset: IMDB Reviews Dataset is a large movie review dataset collected and prepared by Andrew L. Maas from the popular movie rating service, IMDB. The IMDB Reviews dataset is used for binary sentiment classification, whether a review is positive or negative. It contains 25,000 movie reviews for training and 25,000 for testing. All these 50,000 reviews are labeled data that may be used for supervised deep learning. Besides, there is an additional 50,000 unlabeled reviews that we will not use in this case study. In this case study, we will only use the training dataset.

A successful transformers network with a pre-trained BERT model and achieved ~97% accuracy on the sentiment analysis of the IMDB reviews dataset for just 5 epochs.
