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

Diffusion models generate stunning images, but what if we could make them even better? We discovered that the standard denoising process has a blind spot: it doesn't know how "noisy" an image truly is at each step. Our fix? A lightweight correction network that recalibrates noise estimates on the fly, guiding generation toward cleaner, sharper results. The best part: it plugs into any diffusion model and scheduler (DDIM, etc.), and naturally extends to image restoration tasks—inpainting, deblurring, super-resolution, and more.