# Vehicle Simulation


## How to run the simulation


### Prerequisites

Before running the code, make sure you have the following dependencies installed:

- [Python](https://www.python.org/) (version 3.x)
- [pygame](https://www.pygame.org/) (version 2.1.1)
- [matplotlib](https://matplotlib.org/) (version 3.4.3)

Install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Clone the repository:

```bash
git clone https://github.com/Aditya-y9/GeneticAlgorithm.git
cd genetic-algorithm-simulation
```

### Run the simulation:

```bash
python main.py
```

Controls:

Press D to toggle debug mode.
Press P to pause/unpause the simulation.
Enjoy the simulation! Watch as vehicles evolve to navigate the environment.


#### Project to demonstrate Theoretical and Practical Understanding of Genetic Algorithm for ProjectX
<p align="center">
<img src="https://github.com/Aditya-y9/GeneticAlgorithm/assets/122613756/915e2bab-d17b-4fc2-9906-cad83ef72928"
>
</p>

<p align="center">
<strong style="align-text:center">
Under Guidance of College Coding Club CoC.
<strong>
</p>

<ul>
<li>
This is a Python simulation of organisms that eat food and avoid poison.<li>
The organisms are controlled by a set of rules that determine their behavior, such as seeking out food and avoiding poison.<li>
The organisms make decisions based on their current state and the state of their environment.<li>
The organisms are able to learn from their experiences and improve their behavior over time.<li>
The organisms are able to reproduce and pass on their genes to the next generation.<li>
The organisms are able to mutate their genes to create new behaviors.<li>
The simulation is built using the Pygame library, which is a set of Python modules designed for writing video games. 
<li>
The simulation is displayed on a screen
</ul> 

![ui](https://github.com/Aditya-y9/GeneticAlgorithm/assets/122613756/3683e61a-34f7-45f5-92d1-dfe428a4079d)
### <strong style="font-family:courier new">
Basic interface
<strong>
The simulation includes vehicles, food particles, and poison particles. 
The vehicles are controlled by a set of rules that determine their behavior, such as seeking out food particles and avoiding poison particles.


![debug](https://github.com/Aditya-y9/GeneticAlgorithm/assets/122613756/ef7c3305-f426-4fac-abe2-2c8dec864728)

### <strong style="font-family:copperplate gothic">
Vehicle with debug mode on
<strong>


# Genetic Algorithm
DNA List contains 4 genes for each vehicle
1. Food Attractions
2. Poison Repulsions
3. Food Perception
4. Poison Perception

### DNA
DNA is a list of genes that determine the behavior of the vehicle.
Each gene gets randomly assigned a value
The values of the genes determine the behavior of the vehicle.
The values of the genes are used to calculate the forces that act on the vehicle.
Also, the values of the genes are used to determine the range of the vehicle's perception.

At each new generation, the DNA of the vehicle is mutated.

Any two of the genes get mutated by random value between -5 and 5

### <strong style="font-family:courier new">
DNA of a vehicle
<strong>

#### Gene Pool
Gene pool is a list of all the genes of all the vehicles in the population.
The gene pool is used to calculate the average fitness of the population.
The gene pool is also used to select the parents for reproduction.

### <strong style="font-family:courier new">
Gene Pool
<strong>

#### Fitness
Fitness is a measure of how well the vehicle is able to survive in its environment.
Initial health of a vehicle is 0
Health increases when vehicle eats food
Health decreases when vehicle eats poison
Fitness is assumed to be directly proportional to health


### <strong style="font-family:courier new">
Fitness of a vehicle
<strong>

#### Selection
Selection is the process of choosing the parents for reproduction.
The parents are chosen based on their fitness.
The parents with the highest fitness are more likely to be selected for reproduction.
The parents with the lowest fitness are less likely to be selected for reproduction.


### <strong style="font-family:courier new">
Selection of parents
<strong>

#### Crossover
Crossover is the process of combining the genes of two parents to create a new child.
The genes of the parents are combined by randomly selecting a point in the middle of the gene list.
The genes before the crossover point are taken from the first parent.
The genes after the crossover point are taken from the second parent.
The crossover point is chosen randomly for each child.

### <strong style="font-family:courier new">
Crossover of parents
<strong>

It works by creating a new population of vehicles based on the fitness of the previous population.
The fitness of each vehicle is determined by the amount of food it eats and the amount of poison it avoids.
The vehicles with the highest fitness are more likely to be selected for reproduction.

```
Proboablity of selection is proportional to fitness of that organism
```

![generations](https://github.com/Aditya-y9/GeneticAlgorithm/assets/122613756/3c1bcc9e-29e2-416d-9399-4dd682a1aa07)

### <strong style="font-style:italic">
Generations of vehicles
</strong>
The vehicles with the lowest fitness are less likely to be selected for reproduction.
The vehicles with the highest fitness are more likely to pass on their genes to the next generation.
Gene mutation takes place in the next generation.
The vehicles with the highest fitness are more likely to pass on their genes to the next generation.

![graph](https://github.com/Aditya-y9/GeneticAlgorithm/assets/122613756/d170835a-2eb6-4db9-90a1-cf5db6521f35)

### <strong style="font-family:courier new">
Graph showing average health of vehicles over generations
Graph made using Matplotlib
<strong>


## Usage

To run the simulation, simply run the `main.py` file using Python. The simulation will start and run until the user quits the simulation.

## Dependencies

- Python 3
- Pygame

## Installation

1. Install Python 3 from the official website: https://www.python.org/downloads/
2. Install Pygame by running the following command in the terminal: `pip install pygame`
3. Download the `main.py` file from this repository
4. Run the `main.py` file using Python

## Pygame Library

The Pygame library is used extensively in the simulation to handle the graphics and user input. Here are some of the ways that Pygame is used:

1. The Pygame library is used to create a window with a width of 1080 pixels and a height of 720 pixels. This window is used to display the simulation.

2. Pygame is used to handle user input, such as quitting the simulation or toggling debug mode.

3. Pygame is used to draw the vehicles, food particles, and poison particles on the screen. This is done using the Pygame draw functions, such as `draw.circle()` and `draw.line()`.

4. Pygame is used to handle the frame rate of the simulation. The frame rate is set to 15 frames per second using the Pygame `time.Clock()` function.

5. Pygame is used to handle the event loop of the simulation. This loop handles events such as quitting the simulation, toggling debug mode, and adding a new vehicle.

Overall, Pygame is an essential part of the simulation, as it provides the necessary tools for handling graphics and user input. Without Pygame, it would be much more difficult to create a simulation with a graphical interface.
