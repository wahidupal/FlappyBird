# Flappy Bird AI

This project demonstrates an AI learning to play the popular Flappy Bird game using the **NEAT (NeuroEvolution of Augmenting Topologies)** algorithm. The project employs **Pygame** for game simulation, **NEAT** for the AI model, and visualization tools to showcase the learning process.

---

## Features

- **AI Training**: Uses NEAT to evolve neural networks for controlling the bird's behavior (e.g., jumping) based on the game state.
- **Game Simulation**: Built with Pygame, the Flappy Bird game simulates the environment for the AI to learn and adapt.
- **Dynamic Visualization**: Displays real-time gameplay with visual indicators of AI decisions and fitness scoring.
- **Configurable Parameters**: Modify NEAT parameters via the configuration file (`config-feedforward.txt`) for experimentation.
- **Generational Evolution**: The AI improves over multiple generations by selecting the best-performing neural networks.

---

## Requirements

### Python Libraries
Ensure you have the following libraries installed:
- `pygame`
- `neat-python`
- `pickle`

To install these, run:
```bash
pip install pygame neat-python
