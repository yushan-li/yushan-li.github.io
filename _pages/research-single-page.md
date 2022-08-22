---
permalink: research/
title: "Research Direction"
author_profile: true
redirect_from: 
  - /rs/
  - /research.html
---


# **Intelligent Physical Attack Against Mobile Robots**

*<u>Background:</u>* The mobile robots can be seen as a typical cyber-physical system (CPS), whose security issues become critical yet imperatively challenging. Prior works concerning the security of mobile robots are mainly developed from the perspective of cyberspace, while physical attacks are less noticed yet also critically important. It is universally needed for mobile robots in the real world to interact with the physical environment, which also essentially brings a security vulnerability. 

------

*<u>Problem of interest:</u>* We investigate a novel intelligent physical attack against mobile robots without relying on any prior knowledge. The ultimate goal of the attacker is to learn the obstacle-avoidance mechanism of a mobile robot from external observation, and then leverage it to fool the target robot into a preset trap.

------

*<u>Challenges and contributions:</u>* Three major challenges must be addressed. First, the attacker is unaware of the prerequisite information that supports the attack (like the obstacle detection range and goal position), making it an impediment to formulating the attack model by traditional techniques. Second, the attacker and victim robots are mutually influenced in the motion space, incurring difficulties to find the feasible solution space that meets the attack requirements. Third, even if a feasible solution space is found, it is hard to optimize strategy designs to achieve the final purpose with low attack costs. Our main contributions are as follows: 

- Taking the universal obstacle-avoidance mechanism as the attack interface, we investigate the possibility of achieving an intelligent and advanced physical attack against mobile robots, merely utilizing external observations and not relying on any prior information of the system dynamics.
- We propose an intentional excitation based learning approach to acquire the obstacle-avoidance knowledge by disguising the attacker as an obstacle. We establish the featured data pairs that reflect the underlying mechanism and further regress it by learning-based methods.
- We design two driving-to-trap attack algorithms by taking the attack path length and activity period as the objectives, respectively. The convergence and performance bounds are analyzed. Extensive simulations and real-life experiments illustrate the effectiveness of the proposed attack.

*Representative papers*:	[[IEEE TRO'22](https://arxiv.org/abs/1910.06461)]	[[ACC'19](https://ieeexplore.ieee.org/document/8814377)] 



# Topology Inference for Network dynamical systems

<u>*Background*:</u> Network dynamical systems (NDSs) are characterized by the locality of information exchange between individual nodes (described by a topology), and the cooperative capability to solve a common task. Inferring the interaction topology structure from observations over the system emerges in various applications in last decades, including social networks, brain connectivity patterns and multi-robot formation, to name a few. Topology inference helps to better understand the systems and implement coordinated tasks, and thus plays a crucial role in many applications, such as tracing the information flow and predicting the system behavior. 

------

<u>*Problem of interest:*</u> We focus on the directed topology inference of NSs in state-space representation,
where the observations are corrupted by noises. Specifically, we aim to reveal the relationships between the basic inference principles using observations from multiple and single trajectory of NSs, respectively. Meanwhile, we seek to derive the non-asymptotic convergence rate and accuracy of the inference methods about the observation number. 

------

<u>*Challenges and contributions:*</u> The challenge is two-fold. First, only noisy observations over the system evolution are available, incurring latent correlation on each consecutive pair in causality modeling. Second, the observations contain noise accumulation that is determined by different system stability. Our main contributions are as follows:

- We revealed the principles of inferring the topology by utilizing causality and correlation, where the system is driven by unknown driving input, and the topology is directed.
- We analyzed the non-asymptotic performance of the proposed method, pointed out the equivalent conditions with benchmark methods, and proved the convergence and accuracy in different system stabilities.
- We prove that the proposed estimator is essentially a deregularization version of the OLS estimator, and provide the online/recursive form of the proposed estimator, which can be applied to time-varying topology cases

*Representative papers*:	[[IEEE CDC'21](https://ieeexplore.ieee.org/document/9682968)] 



# **Local Topology Inference of Mobile Robotic Networks under Formation Control**

*<u>Background:</u>* The interaction topology is critical for efficient cooperation of mobile robotic networks (MRNs), where formation control serves as a fundamental technique to enhance the cooperation performance by maintaining a preset geometric shape. External attackers can utilize the topology inference method to find the critical robot that has significant control impacts in the formation. 

------

*<u>Problem of interest:</u>* We focus on focuses on the local topology inference problem of MRNs under first-order linear formation control, where an inference robot can manoeuvre among the formation robots and observe their motions. Specifically, the inference robot has no knowledge of the formation inputs and interaction parameters, and the observation range is strictly limited.

------

*<u>Challenges and contributions:</u>* Three aspects of challenges need to be addressed. First, the set of robots within the observation range of the inference robot can change over time. Second, the movement of formation robots heavily depends on the unknown formation input and interaction constraints. Third, the state evolution of the observable robot subset is determined by not only itself but also the unobservable robots. It is quite difficult to decouple the influences of the mixed three factors, and obtain a reliable local topology from the noise-corrupted observations. Our main contributions are as follows:

- We determine a constant subset from the time-varying set of robots within the observation range, and identify the formation input parameters. The estimation error bound under finite observations is established in probability.
- We develop an active excitation based method to obtain a reliable estimate of the interaction range. Combining the novel range-shrink strategy and the monotonicity analysis of the interaction range, the influence of unobservable robots is perfectly avoided.
- An ordinary least squares (OLS) based local topology estimator is established after filtering the formation input’s influence on observations before the steady stage. The convergence and accuracy of the proposed estimator are proved. 

*Representative papers*:	[[ECC'21](https://ieeexplore.ieee.org/document/9655038)] 
