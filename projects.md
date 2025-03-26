---
title: Research Topics
---

### Silent Data Corruption Detection for LLM training.

Modern large language models (LLMs) have hundreds of billions (~100Bs) of parameters and need large amount of training data (~100Bs tokens), which requires weeks and even months of training, running on thousands of GPUs simultaneously. Their size has the secondary effect of increasing the likelihood of encountering hardware faults, requiring various detection and mitigation/recovery procedures which further adds to training time and cost. Faults in GPUs can lead to application-level errors, which can either be observed promptly, e.g. cause a crash or throw an exception, or not observed promptly, e.g. introduce incorrect data from incorrect calculation or data loss; the latter type is referred to as silent data corruption (SDC). Most strategies for mitigating the effect of SDCs are task-agnostic and focus on the fixing individual errors. 

The goal of this researcj is to develop methods to identify and localize SDCs when training instabilities occur during the training of LLMs, and to develop non-preemptive mitigation strategies that can allow training to continue, possibly in a suboptimal state, while still using the possibly defective chip(s). 

**Contact:** Anton Altenbernd,  Prof. Dr Odej Kao

**Presentation:** [Research introduction](docs/LLM_kao.pdf) 

<a href="docs/LLM_kao.pdf" class="image fit"></a>
