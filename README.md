# Transfer learning using Google's Inception v3
 
Deep learning models have enjoyed a recent resurgence in both academia and industry and have achieved outstanding performance results. These models, which can contain millions of parameters, require enormous datasets to train on. The idea of *feature transferability* or *transfer learning* involves recycling a model trained on one task to achieve good performance on another task, which may have a more limited training data set that would otherwise ensure non-satisfactory performance. 

This project explores how well features extracted from various depths of Google's [Inception v3](http://arxiv.org/abs/1512.00567) deep learning model, trained on the 2012 ImageNet dataset, generalize to different tasks. The novel tasks we selected range from being very similar to that which the model was trained on, such as identifying hand-written digits, to very different, such as identifying what emotions an image is likely to evoke in a viewer.

This project was submitted as part of a *Deep Learning for Pattern Recognition* class taught by Professor Paul Gader during winter quarter at the University of California, Santa Barbara.
