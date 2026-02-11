---
layout: post
title:  "Estimating Neural Network Robustness via Lipschitz Constant and Architecture Sensitivity"
date:   2024-10-22 18:08:39 +00:00
image: /images/Robustness.png
categories: research
author: "Abulikemu Abuduweili"
authors: "<strong>Abulikemu Abuduweili</strong>, Changliu Liu"
venue: "CoRL Workshop on Safe and Robust Robot Learning for Operation in the Real World <strong>[Oral Presentation]</strong>"
location: "Munich, Germany"
arxiv: https://openreview.net/forum?id=Mk2pq3Gjq1
---

A self-driving car's neural network works flawlessly in testing—then fails on a slightly different road sign. Why? Neural networks can be surprisingly fragile to tiny input changes. We show that the Lipschitz constant—a measure of how much outputs can change given small input perturbations—is the key to understanding and improving robustness. Better yet, we derive analytical expressions to estimate this from the network architecture itself, opening doors to designing inherently robust perception systems.