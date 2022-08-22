---

title: "Local Topology Inference of Mobile Robotic Networks under Formation Control"

collection: research

permalink: /research/2022-local-inference

excerpt: 'We focus on focuses on the local topology inference problem of MRNs under first-order linear formation control, where an inference robot can manoeuvre among the formation robots and observe their motions. Specifically, the inference robot has no knowledge of the formation inputs and interaction parameters, and the observation range is strictly limited.'

venue: ''

---



*<u>Background:</u>* The interaction topology is critical for efficient cooperation of mobile robotic networks (MRNs), where formation control serves as a fundamental technique to enhance the cooperation performance by maintaining a preset geometric shape. External attackers can utilize the topology inference method to find the critical robot that has significant control impacts in the formation. 

------

*<u>Problem of interest:</u>* We focus on focuses on the local topology inference problem of MRNs under first-order linear formation control, where an inference robot can manoeuvre among the formation robots and observe their motions. Specifically, the inference robot has no knowledge of the formation inputs and interaction parameters, and the observation range is strictly limited.

------

*<u>Challenges and contributions:</u>* Three aspects of challenges need to be addressed. First, the set of robots within the observation range of the inference robot can change over time. Second, the movement of formation robots heavily depends on the unknown formation input and interaction constraints. Third, the state evolution of the observable robot subset is determined by not only itself but also the unobservable robots. It is quite difficult to decouple the influences of the mixed three factors, and obtain a reliable local topology from the noise-corrupted observations. Our main contributions are as follows:

- We determine a constant subset from the time-varying set of robots within the observation range, and identify the formation input parameters. The estimation error bound under finite observations is established in probability.
- We develop an active excitation based method to obtain a reliable estimate of the interaction range. Combining the novel range-shrink strategy and the monotonicity analysis of the interaction range, the influence of unobservable robots is perfectly avoided.
- An ordinary least squares (OLS) based local topology estimator is established after filtering the formation input’s influence on observations before the steady stage. The convergence and accuracy of the proposed estimator are proved. 

*Representative papers*:	[[ECC'21](https://ieeexplore.ieee.org/document/9655038)] 