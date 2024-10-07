
# Chess-Bot-using-Deep-Reinforcement-Learning

## Overview

This project implements a **Chess Bot** that learns to play chess from scratch using **Deep Reinforcement Learning**. By leveraging advanced machine learning techniques, the bot gradually improves its game and has achieved an **ELO rating of 1100** through self-play. The project includes both training and deployment phases, using a large-scale, distributed computing architecture to ensure efficient learning.

## Key Features

- **Deep Reinforcement Learning**: The bot learns chess strategies through self-play, using a combination of **Convolutional Neural Networks (CNN)** and reinforcement learning algorithms.
- **Scalable Training Pipeline**: The training process is built on a distributed architecture to handle large-scale computations efficiently, enabling faster training times and better results.
- **Deployment**: The Chess Bot is deployed using **Flask** for serving the model and **Python-Chess** for simulating the game environment.

## Tools & Technologies

- **Python**: Core programming language used for developing the bot.
- **NumPy & Pandas**: Libraries used for data manipulation and processing.
- **TensorFlow**: Deep learning framework for implementing the CNN and training the bot using reinforcement learning.
- **Matplotlib**: Used for visualizing training results and performance metrics.
- **Flask**: A lightweight web framework for deploying the bot as a service.
- **Python-Chess**: A Python library for simulating chess games and interacting with the chess engine.

## Installation Procedure

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Akashsingh2100/Chess-Bot-using-Deep-Reinforcement-Learning.git

* Load both Notebooks into Google Colab
* Go to official website of ngrok and generate an Auth Token
* Replace the old Token present in second cell Chess_AI_Server notebook with this new Token
* Last step is to create a folder named `CHESS-AI` into your Google Drive
* Run both notebooks, firstly the Server then followed by Client

