# Reinforcement Learning Implementations

A collection of reinforcement learning algorithms implemented as part of my RL self-study.

This repository covers the progression from **tabular methods** to **deep reinforcement learning**, with experiments on classic control environments such as CartPole, Acrobot, MountainCar, and Pendulum and on a 5x5 Maze evironment.
All implementations use popular environments from OpenAI Gym and include detailed explanations within the notebooks.

---

## 🎯 Algorithms Implemented & Environment implemented on

### 1. Dynamic Programming

* **Policy Iteration** - Iterative policy evaluation and improvement for solving MDPs - (5x5 Maze)
* **Value Iteration** - Direct computation of optimal value function - (5x5 Maze)

### 2. Monte Carlo Methods

* **On-policy Monte Carlo Control** - Learning from complete episodes - (5x5 Maze)
* **Off-policy Monte Carlo Control** - Importance sampling for learning from exploratory behavior - (5x5 Maze)
* **Constant-α Monte Carlo** - Fixed step-size updates for non-stationary problems - (5x5 Maze)

### 3. Temporal-Difference Learning

* **SARSA** - On-policy TD control algorithm - (5x5 Maze)
* **Q-Learning** - Off-policy TD control (learns optimal policy while following exploratory policy) - (5x5 Maze)
* **n-step SARSA** - Multi-step lookahead for better credit assignment - (5x5 Maze)

### 4. Function Approximation
- **State Aggregation & Tile Coding** - Methods for handling continuous observation spaces - (MountainCar)
- **Deep Q-Learning (DQN)** - Neural network approximation of Q-function - (CartPole)
- **Deep SARSA** - On-policy deep learning variant - (MountainCar)

### 5. Policy Gradient Methods
- **REINFORCE Algorithm** - Monte Carlo policy gradient - (CartPole)
- **Advantage Actor-Critic (A2C)** - Combines value and policy learning - (Acrobot)

### 6. Environment Exploration
- **Classic Control Theory environments** - Showcasing CartPole, Acrobot, MountainCar, and Pendulum environments
- **MDP Control Tasks Introduction** - Showcasing 5x5 Maze environment

---

## Environments

Experiments were conducted on OpenAI Gym classic control environments and custom 5x5 Maze environment:

* 5x5 Maze
* CartPole
* Acrobot
* MountainCar
* Pendulum

---

## Repository Structure

```
dynamic_programming/
monte_carlo_methods/
temporal_difference_learning/
function_approximation/
policy_gradient_methods/
environment_exploration/
README.md
```

Each notebook includes:

* Algorithm implementation
* Training loops with episode tracking
* Hyperparameter configurations
* Performance visualizations
* Environment-specific adaptations

---

## Goals of This Repository

* Understand RL algorithms **from first principles**
* Implement methods without relying on high-level libraries
* Compare learning behavior across different paradigms
* Build a strong foundation for advanced research and deep RL systems

---

## 🛠️ Technologies & Libraries

- **Python** - Primary programming language
- **NumPy** - Numerical computations
- **Gymnasium/OpenAI Gym** - RL environments
- **TensorFlow** - Deep learning frameworks (for DQN, A2C, REINFORCE)
- **Matplotlib** - Visualization of results

---

### Running the Notebooks

Each notebook is self-contained and can be run independently. Simply open any `.ipynb` file in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```
Navigate to the desired algorithm notebook and run all cells.
---

## Future Work

* PPO implementation
* Dueling / Double DQN
* Replay buffer improvements
* Continuous control with Actor-Critic variants
* Clean modular codebase (non-notebook version)

---

## 👤 Author

If you find this repository helpful, please consider giving it a ⭐!

## 🔗 Useful Links

- [OpenAI Gym Documentation](https://gymnasium.farama.org/)
- [Sutton & Barto Book (Free)](http://incompleteideas.net/book/the-book-2nd.html)
- [David Silver's Course](https://www.davidsilver.uk/teaching/)
