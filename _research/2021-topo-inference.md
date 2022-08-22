---

title: "Topology Inference for Network Dynamical Systems"

collection: research

permalink: /research/2021-topo-inference

excerpt: 'We focus on the directed topology inference of NSs in state-space representation, where the observations are corrupted by noises. Specifically, we aim to reveal the relationships between the basic inference principles using observations from multiple and single trajectory of NSs, respectively. Meanwhile, we seek to derive the non-asymptotic convergence rate and accuracy of the inference methods about the observation number.'

venue: ''

---



<u>*Background*:</u> Network dynamical systems (NDSs) are characterized by the locality of information exchange between individual nodes (described by a topology), and the cooperative capability to solve a common task. Inferring the interaction topology structure from observations over the system emerges in various applications in last decades, including social networks, brain connectivity patterns and multi-robot formation, to name a few. Topology inference helps to better understand the systems and implement coordinated tasks, and thus plays a crucial role in many applications, such as tracing the information flow and predicting the system behavior. 

------

<u>*Problem of interest:*</u> We focus on the directed topology inference of NSs in state-space representation, where the observations are corrupted by noises. Specifically, we aim to reveal the relationships between the basic inference principles using observations from multiple and single trajectory of NSs, respectively. Meanwhile, we seek to derive the non-asymptotic convergence rate and accuracy of the inference methods about the observation number. 

------

<u>*Challenges and contributions:*</u> The challenge is two-fold. First, only noisy observations over the system evolution are available, incurring latent correlation on each consecutive pair in causality modeling. Second, the observations contain noise accumulation that is determined by different system stability. Our main contributions are as follows:

- We revealed the principles of inferring the topology by utilizing causality and correlation, where the system is driven by unknown driving input, and the topology is directed.
- We analyzed the non-asymptotic performance of the proposed method, pointed out the equivalent conditions with benchmark methods, and proved the convergence and accuracy in different system stabilities.
- We prove that the proposed estimator is essentially a deregularization version of the OLS estimator, and provide the online/recursive form of the proposed estimator, which can be applied to time-varying topology cases

*Representative papers*:	[[IEEE CDC'21](https://ieeexplore.ieee.org/document/9682968)] 