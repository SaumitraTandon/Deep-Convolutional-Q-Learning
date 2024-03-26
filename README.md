# Deep Convolutional Q-Learning for Pac-Man

This project implements a Deep Convolutional Q-Learning (DCQN) agent to play the Ms. Pac-Man game using the OpenAI Gymnasium environment.

## Gymnasium

Gymnasium is a toolkit for developing and comparing reinforcement learning algorithms. It provides a wide range of environments for training agents, including classic Atari games like Ms. Pac-Man.

## Convolutional Deep Q-Learning

Convolutional Deep Q-Learning (CDQN) is an extension of Deep Q-Learning (DQN) that uses convolutional neural networks (CNNs) to process raw pixel inputs from the game environment. This allows the agent to learn directly from raw visual data, enabling more complex and nuanced strategies.

## Project Structure

- **agent.py**: Contains the implementation of the DCQN agent.
- **network.py**: Defines the neural network architecture.
- **train.py**: Trains the DCQN agent using the Ms. Pac-Man environment.
- **utils.py**: Provides utility functions for video rendering and visualization.

## Requirements

- Python 3.x
- Gymnasium
- PyTorch
- NumPy
- OpenAI Gym

## Usage

1. Install the required packages: `pip install -r requirements.txt`
2. Run `python train.py` to train the DCQN agent.
3. Run `python test.py` to test the trained agent.
4. Use `show_video()` function in `utils.py` to visualize the agent's performance.

## Results

The agent successfully solves the Ms. Pac-Man environment, achieving an average score of over 500 in 100 consecutive episodes.

## References

- [Human-level control through deep reinforcement learning](https://www.nature.com/articles/nature14236)
- [OpenAI Gym Documentation](https://gym.openai.com/docs/)
