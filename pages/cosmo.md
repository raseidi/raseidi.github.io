---
layout: post
---

# CoSMo

The **Co**nditioned Process **S**imulation **Mo**del (CoSMo) is a framework that trains deep generative models to create process simulation models. Unlike other solutions, our approach uses a conditional mechanism during the training phase to reduce randomness. By teaching deep neural networks how to perform conditioned simulations, users have greater flexibility to perform analysis based on their interests. For example, CoSMo can learn how to satisfy conditions based on the resource usage of processes. See in the figure below how traces simulated from different case positions (a.k.a. time positions) can be simulated by satisfying two different conditions (i.e. usage or abscence of a specific resource).

![alt text](/assets/img/posts/cosmo/results.png)

The preprint is available on [arxiv](https://arxiv.org/abs/2303.17879) and the code fully available on [github](https://github.com/raseidi/cosmo).

[back](/)
