---
title: Research Topics
---

### Silent Data Corruption Detection for LLM training.

Modern large language models (LLMs) have hundreds of billions (~100Bs) of parameters and need large amount of training data (~100Bs tokens), which requires weeks and even months of training, running on thousands of GPUs simultaneously. Their size has the secondary effect of increasing the likelihood of encountering hardware faults, requiring various detection and mitigation/recovery procedures which further adds to training time and cost. Faults in GPUs can lead to application-level errors, which can either be observed promptly, e.g. cause a crash or throw an exception, or not observed promptly, e.g. introduce incorrect data from incorrect calculation or data loss; the latter type is referred to as silent data corruption (SDC). Most strategies for mitigating the effect of SDCs are task-agnostic and focus on the fixing individual errors. 

The goal of this researcj is to develop methods to identify and localize SDCs when training instabilities occur during the training of LLMs, and to develop non-preemptive mitigation strategies that can allow training to continue, possibly in a suboptimal state, while still using the possibly defective chip(s). 

**Contact:** Anton Altenbernd,  Prof. Dr. Odej Kao

**Presentation:** [Research introduction](../docs/LLM_kao.pdf) 


### Boosting Efficiency of Serverless Computing Platforms

Serverless computing is the latest incarnation of cloud computing and is enjoying vast (and growing) popularity due to the powerful abstractions it offers to developers. As a result of the serverless abstractions, the additional software layers and coordination efforts create significant resource waste, thus, leading to both additional cost and carbon emissions. Examples include cold start latency or remote calls between FaaS functions which would have been either local or at least direct (not via an API gateway) in alternative architectural styles from monolith to microservices or cloud-native. There is hence significant potential for resource savings in this area by removing indirections. To preserve the powerful abstractions of FaaS, however, it is necessary to do that automatically and not to burden developers with this.

The overall goal of this work is to reduce such resource waste. For this, we will develop native provider-side support of intelligent application- and time-criticality-aware scheduling for FaaS platforms, targeting runtime deduplication and peak load shaving.

**Contact:** Niklas Kowallik, Prof. Dr.-Ing. David Bermbach

**Presentation:** [Research introduction](../docs/Serverless_Bermbach.pdf) 


### Analyzing and Optimizing AI Network Traffic Performance and Simulations

With the rapid expansion of AI-driven applications, it requires faster and more efficient networks to handle large amount of data. High performance networking is essential to ensure low-latency and high-throughput communication for AI workloads. However, existing solutions, such as InfiniBand and NVLink, are not only expensive but also rely on specialized hardware. These limitations make them difficult to adopt widely. As AI models continue to grow in size and complexity, there is a growing need for open, efficient, and scalable network solutions for AI inference.

To address this challenge, this research aims to shed light on traffic patterns and conduct simulations to optimize AI networks, e.g., using high-efficiency Ethernet protocol. Unlike current solutions, this approach will provide a more effective, flexible and accessible alternative for a boarder range of users to analyze and improve AI networking performance. By leveraging open-source methodologies, it allows researchers and engineers to explore new networking strategies that enhance both scalability and efficiency in AI inference workloads.


**Contact:** Huiran Liu, Prof.Dr. Stefan Schmid

**Presentation:** [Research introduction](../docs/Schmid_intro.pdf) 
