---
title: "Trainable Transformer in Transformer"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-8
date: 2023-07-01
excerpt: ''
venue: 'International Conference on Machine Learning (ICML)'
year: '2024'
authors: 'Abhishek Panigrahi$\text{ }^{*}$, Sadhika Malladi$\text{ }^{*}$, Mengzhou Xia, Sanjeev Arora'
paperurl: 'https://arxiv.org/abs/2307.01189'


---


Recent works attribute the capability of in-context learning (ICL) in large pre-trained language models to implicitly simulating and fine-tuning an internal model (e.g., linear or 2-layer MLP) during inference. However, such constructions require large memory overhead, which makes simulation of more sophisticated internal models intractable. In this work, we propose an efficient construction, Transformer in Transformer (in short, TinT), that allows a transformer to simulate and fine-tune complex models internally during inference (e.g., pre-trained language models). In particular, we introduce innovative approximation techniques that allow a TinT model with less than 2 billion parameters to simulate and fine-tune a 125 million parameter transformer model within a single forward pass. TinT accommodates many common transformer variants and its design ideas also improve the efficiency of past instantiations of simple models inside transformers. We conduct end-to-end experiments to validate the internal fine-tuning procedure of TinT on various language modeling and downstream tasks. For example, even with a limited one-step budget, we observe TinT for a OPT-125M model improves performance by 4-16% absolute on average compared to OPT-125M. These findings suggest that large pre-trained language models are capable of performing intricate subroutines. To facilitate further work, a modular and extensible codebase for TinT is included.