# Search algorithm 
## - Finding a path from A to destination B
The following code allows you to find a path from source A to destination B on a map.

## Introduction 
The aim of this project is to solve the problem of finding a path from a starting point to a destination. 
The project is implemented in Python and utilizes two search algorithms: the A* algorithm and the Constraint Satisfaction Problem (CSP) approach. 

## Implementation
#### A* algorithm
The A* algorithm is a graph traversal and pathfinding algorithm widely used in various areas of computer science due to its efficiency and effectiveness in minimizing travel distance or time. In this project, the A* algorithm is used to find the shortest path between the source and the destination.

#### Constraint Satisfaction Problem (CSP)
The CSP approach tries to find a path by generating all possible paths and checking if they satisfy a set of constraints. 
In this project, the constraints include:

Total Distance: The path must not exceed a specified maximum distance.
    
Duration Between Intermediate Cities: Each segment of the journey must not exceed a specified maximum duration.
    
## Installation
Clone the repository to your local machine:
Use: 
```bash
git clone https://github.com/lilifee7/KBS_assignment5.git
```

The following cell contains the Python libraries needed to work with the code. They need to be installed in the running environment with e.g:

```bash
pip install pandas
```

```python
import json
import pandas as pd
import matplotlib.pyplot
import heapq
```

## Usage 
If you have cloned the repository to your local machine, the JSON file is already included and loaded.

#### Structure of the code 
##### 1. Imported Libraries
The necessary Python libraries are imported at the beginning of the code.

##### 2. Data Inspection
The code prints the data as it is stored in the JSON file and provides a visualization of the map.

##### 3. A Algorithm Implementation*
To change the cities for which you want to find the path, modify the following lines in the code:

```python
start = 'Blanes'
goal = 'Barcelona'
```
Replace 'Blanes' and 'Barcelona' with the cities you are interested in.

##### 4. CSP Algorithm Implementation
Similarly, for the CSP algorithm results, update the following lines in the code:
```python
start_city = 'Blanes'
goal_city = 'Barcelona'
max_distance = 150000 
max_duration = 90 
```
Replace 'Blanes' and 'Barcelona' with the desired cities. Furthermore adjust max_distance and max_duration, if you want to change the constraints.

## Data
The provided data is a JSON file containing essential information for representing a map. It consists of two main sections:

Cities: Provides the name, address, country, latitude, and longitude of the cities.

Connections: Describes the distance and duration between pairs of cities

## License
You can use VSC program to clone the program for free - see the LICENSE file for details.

[MIT](https://choosealicense.com/licenses/mit/)
