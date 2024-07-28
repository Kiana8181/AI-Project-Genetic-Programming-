# AI Project: Genetic Programming for Symbolic Regression

## Overview
This project implements a Genetic Programming algorithm from scratch to perform symbolic regression. The goal is to find a mathematical expression that best fits a given set of input-output pairs. The project consists of several key components, including the representation of individuals (chromosomes), population management, genetic operations, and the training algorithm.

## Project Structure
- **Chromosome Class**: Represents an individual in the population, containing methods for generating and evaluating mathematical expressions.
- **Population Class**: Manages a population of individuals, providing methods for creating and evolving the population.
- **Algorithm Class**: A wrapper class that uses the Population class to train a population of individuals using the genetic algorithm.

## Key Features
- **Full and Grow Methods**: Generate new individuals using the full and grow methods of tree generation.
- **Fitness Calculation**: Evaluate individuals based on how well they fit the given input-output pairs.
- **Genetic Operations**: Includes selection, crossover, mutation, and replacement operations to evolve the population.
- **Parse Tree Generation and Plotting**: Generate and plot parse trees for visualizing the mathematical expressions.

## Implementation Details
- The genetic programming algorithm is coded from scratch.
- Symbolic regression is performed to find mathematical expressions for two functions:
  - \( f(x) = x^2 + 2x \)
  - \( f(x) = \exp(\sin(x)) + x \)

## Dependencies
- Python libraries: `math`, `warnings`, `random`, `numpy`, `sympy`, `matplotlib`, `pydot`

## Usage
1. **Initialize Parameters**: Set up the parameters for the genetic programming algorithm, including population size, maximum depth of individuals, function and terminal sets, and number of iterations.
2. **Define the Function and Generate Data**: Define the target mathematical function and generate corresponding input-output data pairs.
3. **Initialize and Train the Population**: Initialize the population and train it using the genetic programming algorithm.
4. **Evaluate and Plot Results**: Evaluate the best individual and plot the results to visualize the fit of the mathematical expression to the data.

## Results
- The best individual and its fitness value are printed during the training process.
- Parse trees for the best individuals are generated and plotted.

## Live Demo
Check out the live demo of the project [here](https://kiana8181.github.io/AI-Project-Genetic-Programming-/).

## Conclusion
This project demonstrates the implementation of a Genetic Programming algorithm for symbolic regression, showcasing the evolution of mathematical expressions to fit given data.
