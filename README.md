# Self-driving Cars project from Luo Yingjie
Neuroevolution is a powerful approach to machine learning and artificial intelligence that uses evolutionary algorithms to evolve neural networks.

This project contain a neuro-evolution library that allows you to easily use [NeuroEvolution](https://en.wikipedia.org/wiki/Neuroevolution) in self-driving game.

In this project, we have applied GeneticEvolution to game self-driving cars.

![Alt text](neuroevolution.png?raw=true "Neuro-evolution")

Evolutionary algorithm uses mechanisms inspired by biological evolution, such as reproduction, mutation, recombination, and selection.
Candidate solutions to the optimization problem play the role of individuals in a population, and the fitness function determines the quality of the solutions.
Evolution of the population then takes place after the repeated application of the above operators.

The project is developed with no external libraries.

## Brief Introduction
The library is in the `neuroevolution` folder. The library is composed of 3 main classes:
- `NeuralNetwork`: This class represents the required Artificial Neural network.
- `GeneticEvolution`: This class represents the Genetic Evolution Algorithm.
- `PopulationHandler`: This class represents the genetic population.
- `PopulationItem`: This class represents the item in population.

![Alt text](self-driving.png?raw=true "Self driving car")
