Tabular POMDP Simulator

I'm working on understanding how agents make decisions in environments where uncertainty is involved. This project is part of my learning process in reinforcement learning, with a focus on tabular decision-making models.

I'll start with Markov Decision Processes (MDPs), then move toward Partially Observable MDPs (POMDPs), Bayesian Adaptive MDPs (BAMDPs), and Interactive POMDPs (IPOMDPs).

My goal is not just to implement these models, but to understand the problems they address, the assumptions behind them, and how their mathematical ideas translate into Python code.

Topics I'm Exploring

- MDP: Decision-making using observable states, actions, transition probabilities, and rewards.
- POMDP: Decision-making when the true state of the environment cannot be directly observed.
- BAMDP: Decision-making when the environment's model, such as its transition probabilities, is uncertain and must be learned.
- IPOMDP: Decision-making when an agent also reasons about other agents' beliefs and behavior.
- Bayesian inference: Updating beliefs when new evidence becomes available.

Progress

Day 1 — MDP Foundations

I started with the basics of reinforcement learning and Markov Decision Processes.

Concepts studied:

- Reinforcement learning and the agent-environment interaction.
- The five components of an MDP: state space, action space, transition model, reward function, and discount factor.
- The Markov property.
- Policies and discounted returns.
- Model-based and model-free reinforcement learning.

Implementation: Campus Robot Environment

I implemented a small deterministic environment in Python in which a robot moves between three locations: Classroom, Hallway, and Library.

The environment defines:

- A finite set of states.
- Available actions (forward and backward).
- A transition function that determines the next state.
- A reward function that returns immediate feedback.

This example helped me understand how an MDP represents an environment and how an agent's actions affect state transitions and rewards.

Current limitation: The example only simulates the environment. It does not yet implement a policy that learns or plans an optimal sequence of actions.

Repository Structure

tabular-pomdp-simulator/
│
├── learning-notes/
│   └── 01-mdp-foundations.md
│
├── examples/
│   └── mdp_example.py
│
├── README.md
└── .gitignore

Tools

- Python
- Git
- GitHub
- VS Code

Development Plan

I'll gradually extend this project by studying and implementing the mathematical foundations of partially observable and other uncertain decision-making models.

The implementation and documentation will grow as I work through each topic.
