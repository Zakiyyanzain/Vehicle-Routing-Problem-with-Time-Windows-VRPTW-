# Vehicle-Routing-Problem-with-Time-Windows-VRPTW
Vehicle Routing Problem
📌 Introduction
This problem aims to find the optimal route for multiple vehicles (in this case, buses) to visit multiple locations (pick-up and drop-off points) considering time and capacity constraints.

🧠 Method
1. Initialization and Data Preparation
2. Creating the Routing Model
3. Defining the Distance Function
4. Adding Constraints
5. Defining the Objective Function and Search Parameters
6. Running the Solver and Displaying the Solution

📊 Result & Analysis
Example output if a solution is found:
bus route 1: [0, 0]
bus route 2: [0, 2, 0]
bus route 3: [0, 1, 3, 4, 0]

0 is the depot (start and end point).
Each array represents the sequence of visits for each bus.

🔍 Interpretation:
If a solution is found: The code will display the route for each bus, including the order of the points visited.
If no solution is found: The code will display the message:
No valid solution found.
