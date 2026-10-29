**Regional Bus Route Navigation System**
 **Project Description**

The Regional Bus Route Navigation System is a C++ console-based application designed to represent bus routes between different places and calculate routes based on distance.

The project uses an adjacency matrix to represent connections between places and implements graph algorithms to explore locations and find the shortest and longest simple routes.

** **Objectives****
To represent regional bus routes using a graph.
To store connections and distances using an adjacency matrix.
To find reachable places using Breadth-First Search (BFS).
To calculate the shortest route using Dijkstra's algorithm.
To calculate the longest simple route using DFS and backtracking.
** **Places Included*****
Sangamner
Ghulewadi
Loni
Shirdi
Rahata
Rajapur
⚙️ Technologies Used
Programming Language: C++
Data Structure: Graph
Graph Representation: Adjacency Matrix
Algorithms: BFS, Dijkstra's Algorithm, DFS and Backtracking
IDE: Visual Studio Code
✨** **Features****
Display all available places.
Display direct routes and sample distances.
Find reachable places from a selected location.
Find the shortest route between two places.
Find the longest simple route between two places.
Interactive menu-driven interface.
 **Algorithms Used**
1. Breadth-First Search (BFS)

BFS explores connected places level by level and identifies reachable locations.

2. Dijkstra's Algorithm

Dijkstra's algorithm calculates the minimum-distance route between a source and destination.

3. Depth-First Search (DFS) with Backtracking

DFS explores possible routes without repeating places. Backtracking is used to find the longest simple route between the selected locations.

 **How to Run the Project**
Install a C++ compiler such as GCC.
Clone or download this repository.
Open the project folder in Visual Studio Code.
Open the terminal.

Compile the program:

g++ main.cpp -o main

Run the program:

./main

On Windows PowerShell, use:

.\main.exe
 **Sample Output**
REGIONAL BUS ROUTE NAVIGATION SYSTEM

1. Display All Places
2. Display Direct Bus Routes
3. Find Reachable Places using BFS
4. Find Shortest Route
5. Find Longest Simple Route
6. Find Both Shortest and Longest Routes
7. Exit

Example shortest route from Sangamner to Shirdi:

Sangamner -> Loni -> Shirdi
Total Distance: 45 km

 **Future Scope**
Integrate real-world road distances.
Add a graphical user interface.
Include actual bus schedules and timings.
Integrate GPS-based location tracking.
Develop a web or mobile application.
