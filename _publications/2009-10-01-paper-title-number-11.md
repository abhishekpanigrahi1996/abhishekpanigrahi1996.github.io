---
title: "Inducing Robust Algorithmic Reasoning in Vision Language Models"
collection: publications
permalink: /publications/2015-10-01-paper-title-number-11
date: 2024-12-01
excerpt: ''
authors: 'Simon Park$\text{ }^{*}$, Abhishek Panigrahi$\text{ }^{*}$, Yun CHeng$\text{ }^{*}$, Dingli Yu, Anirudh Goyal, Sanjeev Arora'

---


Recent works point out a modality imbalance in
Vision Language Models (VLMs), characterized
by a performance gap between a VLM and its
LLM backbone when evaluated on image and
text-formatted inputs of the same task. While
most such studies involve in-domain evaluation,
we study modality imbalance with respect to an
out-of-distribution (OOD) generalization. On four
synthetic settings involving algorithmic reasoning, which are difficult for frontier VLMs such
as GPT-4o and Claude-3.5 Sonnet, we identify
families of SIMPLE and HARD instances in each
setting and study SIMPLE-to-HARD (S2H) generalization. We first propose learning strategies to
mitigate modality imbalance on tasks where the
LLM backbone can achieve good S2H generalization on text inputs. In settings where the HARD
instances remain difficult for the LLM backbone,
we adapt the strategy to use fine-tuning to improve its S2H generalization on text inputs, which
transfers to good S2H generalization on images.
Ablation studies reveal that VLMs benefit significantly from explicit image-to-text conversion and
chain-of-thought during training.