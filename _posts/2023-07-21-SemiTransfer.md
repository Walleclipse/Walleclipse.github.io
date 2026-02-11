---
layout: post
title:  "Semi-Supervised Transfer Learning with Hierarchical Self-Regularization"
date:   2023-07-21 18:08:39 +00:00
image: /images/Adaptive-KD.png
categories: research
author: "Abulikemu Abuduweili"
authors: "Xingjian Li*, <strong>Abulikemu Abuduweili*</strong>,  Humphrey Shi, Pengkun Yang, Dejing Dou, Haoyi Xiong, Chengzhong Xu"
venue: "Pattern Recognition"
arxiv: https://doi.org/10.1016/j.patcog.2023.109831 
code: https://github.com/SHI-Labs/Semi-Supervised-Transfer-Learning 
---

Pre-trained models are powerful, but fine-tuning them with limited labeled data is tricky—you risk either forgetting what they knew or overfitting to your small dataset. We introduce hierarchical self-regularization: the model constrains itself at both individual and population levels, with adaptive weighting that knows when to trust the teacher vs. explore new patterns. The approach boosts performance whether you're doing semi-supervised, fully-supervised, or even self-supervised learning.
