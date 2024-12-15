---
title: "Progressive distillation induces an implicit curriculum"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-10
date: 2024-10-01
excerpt: ''
authors: 'Abhishek Panigrahi$\text{ }^{*}$, Bingbin Liu$\text{ }^{*}$, Sadhika Malladi, Andrej Risteski, Surbhi Goel'
paperurl: 'https://arxiv.org/abs/2410.05464'


---


Knowledge distillation leverages a teacher model to improve the training of a student model. A persistent challenge is that a better teacher does not always yield a better student, to which a common mitigation is to use additional supervision from several ``intermediate'' teachers. One empirically validated variant of this principle is progressive distillation, where the student learns from successive intermediate checkpoints of the teacher. Using sparse parity as a sandbox, we identify an implicit curriculum as one mechanism through which progressive distillation accelerates the student's learning. This curriculum is available only through the intermediate checkpoints but not the final converged one, and imparts both empirical acceleration and a provable sample complexity benefit to the student. We then extend our investigation to Transformers trained on probabilistic context-free grammars (PCFGs) and real-world pre-training datasets (Wikipedia and Books). Through probing the teacher model, we identify an analogous implicit curriculum where the model progressively learns features that capture longer context. Our theoretical and empirical findings on sparse parity, complemented by empirical observations on more complex tasks, highlight the benefit of progressive distillation via implicit curriculum across setups.
