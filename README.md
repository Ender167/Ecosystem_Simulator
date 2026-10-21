Unity project designed to simulate the interactions between various species over time. Structured as a concurrent multi-agent system whose environment is shared, continuous, non-markovian and non-episodic.

# Overview
Population change is modeled through genetic algorithms:
* Each agent has a fitness score defined as the weigthed sum of all available properties;
* Roulette wheel selection based on fitness for reproduction candidate selection;
* Uniform crossover with creep mutation for generating the offspring;

Agent communicate through peer-to-peer. Communication events occur between:
* Animal and plant agents;
* Carnivores and other animal agents;
* Same species animals;

For an overview of the multi-agent system, check the [following](_documentation/EcosystemOverview.pdf).

For a formal analysis of the environment, agents and communication model, check the [following](_documentation/EcosystemPAGES.pdf).

# Features
* The simulation environmet is a 3D space in which agents act independently using a 3-state finite state machine whose transitions are dependent on each individual agents' properties;
* The application supports the creation of agents representing different competing species (herbivores, carnivores, plants) and configuration of 16 properties which define how an agent explores, feeds and reproduces within the system;
* The application supports changing the rendering speed of the simulation by up to 6x the speed;
* The application allows the change in point of view at any time during the simulation by pressing TAB on the keyboard and orienting the camera using the mouse.

# How to run
The project requires Unity version 2022.3.4f1 or later. Open through Unity Hub and play through the editor.

# Showcase

<img width="1920" height="904" alt="image" src="https://github.com/user-attachments/assets/bd803106-114b-4bbf-94b8-388cc7d353d3" />
