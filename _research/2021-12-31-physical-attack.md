---
title: "Intelligent Physical Attack Against Mobile Robots"

collection: research

permalink: /research/2021-12-31-physical-attack


excerpt: 'We investigate a novel intelligent physical attack against mobile robots without relying on any prior knowledge. The ultimate goal of the attacker is to learn the obstacle-avoidance mechanism of a mobile robot from external observation, and then leverage it to fool the target robot into a preset trap.'

date: 2021-12-31

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
