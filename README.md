Snake Game AI - Reinforcement Learning & Deep Q-Learning
This project implements an AI-driven Snake game using Deep Q-Learning (DQL), a Reinforcement Learning (RL) technique. The AI learns to play Snake by optimizing its movements through rewards and penalties.

Why Reinforcement Learning?
Traditional supervised learning requires labeled data, but in our case, the best move at each step is unknown. Reinforcement Learning allows the AI agent (Snake) to learn optimal strategies through interaction with the game environment.

Algorithm Overview
The game board consists of a snake and food, randomly placed.
The state of the snake is represented using 11 key values.
The RL model predicts the next action based on the current state.
Rewards are assigned:
+10 for eating food
-10 for hitting the wall (Game Over)
0 otherwise
The model updates the Q-values and improves through training.
Project Structure
Agent: The AI decision-maker using Deep Q-Learning.
Game: The Snake game environment (built with pygame).
Model: Deep Neural Network for learning and predicting actions.
Results
Initially, the AI makes random moves.
After 100 epochs, the AI optimizes movements, avoiding walls and seeking food efficiently.
Live Demonstration
🚀 Watch the AI in action: Live Demo (Replace with the actual link when available)

Try It Out
A simple user-controlled version of the Snake game is available: Snake Game (Pygame)
