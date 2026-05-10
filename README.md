# IndoBERT on NLP (case on my competition multiclass classification)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)

This project focuses on using IndoBERT for opinion classification on an Indonesian-language tweet dataset divided into 8 topics.

The dataset used comes from one of the competitions I participated in.

The experiments include EDA, text preprocessing (including augmentation and resampling), and comparisons across several models such as IndoTweet, Multilingual-BERT, IndoBERT (base/large), and other BERT-based models.

The results are still not very satisfying. Possible reasons are that the dataset size is not large enough for BERT models, and the preprocessing pipeline can still be improved.
