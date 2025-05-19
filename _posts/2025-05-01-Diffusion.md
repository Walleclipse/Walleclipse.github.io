---
layout: post
title:  "Enhancing Sample Generation of Diffusion Models using Noise Level Correction"
date:   2025-05-01 18:08:39 +00:00
image: /images/Diffusion.png
categories: research
author: "Abulikemu Abuduweili"
authors: "<strong>Abulikemu Abuduweili</strong>, Chenyang Yuan, Changliu Liu, Frank Permenter"
venue: "Transactions on Machine Learning Research (TMLR)"
arxiv: https://arxiv.org/abs/2412.05488
---


This paper proposes a novel method to enhance diffusion model sample generation by aligning noise level estimates with the true distance to the underlying manifold. A noise level correction network refines estimates during denoising, compatible with any scheduler (e.g., DDIM), and extends to image restoration tasks like inpainting, deblurring, super-resolution, colorization, and compressed sensing.