# RL-Swarm-Papers

1. Monitoring cross-research on RL & multi agent robotics.
2. Feel free to open PRs if you want to share the good papers you’ve read.

***

## Table of Content



***

# Research Review

[Sort by time]

***

### Multi-agent Reinforcement Learning: A Comprehensive Survey 

- Paper Link: [arXiv 2312.10256](https://arxiv.org/abs/2312.10256)

***

### A Survey of Progress on Cooperative Multi-agent Reinforcement Learning in Open Environment

- Paper Link: [arXiv 2312.01058](https://arxiv.org/abs/2312.01058)

<img src="./images/arXiv2312_01058_training.png" style="zoom:67%;" />

​	In MARL, training is the process of optimizing policies based on acquired experience (states, actions, rewards, etc.), while execution involves agents interacting with the environment by executing actions according to individual or joint policies. Generally, depending on whether agents need information from other agents during policy updates, the training process can be categorized into Centralized Training and Decentralized Training. Correspondingly, based on whether external information is required during the execution phase, it is categorized into Centralized Execution and Decentralized Execution. Combining these phases, MARL encompasses three paradigms: Decentralized Training Decentralized Execution (DTDE), Centralized Training Centralized Execution (CTCE), and Centralized Training Decentralized Execution (CTDE)

<img src="./images/arXiv2312_01058_communication.png" style="zoom:67%;" />

​	Key questions in communication involve determining who to communicate with, what information to communicate, and when to communicate. Current research explores three communication topologies: broadcasting information to all agents, forming network structures for selective communication, or communicating with a subset of neighbors. Policies for handling these questions include direct exchange of local information, preprocessing information before transmission, and optimizing communication timing. In conclusion, the challenges of non-stationarity, scalability, and partial observability in MARL demand innovative solutions to ensure effective learning and decision-making in complex, real-world scenarios.

***

### An Overview of Multi-Agent Reinforcement Learning from Game Theoretical Perspective

- Paper Link: [arXiv 2011.00583](https://arxiv.org/abs/2011.00583)

 <img src="./images/arXiv2011_00583_MARL_topology.png" style="zoom: 67%;" />

Common learning paradigms of MARL algorithms.
(1) Independent learners with shared policy. 
(2) Independent learners with independent policies (i.e. , denoted by the difference in wheels). 
(3) Independent learners with shared policy within a group. 
(4) One central controller controls all agents: agents can exchange information with any other agents at any time. 
(5) Centralised training with decentralised execution (CTDE): only during training, agents can exchange information with others; during execution, they act independently. 
(6) Decentralised training with networked agents: during training, agents can exchange information with their neighbours in the network; during execution, they act independently.

***

### Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms

- Paper Link: [arXiv 1911.10635](https://arxiv.org/abs/1911.10635) 

***

### A comprehensive survey of multi-agent reinforcement learning

- Paper Link: [IEEE 2007.913919](https://ieeexplore.ieee.org/abstract/document/4445757/)

***

### 智能集群系统的强化学习方法综述

- Paper Link: [中国计算机学报CJC 2023.12](http://cjc.ict.ac.cn/online/onlinepaper/lll-20231210115504.pdf)

***

#### 多智能体深度强化学习的若干关键科学问题

- Paper Link: [中国自动化学报ACTA 2020.7](http://www.aas.net.cn/fileZDHXB/journal/article/zdhxb/2020/7/PDF/AAS-CN-2020-0159.pdf)

***

### 万字长文：详解多智能体强化学习的基础和应用

- Web Link: [机器之心 2020.11](https://zhuanlan.zhihu.com/p/272735656)

***



## Papers

[sort by time]

***



