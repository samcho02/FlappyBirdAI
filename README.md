# Flappy Bird AI using NEAT
A simple Flappy Bird AI that utilizes NeuroEvolution of Augmenting Topologies (NEAT) method. NEAT is an efficient artificial neural model, which can outperform other methods when given a reinforcement learning task such as double pole balancing task. This AI strives to create population of "Flappy Birds" to survive the longest over the course of multiple generations. When given over 100 population size, the AI seemed to beat the game within 2 generations, given the game is considered to be a simple task. The Flappy Bird is created with PyGame module.

## Disclaimer
I do not own this project and all of the rights are reserved to Tech with Tim. It is entirely for educational / record purposes for my future projects.

## Example
![Screenshot 2024-01-08 at 6 35 05 PM](https://github.com/samcho02/FlappyBirdAI/assets/100737807/08c14225-0f26-4361-8470-402391a296fd)

![image](https://github.com/samcho02/FlappyBirdAI/assets/100737807/efd23eba-395e-44ea-88ef-19a3032e630b)

## NEAT Configurations
Here are the parameters used in this project for the configuration file of NEAT.
- Inputs: Bird Y, Top Pipe, Bottom Pipe
- Outputs: Jump controls
- Activation Function: tan(H) → squishes values b/w -1 or 1
- Population Size: 50
- Fitness Function: distance (furthest)
- Max Generations: 30

## References
- Tech with Tim: https://youtu.be/MMxFDaIOHsE?si=d6G7WBNQafXwCLuN 
- NEAT Documentation: https://neat-python.readthedocs.io/en/latest/config_file.html
- “Efficient Evolution of Neural Network Topologies”: https://nn.cs.utexas.edu/downloads/papers/stanley.cec02.pdf
