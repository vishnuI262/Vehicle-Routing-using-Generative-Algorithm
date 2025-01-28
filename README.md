# Vehicle-Routing-using-Generative-Algorithm
This project solves the Vehicle Routing Problem (VRP) using a Genetic Algorithm (GA). The goal is to find the most efficient routes for a fleet of vehicles to deliver goods to various locations while minimising the total distance travelled.

# Problem Overview
The VRP involves optimising the routes of a fleet of vehicles that need to deliver goods to multiple locations. The challenge is to determine the most efficient set of routes that reduces the total distance travelled, ensuring each vehicle starts and ends at the depot.

# Approach
The solution uses a Genetic Algorithm to evolve a population of potential routes. Key steps involved:

### Initialisation: Randomly generate locations and depot.
### Population Generation: Create a population of possible routes.
### Genetic Operations: Apply selection, crossover, and mutation to evolve solutions.
### Fitness Evaluation: Evaluate solutions based on the total distance and route variance (standard deviation).
### Visualisation: Use Matplotlib to visualise the optimal solution and vehicle routes.

Installation
To run this project, install the required dependencies:

"pip install matplotlib deap numpy"

### Usage
Run the script to generate random locations, solve the VRP using the Genetic Algorithm, and visualise the optimal routes:

"python main.py"

### Visualisation
The optimal solution is displayed using Matplotlib, where:

-Locations are marked as blue dots.
-The depot is marked as a red square.
-The routes for each vehicle are shown as lines connecting the locations.

### Conclusion
This project demonstrates how genetic algorithms can be used to solve real-world optimisation problems, such as vehicle routing. It's a practical example of applying evolutionary strategies to logistics and transportation problems.

