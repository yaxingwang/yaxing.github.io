---
title: "Federated Learning (Cambridge machine learning reading group)"
collection: talks
type: "Talk"
permalink: /talks/2020-03-11-mlg-reading-group-federated-learning
venue: "Cambridge University Engineering Department"
date: 2020-03-11
location: "Cambridge, UK"
---

With [Siddharth Swaroop](https://siddharthswaroop.github.io/). [Slides](https://talayCh.github.io/files/talks/2020_mlgrcc_fl.pdf).

The goal of federated learning is to perform distributed training without centralising data. The training dataset is split across multiple devices or clients, potentially in a non-IID way. The key motivating factors are security and privacy of personal data. Use-cases include training on data from customers' mobile phones, and collaboratively training a healthcare model on patient data from hospitals. 

Communication is usually the limiting factor, and the field has grown recently with many communication-efficient algorithms proposed.We will start by considering federated learning's cryptographic origins. We will then explicitly consider its core challenges. We will build up from the simplest proposed SGD algorithms to more recent Bayesian algorithms. We will also briefly consider techniques that enhance security (like Secure Multi-Party Computation) and privacy (like Differential Privacy), which are of crucial importance in federated learning. Recommended Reading:

Recommended Reading:
1. Section 1 (Introduction) of "Federated Learning: Challenges, Methods, and Future Directions", Li et al., 2019, ([link](https://arxiv.org/pdf/1908.07873.pdf))
This is a good recent review paper of the field, and interested readers should read the entire paper.

Optional Reading:
1. "Communication-Efficient Learning of Deep Networks from Decentralized Data", McMahan et al., 2017. This paper coined the term, 'federated learning'.
2. "Advances and Open Problems in Federated Learning", Kairouz et al., 2019. A lengthy review paper on federated learning from the viewpoint of those at Google.
