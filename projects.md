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



### Holographic MIMO & Advanced Channel Coding for 6G

As wireless communication evolves toward the sixth generation (6G), a major technological shift is anticipated in the operating frequency bands. Specifically, there is a move from the current 2–3.5 GHz carrier frequency range used in 5G—known as Frequency Range 1 (FR1)—to the higher 7–14 GHz band, referred to as Frequency Range 3 (FR3). This transition enables a substantial increase in antenna density, with projections indicating a 4 to 16 times rise in the number of antennas per array while maintaining the same physical form factor as in 5G systems. However, this dramatic scaling presents a critical challenge: the conventional all-digital baseband processing used in today’s massive MIMO architectures becomes increasingly impractical due to excessive hardware complexity and power consumption. As a result, the development of innovative antenna technologies, particularly those incorporating efficient analog or hybrid RF-domain processing, is essential to realize the performance and energy efficiency targets of 6G systems.

This research activity focuses on two complementary axes: 1) novel massive MIMO schemes based on the concept of holographic antennas; 2) novel channel coding techniques for the multiuser MIMO channel.

1) Holographic MIMO consists of replacing the highly complex and power hungry all-digital processing of all antenna elements as in today's 5G technology with
analog RF processing directly in the wave domain, exploiting the properties of controllable metasurfaces. In this way, the digital processing is reduced to the minimum necessary information dimension, while the dimensionality expansion to harvest the benefit of antenna gains, and dynamic beam steering/shaping, is implemented bu controlling the electrical properties of
large-aperture  metasurface antennas. The challenges here are 1) accurate electromagnetic modeling of such metasurfaces including their controls; 2) design of the control algorithms to
obtain favorable channel conditions in the presence of multipath propagation and multiuser scenarios; 3) accurate complexity and power efficiency analysis; 4) Channel estimation and precoding/detection techniques in the baseband, optimized for the effective channel ``presented'' to the baseband by the RF processing stage.

2) Present state of the art channel coding in multiuser MIMO is based on a) pilot-based channel estimation; b) linear data stream separation; c) single-user decoding; d) concatenation of binary codes (LDPC and Polar Codes) with high-order modulation via the Bit-Interleaved Coded Modulation (BICM) paradigm. In this research thrust we shall explore a novel class of codes named SR-LDPC, obtained by concatenating a non-binary LDPC code with an inner Sparse-Regression (SR) code. These codes have the property that they inherently achieve the shaping gain since their codewords are essentially Gaussian random-line sequences. In addition, the structure of SR-LDPC is amenable for an advanced iterative decoder based on
Approximated Message Passing (AMP) with non-separable denoising function obtained by the LDPC Belief Propagation (BP) algorithm.
We shall consider the application fo these codes with a modified (novel, and recently discovered by Prof Caire and his collaborators) AMP-BP decoder for the multiuser MIMO case, that does not require the use of explicit pilots and channel estimation. In this way, the usual system bottleneck given by the number of orthogonal uplink pilots is eliminated.
Preliminary results indicate that this approach is promising and has the potential of improving upon the present state of the art.

**Contact:** Prof. Dr. Guiseppe Caire
