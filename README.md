# Disaster Tweets
Natural Language Processing with Disaster Tweets using BERT

## Introduction (Copied from Kaggle)
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:
<p align="center">
  <img width="200" height="400" src=images/tweet.png>
</p>
The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

## Hardware
GPU is preferred

Free GPU can be used through Google Colab, by changing runtime type to GPU

## Dataset
Dataset can be found from https://www.kaggle.com/competitions/nlp-getting-started/data

This dataset was created by the company figure-eight and originally shared on their [‘Data For Everyone’ website here](https://appen.com/pre-labeled-datasets/)

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

## Architecture of Neural Network
<p align="center">
  <img width="460" height="700" src=images/model_layout.PNG>
</p>

## Result
The model was ranked 33th out of a total of 812
teams participating in the Twitter Disaster contest in these
two months
<p align="center">
  <img width="460" height="70" src=images/leaderboard.png>
</p>

<p align="center">
  <img width="460" height="300" src=images/matrix.PNG>
</p>

## Reference
Kaggle. Natural Language Processing with Dis- aster Tweets. Retrieved April 01, 2022 from https://www.kaggle.com/c/nlp-getting-started.

Devlin, J.; Chang, M.-W.; Lee, K.; and Toutanova, K. 2018. Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805

Mikolov, T., Chen, K., Corrado, G., and Dean, J. (2013a). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781

Radford, A., Narasimhan, K., Salimans, T., Sutskever, I. (2018). Improving language understanding by generative pre-training (2018).

Chi Sun, Xipeng Qiu, Yige Xu, and Xuanjing Huang. 2020. How to Fine-Tune BERT for Text Classification? arXiv:1905.05583 (2019)
