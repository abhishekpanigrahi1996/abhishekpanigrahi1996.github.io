---
title: "On the SDEs and Scaling Rules for Adaptive Gradient Algorithms"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-5
date: 2022-09-17
venue: 'Neural Information Processing Systems (NeurIPS)'
year: '2022'
excerpt: ''
authors: 'Sadhika Malladi$\text{ }^{*}$, Kaifeng Lyu$\text{ }^{*}$, Abhishek Panigrahi, Sanjeev Arora'
paperurl: 'https://openreview.net/pdf?id=F2mhzjHkQP'

---

Approximating Stochastic Gradient Descent (SGD) as a Stochastic Differential Equation (SDE) has allowed researchers to enjoy the benefits of studying a continuous optimization trajectory while carefully preserving the  stochasticity of SGD. Analogous study of adaptive gradient methods, such as RMSprop and Adam, has been challenging because there were no rigorously proven SDE approximations for these methods. This paper derives the SDE approximations for RMSprop and Adam, giving theoretical guarantees of their correctness as well as experimental validation of their applicability to common large-scaling vision and language settings. A key practical result is the derivation of a \textit{square root scaling rule} to adjust the optimization hyperparameters of RMSprop and Adam when changing batch size, and its empirical validation in deep learning settings.
