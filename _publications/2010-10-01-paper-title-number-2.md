---
title: "Effect of Activation Functions on the Training of Overparametrized Neural Nets"
collection: publications
permalink: /publications/2019-10-03-Activation
authors: 'Abhishek Panigrahi, Abhishek Shetty, Navin Goyal'
venue: 'International Conference on Learning Representations (ICLR)'
paperurl: 'https://openreview.net/forum?id=rkgfdeBYvH'
date: 2019-12-20
excerpt: ''
year: '2020'
---

It is well-known that overparametrized neural networks trained using gradient-based methods quickly achieve small training error with appropriate hyperparameter settings. Recent papers have proved this statement theoretically for highly overparametrized networks under reasonable assumptions. These results either assume that the activation function is ReLU or they crucially depend on the minimum eigenvalue of a certain Gram matrix depending on the data, random initialization and the activation function. In the later case, existing works only prove that this minimum eigenvalue is non-zero and do not provide quantitative bounds. On the empirical side, a contemporary line of investigations has proposed a number of alternative activation functions which tend to perform better than ReLU at least in some settings but no clear understanding has emerged. This state of affairs underscores the importance of theoretically understanding the impact of activation functions on training. In the present paper, we provide theoretical results about the effect of activation function on the training of highly overparametrized 2-layer neural networks. A crucial property that governs the performance of an activation is whether or not it is smooth. For non-smooth activations such as ReLU, SELU and ELU, all eigenvalues of the associated Gram matrix are large under minimal assumptions on the data. For smooth activations such as tanh, swish and polynomials, the situation is more complex. If the subspace spanned by the data has small dimension then the minimum eigenvalue of the Gram matrix can be small leading to slow training. But if the dimension is large and the data satisfies another mild condition, then the eigenvalues are large. If we allow deep networks, then the small data dimension is not a limitation provided that the depth is sufficient. We discuss a number of extensions and applications of these results. 

The [paper](https://openreview.net/forum?id=rkgfdeBYvH){:target="_blank"} has been accepted for **Poster** presentation at the conference. 

Please find the below resources
1. [Proceedings and paper](https://openreview.net/forum?id=rkgfdeBYvH){:target="_blank"}.
2. [Video Presentation](https://iclr.cc/virtual_2020/poster_rkgfdeBYvH.html){:target="_blank"}.
