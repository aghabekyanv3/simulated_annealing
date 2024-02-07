# Simulated Annealing Optimization Project README

## Overview
This project explores the application of simulated annealing (SA) to optimize an objective function within a circular grid domain. It aims to demonstrate the algorithm's capability in navigating complex solution spaces effectively by adjusting parameters like initial temperature.

## Features
- **SimAnn Class**: A Python class designed for simulated annealing optimization.
- **Parameter Tuning**: Methods for dynamically adjusting initial temperature, cooling rate, and iterations to optimize performance.
- **Visualization**: Functions to visualize the optimization process and outcomes, offering insights into the algorithm's behavior.

## Implementation
- **Data Generation**: Initializes the optimization landscape based on given dimensions and seed.
- **Performance Evaluation**: Calculates the current state's performance to guide optimization.
- **Acceptance Probability**: Determines the likelihood of accepting new solutions to escape local minima.
- **Objective Function & Move Proposal**: Guides the search for optimal solutions within problem boundaries.

## Experimentation
- Analyzed algorithm performance across various settings, focusing on the impact of initial temperature and dimensionality on convergence.
- Recorded and visualized acceptance probabilities to gain insights into the optimization landscape's complexity.

## Usage
To run the simulated annealing optimization, adjust the parameters in the `simulated_annealing` method within the SimAnn class. Use the visualization functions to analyze the algorithm's performance and parameter influence.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

## Concluding Thoughts
This project underlines the effectiveness of simulated annealing in complex optimization problems, highlighting the importance of parameter tuning and adaptive strategies for enhanced performance.

---

For more detailed information on the project structure and implementation, please refer to the provided Python scripts and visualization outputs within the repository.
