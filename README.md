**Introducing a reinforcement learning approach for efficient taxi navigation in a grid environment**  

We apply and compare different reinforcement learning algorithms to the **Taxi-v3** environment from OpenAI Gym. Techniques like **Q-Learning** and **Double Q-Learning (DQL)** are used to train an agent that picks up and drops off passengers efficiently.

**Q-Learning** is a model-free, off-policy algorithm that uses a single Q-table to estimate the value of actions in each state. However, it suffers from overestimation bias during learning.  
- **Accuracy Achieved:** *62.37%*

**Double Q-Learning**, an improvement over Q-Learning, uses two Q-tables to reduce this bias and provides more stable and accurate value estimates.  
- **Accuracy Achieved:** *88.46%*  
- **Improvement:** *+26.09% over Q-Learning*

The taxi agent learns to make decisions like moving, picking up, and dropping off passengers based on rewards.  
Our results show that **Double Q-Learning significantly outperforms standard Q-Learning**, achieving faster and more reliable convergence to optimal policies.
