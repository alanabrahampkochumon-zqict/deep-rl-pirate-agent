# Maze Solving Agent based on Reinforcement Learning (SNHU CS 370)

This repository contains a deep reinforcement learning agent designed to navigate a maze and find a hidden treasure. It demonstrates the practical application of Q-learning and neural networks to solve pathfinding and decision-making problems in a constrained environment.

## Screenshots

![Incomplete Maze](Screenshots/Incomplete%20Maze.png)
![Complete Maze](Screenshots/Complete%20Maze.png)

## Project Context and Code Breakdown

This project required integrating pre-existing environment architecture with custom-built machine learning logic.

**Code Provided:**

- TreasureMaze.py: Encapsulated the core game logic, state management, and environment rendering.
- Game Experience Class: Acted as the replay memory buffer, storing state transitions for the agent to learn from.
- Neural Network Boilerplate: The foundational Deep Learning Model utilizing three dense layers and the PReLU activation function.
- Testing Framework: Pre-written code to verify if the agent successfully found the path to the reward.

**Code Created:**

- Reinforcement Learning Logic: I translated pseudocode into a functional Deep Q-Learning training algorithm.
- Training Loop: I engineered the core loop where the agent interacts with the maze, balances exploration versus exploitation (epsilon-greedy strategy), records experiences, and updates the neural network's weights based on the calculated rewards.
- Verification: I executed and validated the training algorithm, ensuring the pirate agent consistently solved the maze across multiple test cases.

## The Role of a Computer Scientist

Computer scientists work on developing algorithms and innovative approaches to solve complex problems at various architectural levels. Rather than simply writing code, they focus on theoretical and empirical methods to ensure mathematical consistency. This involves defining invariants (conditions that must remain true during execution), analyzing runtime and memory efficiency using Big-O notation, and providing robust implementations. In the context of machine learning, computer scientists are responsible for driving the industry forward, having engineered cutting-edge architectures like Advantage Actor-Critic (A2C) networks and modern Transformer models. This work matters because it builds the highly optimized, scalable systems that power modern technology and decision-making.

## Approaching Problems as a Computer Scientist

As a computer scientist, I approach problems empirically and structurally. Instead of adopting a "code-first" mentality, I focus on mathematical soundness and logical design. This often involves writing down proofs, diagramming system architecture, and rigorously working through edge cases before writing a single line of syntax. By breaking a problem down into its theoretical constraints and defining the precise input-output relationships, I ensure the resulting code is not just functional, but reliable, scalable, and optimized.

## Ethical Responsibilities

My ethical responsibilities to the end-user and the organization often require careful, principled navigation, as their interests can sometimes conflict.

- **To the Organization**: I am tasked with being a good steward of their resources. This means using my problem-solving skills to devise robust methods that directly address business needs, such as generating income, optimizing performance, or reducing system downtime.

- **To the End-User**: I possess a strict moral obligation to protect their well-being. This requires absolute transparency regarding data collection, ensuring their information is used securely and responsibly, and clearly weighing the consequences of the software they interact with.

When the interests of the organization and the user overlap, software acts as a mutual benefit. However, when those interests conflict, I must make ethically sound decisions rooted in integrity and honesty, ensuring that corporate objectives never compromise the privacy, safety, or fundamental rights of the end-user.
