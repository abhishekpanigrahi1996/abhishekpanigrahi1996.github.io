---
title: "Task-Specific Skill Localization in Fine-tuned Language Models"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-6
date: 2023-02-13
excerpt: ''
venue: 'International Conference on Machine Learning (ICML)'
year: '2023'
authors: 'Abhishek Panigrahi$\text{ }^{*}$, Nikunj Saunshi$\text{ }^{*}$, Haoyu Zhao, Sanjeev Arora'
paperurl: 'https://arxiv.org/pdf/2302.06600.pdf'


---

Pre-trained language models can be fine-tuned
to solve diverse NLP tasks, including in few-shot
settings. Thus fine-tuning allows the model
to quickly pick up task-specific “skills,” but
there has been limited study of where these
newly-learnt skills reside inside the massive
model. This paper introduces the term skill
localization for this problem and proposes a
solution. Given the downstream task and a model
fine-tuned on that task, a simple optimization is
used to identify a very small subset of parameters
(∼ 0.01% of model parameters) responsible for
(> 95%) of the model’s performance, in the
sense that grafting the fine-tuned values for just
this tiny subset onto the pre-trained model gives
performance almost as well as the fine-tuned
model. While reminiscent of recent works on
parameter-efficient fine-tuning, the novel aspects
here are that: (i) No further re-training is needed
on the subset (unlike, say, with lottery tickets). (ii)
Notable improvements are seen over vanilla finetuning with respect to calibration of predictions
in-distribution (40-90% error reduction) as well
as the quality of predictions out-of-distribution
(OOD). In models trained on multiple tasks, a
stronger notion of skill localization is observed,
where the sparse regions corresponding to different tasks are almost disjoint, and their overlap
(when it happens) is a proxy for task similarity.
Experiments suggest that localization via grafting
can assist certain forms of continual learning.
