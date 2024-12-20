---
title: "Do Transformers Parse while Predicting the Masked Word?"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-7
date: 2023-02-13
excerpt: ''
venue: 'Empirical Methods in Natural Language Processing (EMNLP)'
year: '2023'
authors: 'Haoyu Zhao$\text{ }^{*}$, Abhishek Panigrahi$\text{ }^{*}$, Rong Ge, Sanjeev Arora'
paperurl: 'https://arxiv.org/pdf/2303.08117.pdf'


---

Pre-trained language models have been shown to encode linguistic structures, e.g. dependency and
constituency parse trees, in their embeddings while being trained on unsupervised loss functions like
masked language modeling. Some doubts have been raised whether the models actually are doing parsing
or only some computation weakly correlated with it. We study questions: (a) Is it possible to explicitly
describe transformers with realistic embedding dimension, number of heads, etc. that are capable of doing
parsing —or even approximate parsing? (b) Why do pre-trained models capture parsing structure? This
paper takes a step toward answering these questions in the context of generative modeling with PCFGs.
We show that masked language models like BERT or RoBERTa of moderate sizes can approximately
execute the Inside-Outside algorithm for the English PCFG [Marcus et al., 1993]. We also show that
the Inside-Outside algorithm is optimal for masked language modeling loss on the PCFG-generated data.
We also give a construction of transformers with 50 layers, 15 attention heads, and 1275 dimensional
embeddings in average such that using its embeddings it is possible to do constituency parsing with > 70%
F1 score on PTB dataset. We conduct probing experiments on models pre-trained on PCFG-generated
data to show that this not only allows recovery of approximate parse tree, but also recovers marginal
span probabilities computed by the Inside-Outside algorithm, which suggests an implicit bias of masked
language modeling towards this algorithm.
