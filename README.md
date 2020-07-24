# TwitterAirlineULMFiT
Twitter US Airline Sentiment Analysis Using ULMFiT

In this notebook, we perform sentiment analysis on [Twitter US airline data](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) using Universal Language Model Fine-tuning for Text Classification ([ULMFiT](https://arxiv.org/pdf/1801.06146.pdf)) and achieving a test accuracy of 84%. For our ULMFiT implementation, we use the [fastai library](https://nlp.fast.ai/category/classification.html) for preprocessing our data, fine-tuning a pretrained language model and building our sentiment classifier. The language model (LM) is an English model with an AWD-LSTM architecture pre-trained by fast.ai on [Wikitext-103](https://blog.einstein.ai/the-wikitext-long-term-dependency-language-modeling-dataset/). The structure of this notebook is as follows:

1. Set up environment
2. Preprocess airline data
3. Fine-tune pretrained LM
4. Build sentiment classifier
5. Predictions
