# Distributed Event-Triggered Communication and Online Learning for Formation Control on SE(3)

This paper investigates the cooperative control of multiple rigid body systems evolving on the Lie group SE(3) with partially unknown dynamics under limited communication and computational resources. 
To address model uncertainties, an online Gaussian process (GP) regression scheme is employed to learn the unknown dynamics from locally collected data. 
A rigorous analysis establishes practical convergence to a time-varying leader–follower formation with a prescribed error bound, which is based on a joint condition on model accuracy and information freshness.
To efficiently satisfy this condition, a unified event-triggered framework is developed to simultaneously regulate online learning updates and inter-agent communication. 
The proposed mechanism effectively reduces both computational and communication loads, while preserving the desired control performance.
It is further proven that both the learning and communication triggering schemes exclude Zeno behavior.
Moreover, the framework enables explicit trade-offs among control performance, computational effort, and communication usage via tunable triggering parameters.
Numerical simulations are presented to demonstrate the effectiveness and efficiency of the proposed approach.
