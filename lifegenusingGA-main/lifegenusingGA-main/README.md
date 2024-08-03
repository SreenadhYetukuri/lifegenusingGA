This Python code is designed to implement a genetic algorithm (GA) for optimizing ambulance routing in emergency situations within a grid-based environment. The primary objective is to efficiently respond to emergency calls by assigning ambulances optimal routes while considering factors such as patient severity, blocked areas, and traffic signals.
The code begins by importing necessary libraries such as **math, random, numpy, and custom modules** related to the **genetic algorithm** implementation (GA.py). These custom modules include functionalities for managing blocks on the grid, routes, populations of routes, and operations for evolving the population using genetic algorithms.

The **generateGrid** function is responsible for creating a grid layout with specified dimensions and populating it with blocks representing clear paths, blocked areas, and traffic signals. This grid serves as the environment in which ambulance routes are optimized.

The **printPop** function allows printing information about the best routes in the population, including details such as the route itself, indices in the grid, fitness, and distance.

The **getRoutes** function retrieves the best routes from the population based on a specified number.

The **start_Genetic_Algorithm** function initializes and evolves a population of routes using a genetic algorithm. It iterates over a specified number of generations to optimize the routes.

The **scheduling_ambulance** function sorts patient calls based on severity and assigns available ambulances routes using the genetic algorithm. It ensures that ambulances are assigned to calls based on patient urgency and the availability of ambulances.

## In the main program section:

1.The grid layout is generated with specified dimensions.
2.Patient calls are defined, including their start and goal positions along with severity levels.
3.Available ambulances are initialized.
4.Ambulances are scheduled based on patient severity, and optimal routes are assigned to them using the genetic algorithm.
5.Finally, the optimal routes for each ambulance are printed along with relevant details.
This code provides a foundation for developing a system to optimize ambulance routing in emergency scenarios, aiming to minimize response time and maximize patient care efficiency within a grid-based environment.
