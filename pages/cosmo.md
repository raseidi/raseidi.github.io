---
layout: post
---

# CoSMo

Paper accepted at the [BPM'24](https://arxiv.org/abs/2303.17879) conference. Code fully available on [github](https://github.com/raseidi/cosmo).

Process simulation is gaining attention for its ability to assess potential performance improvements and risks associated with business process changes. The existing literature presents various techniques, generally grounded in process models discovered from event logs or built upon deep learning algorithms. These techniques have specific strengths and limitations. Traditional approaches rooted in process models offer increased interpretability, while those using deep learning excel at generalizing changes across large event logs. However, the practical application of deep learning faces challenges related to managing stochasticity and integrating information for what-if analysis. This paper introduces a novel recurrent neural architecture tailored to discover **CO**nditioned Process **S**imulation **MO**dels (CoSMo) based on user-based constraints or any other nature of a-priori knowledge. This architecture facilitates the simulation of event logs that adhere to specific constraints by incorporating declarative-based rules into the learning phase as an attempt to fill the gap of incorporating information into deep learning models to perform what-if analysis. Experimental validation illustrates CoSMo's efficacy in simulating event logs while adhering to predefined declarative conditions, emphasizing both control-flow and data-flow perspectives.

![alt text](/assets/img/posts/cosmo/architecture.png)


[back](/)
