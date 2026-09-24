---
title: Data Assimilation
summary: <a href="https://en.wikipedia.org/wiki/Data_assimilation" style="color:blue;">Data assimilation</a> (DA) combines dynamical models with sparse, noisy observations to estimate latent system states and quantify uncertainty for applications such as climate forecasting and environmental monitoring. In practice, traditional DA methods face severe challenges due to high-dimensional state spaces, nonlinear and possibly chaotic dynamics, model error arising from imperfect physical representations, and non-Gaussian uncertainties. Therefore, it is crucial to develop efficient and robust DA algorithms that can handle high-dimensional systems while properly accounting for model uncertainties for complex dynamical systems.
show_date: false
image:
  preview_only: true
weight: 3
---


- **[Flow Ensemble Filter](/publication/6-preprint-flowef/)** proposes 
a learned nonlinear analysis update that augments a classical ensemble filter by transporting the forecast ensemble from a classical baseline filter to an analysis ensemble using conditional flow matching. It uses a localized Gaussian source during training, transports forecast ensemble members from a baseline filter at deployment, and conditions its velocity field on ensembles from that baseline filter and the observation. The proposed model therefore learns a nonlinear update while mapping each baseline ensemble independently. 