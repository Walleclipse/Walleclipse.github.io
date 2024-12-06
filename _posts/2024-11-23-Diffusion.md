---
layout: post
title:  "Enhancing Sample Generation of Diffusion Models using Noise Level Correction"
date:   2024-11-22 18:08:39 +00:00
image: /images/Diffusion.png
categories: research
author: "Abulikemu Abuduweili"
authors: "<strong>Abulikemu Abuduweili</strong>, Chenyang Yuan, Changliu Liu, Frank Permenter"
venue: " In submission; Arxiv preprint"
arxiv: https://arxiv.org/
---



In diffusion models, the noise level in noisy samples approximates their distance to the underlying manifold.
Building on this insight, we propose a novel method to enhance sample generation by aligning the estimated noise level with the true distance of noisy samples to the manifold.
We introduce a noise level correction network built to refine noise level estimates during the denoising process, and can be applied on top of any existing denoising scheduler (e.g., DDIM). 
 Furthermore, we extend this approach to various image restoration tasks by integrating task-specific constraints, including inpainting, deblurring, super-resolution, colorization, and compressed sensing.