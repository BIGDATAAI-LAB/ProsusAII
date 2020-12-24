---
language: "en"
tags:
- financial sentiment analysis
- sentiment analysis
widget:
- text: "Stocks rallied and the British pound gained on Thursday as Britain and the European Union closed in on a free trade deal and investors wagered on a global economic recovery."
---

FinBERT is a pre-trained NLP model to analyze sentiment of financial text. It is built by further training the BERT language model in the finance domain, using a large financial corpus and thereby fine-tuning it for financial sentiment classification. For the details, please see [FinBERT: Financial Sentiment Analysis with Pre-trained Language Models](https://arxiv.org/abs/1908.10063).

The model will give softmax outputs for three labels: positive, negative or neutral.