
# Day 18: Policy Gradient Methods

## Learning Objectives
1. Understand the concept of policy gradients and how they differ from value-based methods.
2. Learn about the REINFORCE algorithm as a foundational policy gradient method.

---

## Content

### 1. What are Policy Gradient Methods?
- **Concept**: Policy gradients directly optimize the policy (agent's behavior) by using a probability distribution over actions.
- **Goal**: The agent learns to maximize expected cumulative rewards by adjusting the probability of actions.

### 2. REINFORCE Algorithm
- **How It Works**: REINFORCE is a basic policy gradient algorithm that updates the policy weights in the direction of the reward.
- **Advantages**: Effective in tasks with continuous action spaces and can directly learn stochastic policies.

### 3. Applications of Policy Gradient Methods
- **Examples**: Robotics, continuous control tasks, and games with complex action spaces.

---

### Exercise
1. **Implement REINFORCE**: Use REINFORCE in a simple environment like CartPole.
2. **Experiment**: Adjust the learning rate and observe the changes in learning stability.
