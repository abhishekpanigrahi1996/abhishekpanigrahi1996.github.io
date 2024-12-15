---
title: "Efficient Stagewise Pretraining via Progressive Subnetworks"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-9
date: 2024-02-01
excerpt: ''
authors: 'Abhishek Panigrahi$\text{ }^{*}$, Nikunj Saunshi$\text{ }^{*}$, Kaifeng Lyu, Sobhan Miryoosefi, Sashank Reddi, Satyen Kale, Sanjiv Kumar'
paperurl: 'https://arxiv.org/abs/2402.05913'


---


Recent developments in large language models have sparked interest in efficient pretraining methods. Stagewise training approaches to improve efficiency, like gradual stacking and layer dropping (Reddi et al, 2023; Zhang & He, 2020), have recently garnered attention. The prevailing view suggests that stagewise dropping strategies, such as layer dropping, are ineffective, especially when compared to stacking-based approaches. This paper challenges this notion by demonstrating that, with proper design, dropping strategies can be competitive, if not better, than stacking methods. Specifically, we develop a principled stagewise training framework, progressive subnetwork training, which only trains subnetworks within the model and progressively increases the size of subnetworks during training, until it trains the full network. We propose an instantiation of this framework - Random Part Training (RAPTR) - that selects and trains only a random subnetwork (e.g. depth-wise, width-wise) of the network at each step, progressively increasing the size in stages. We show that this approach not only generalizes prior works like layer dropping but also fixes their key issues. Furthermore, we establish a theoretical basis for such approaches and provide justification for (a) increasing complexity of subnetworks in stages, conceptually diverging from prior works on layer dropping, and (b) stability in loss across stage transitions in presence of key modern architecture components like residual connections and layer norms. Through comprehensive experiments, we demonstrate that RAPTR can significantly speed up training of standard benchmarks like BERT and UL2, up to 33% compared to standard training and, surprisingly, also shows better downstream performance on UL2, improving QA tasks and SuperGLUE by 1.5%; thereby, providing evidence of better inductive bias.