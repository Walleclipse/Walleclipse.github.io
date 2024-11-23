---
layout: post
title:  "Enhancing Sample Generation of Diffusion Models using Noise Level Estimation"
date:   2024-11-22 18:08:39 +00:00
image: /images/Diffusion.png
categories: research
author: "Abulikemu Abuduweili"
authors: "<strong>Abulikemu Abuduweili</strong>, Chenyang Yuan, Frank Permenter, Changliu Liu"
venue: " In submission; Arxiv preprint"
arxiv: https://arxiv.org/
---



 In diffusion models, the noise level of the noisy samples approximates the distance between the noisy samples and the underlying manifold. 
 Building on this insight, we propose a novel method to enhance sample generation quality by estimating the noise level. 
 We introduce a noise level estimation network that is on top of the pre-trained denoising network.  Additionally, we extend our approach 
 to tackle a variety of image restoration tasks, such as inpainting, deblurring, super-resolution, colorization, and compressed sensing.