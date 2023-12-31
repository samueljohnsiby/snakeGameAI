# Snake Game AI using Reinforcement Learning
This repository contains code snippets and modules for building a Snake Game AI using reinforcement learning techniques.

## Inspiration
This project is a follow along of the freecodecamp course (https://www.youtube.com/watch?v=L8ypSXwyBds). 
Github link: https://github.com/patrickloeber/snake-ai-pytorch

## Contents
Agent.py: Contains the definition of the Agent class responsible for training the Snake Game AI.
Model.py: Includes the neural network model (Linear_QNet) and trainer (QTrainer) used for training the AI.
Game.py: Defines the Snake Game logic (SnakeGameAI) such as game state, actions, and rewards.
Helper.py: Provides utility functions for plotting scores and mean scores during training.


1. Agent.py
Implements the Agent class responsible for training the Snake Game AI.
Defines functions for getting the game state, training long and short memory, and making AI moves.
2. Model.py
Contains the neural network model (Linear_QNet) used for the Snake Game AI.
Defines the QTrainer class responsible for training the AI model using Q-learning.
3. Game.py
Includes the logic for the Snake Game (SnakeGameAI), including defining the game state, actions, and rewards.
Handles the game state, actions, rewards, and game resets.
4. Helper.py
Provides utility functions for plotting game scores and mean scores during training.
# Usage
The code snippets provided are designed to work together to train a Snake Game AI using reinforcement learning.
The train() function in the main script orchestrates the training process. Run this script to start training the AI.



## License
This project is licensed under the GNU License.
