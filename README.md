# Snake Game AI - Reinforcement Learning & Deep Q-Learning

This project implements an AI-driven **Snake** game using **Deep Q-Learning (DQL)**, a **Reinforcement Learning (RL)** technique. The AI learns to play Snake by optimizing its movements through rewards and penalties, gradually improving its performance over time.

---

## 🎮 Why Reinforcement Learning?

Traditional supervised learning relies on labeled data, but in the case of Snake, the "best move" at any given time isn't pre-defined. **Reinforcement Learning** (RL) allows the AI (the Snake) to learn optimal strategies by interacting with the environment—receiving **rewards** for good actions and **penalties** for bad ones.

---

## 📚 Algorithm Overview

The game consists of a **snake** and **food**, placed randomly on the board. The state of the snake is captured using 11 key values, and the AI predicts the next action based on the current state.

### 🏆 Rewards:
- **+10** for eating food 🥳
- **-10** for hitting the wall (Game Over) 💥
- **0** for any other action 🔄

The **Q-values** are updated and improved during training, allowing the snake to become increasingly skilled at avoiding obstacles and finding food.

---

## 🏗️ Project Structure

- **Agent**: The AI decision-maker that uses Deep Q-Learning to determine the best actions.
- **Game**: The Snake game environment (built using **pygame**).
- **Model**: The **Deep Neural Network** (DNN) that learns and predicts the best actions based on the current game state.

---

## 🚀 Results

- Initially, the AI starts by making **random moves**.
- After training for **100 epochs**, the AI becomes proficient in:
  - Avoiding walls 🚧
  - Actively seeking food 🍏
  - Improving its overall strategy over time 🔥

---

## 💻 Live Demonstration

🎥 Watch the AI in action!  
[Live Demo](#) *(Replace with actual link when available)*

---

## 🛠️ Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/snake-game-ai.git

2. Navigate to the project folder:
   ```
   cd snake-game-ai

4. Run the game:
   ```
   python snake_game.py

---
## 💬 Feedback
Have any questions or suggestions? Feel free to open an issue, and I'll get back to you as soon as possible!
