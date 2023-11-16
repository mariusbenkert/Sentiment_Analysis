# Sentiment_Analysis

This repository contains code for training sentiment classifiers and is structured as follows:

```
| [root]
|── data
    |── training
    |── validation
|── models
    |── bayes_classifier
    |── distilbert_classifier
    |── distilbert_tokenizer
| bayes_classifier            -> Notebook used for creating the bayes classifier
| data_exploration            -> Notebook used for data exploration and gaining insights
| distilbert_classifier       -> Notebook used for creating the distilbert classifier
```

In summary, two different models were trained to predict the sentiment of tweets from twitter. While the bayes classifier provides a good baseline with $\approx 80$% accuracy, the transformer based distilbert model takes the lead with $\approx 95$% accuracy.