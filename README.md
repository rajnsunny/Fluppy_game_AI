# Fluppy AI Game using NEAT Library

Welcome to Fluppy AI Game! This game utilizes the NEAT (NeuroEvolution of Augmenting Topologies) library in Python to train an AI agent to play the game.

## Game Description

Fluppy AI is a simple 2D game where the player controls a flying character called Fluppy. Fluppy's objective is to navigate through a series of obstacles by jumping over them. The game ends if Fluppy collides with any obstacles or touches the ground. The goal of the AI agent is to learn to play the game effectively and achieve the highest score possible.

## Installation

To run Fluppy AI Game, follow these steps:

1. Clone the repository from GitHub:

```
git clone https://github.com/rajnsunny/Fluppy_game_AI.git
```

2. Navigate to the project directory:

```
cd fluppy-ai-game
```

3. Create a virtual environment (optional but recommended):

```
python3 -m venv venv
```

4. Activate the virtual environment:

```
# On macOS and Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

5. Install the required dependencies:

```
pip install -r requirements.txt
```

6. Run the game:

```
python game.py
```

## NEAT Library

NEAT (NeuroEvolution of Augmenting Topologies) is a popular Python library for implementing neuroevolution, which is a technique to evolve artificial neural networks using genetic algorithms. NEAT is particularly useful for training AI agents without the need for extensive manual tuning or human intervention.

In Fluppy AI Game, the NEAT library is used to train the AI agent to play the game. The NEAT algorithm will automatically generate and evolve neural networks to optimize the AI agent's performance over time.

## NEAT Configuration

The configuration file `config-feedforward.txt` contains the parameters that control the NEAT algorithm's behavior. You can modify these parameters to customize the training process according to your requirements. Some of the key configuration parameters include:

- `pop_size`: The size of the population (number of individuals) in each generation.
- `fitness_criterion`: The criterion used to evaluate an individual's fitness (e.g., maximizing the score in the game).
- `max_fitness_threshold`: The maximum fitness threshold at which the training will terminate.
- `activation_default`: The default activation function for neurons in the neural networks.
- `activation_mutate_rate`: The probability of mutating the activation function of a neuron.
- `conn_add_prob`: The probability of adding a new connection between two neurons.
- `node_add_prob`: The probability of adding a new neuron to the neural network.
- `initial_connection`: Determines how initial connections are created in the neural networks.

Feel free to experiment with these parameters to achieve the desired AI agent's performance.

## Game Controls

- Press the **Spacebar** or **Up Arrow** key to make Fluppy jump.

## Credits

The Fluppy AI Game was developed by me and inspired by Tim. It utilizes the NEAT library, which was created by Kenneth O. Stanley and others.

## License

This project is licensed under the [MIT License](LICENSE).

Enjoy playing Fluppy AI Game and have fun training your AI agent to become a Fluppy champion!
