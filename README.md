# N-Queens Problem Solutions

This repository contains two algorithms to solve the N-Queens problem: Simulated Annealing and Genetic Algorithm.

## Algorithm 1: Simulated Annealing

The Simulated Annealing approach seeks to find a solution by gradually lowering the "temperature" and exploring the board configuration space.

### Key Concepts:
- **Cost Calculation**: Measures the number of pairs of queens that can attack each other.
- **Annealing Schedule**: The temperature decreases at each step (starting from 4000).
- **Acceptance Probability**: New board configurations are accepted based on a probability determined by the current temperature.

### How It Works:
- Random initial queen placements.
- Iterative process where the system "cools" over time, leading to a solution if one exists.
- Prints board configurations at each step.

## Algorithm 2: Genetic Algorithm

The Genetic Algorithm solves the problem using evolutionary techniques such as selection, crossover, and mutation.

### Key Concepts:
- **Fitness Score**: Measures how many queens are not attacking each other.
- **Selection**: Selects individuals based on their fitness scores to become parents.
- **Crossover**: Combines parents' sequences to create offspring.
- **Mutation**: Randomly changes a queen's position with a certain probability.

### How It Works:
- Starts with a random population of queen placements.
- Evolves the population through selection, crossover, and mutation to find a solution.
- Continues until a solution is found.

