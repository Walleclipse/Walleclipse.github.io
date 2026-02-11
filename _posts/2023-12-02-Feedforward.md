---
layout: post
title:  "Online Model Adaptation with Feedforward Compensation"
date:   2023-12-02 18:08:39 +00:00
image: /images/Feedforward.gif
categories: research
author: "Abulikemu Abuduweili"
authors: "<strong>Abulikemu Abuduweili</strong>,  Changliu Liu"
venue: "Conference on Robot Learning (CoRL)"
location: "Atlanta, Georgia, USA"
arxiv: https://proceedings.mlr.press/v229/abuduweili23a
code: https://github.com/intelligent-control-lab/Feedforward_Adaptation 
video: https://www.youtube.com/watch?v=fB9-UE3Q4bE
highlight: true
---

Robots deployed in the real world encounter environments that slowly drift over time—lighting changes, surfaces wear down, sensors degrade. Standard models trained offline can't keep up. Our solution: online feedforward adaptation that continuously fine-tunes the model using the most informative samples from recent experience. The payoff? Better predictions with provably smaller error bounds, even as the world changes around the robot.