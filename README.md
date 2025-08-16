# Snake Game with Deep Q-Learning (PyGame + Reinforcement Learning)

A classic Snake game implemented using [PyGame](https://www.pygame.org/) and trained with Deep Q-Learning (DQN), a reinforcement learning algorithm. This project demonstrates how an agent can learn to play Snake autonomously using neural networks and experience replay.

## Features

- Classic Snake game interface using PyGame
- Deep Q-Network (DQN) implementation for reinforcement learning
- Train your own AI agent to play Snake
- Save/load trained models
- Visualize training progress and agent's gameplay

## Demo

![Snake DQN Demo](demo.gif) <!-- Replace or add a local screen recording or GIF if available -->

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/Shashankkusu/Snake-pyGame-DQN-Reinforcement-Learning-.git
    cd Snake-pyGame-DQN-Reinforcement-Learning-
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
    Or install manually:
    ```bash
    pip install pygame numpy torch matplotlib
    ```

### Running the Game

#### Human Play
To play the game yourself:
```bash
python snake_game.py
