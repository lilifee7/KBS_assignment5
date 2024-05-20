# Search algorithm - Fidning a path from A to destination B
The following code allows you to find a path from source A to destination B on a map.

## Introduction 
The aim of this project is to solve the problem of finding a path from a starting point to a destination. 
The project is implemented in Python and utilizes two search algorithms: the A* algorithm and the Constraint Satisfaction Problem (CSP) approach. 
The A* algorithm is used to find the shortest path between the source and the destination. 
The CSP approach is used to find a path that satisfies a set of constraints, ensuring the practicality of the route 
by limiting the total distance traveled and the duration between cities.

## Implementation
#### A* algorithm
The A* algorithm is a graph traversal and pathfinding algorithm and used widely used in various areas of computer 
science due to its efficiency and effectiveness in minimizing travel distance or time.
In this code we use it to find the shortest path between the source and the destination. 

#### Constraint Satisfaction Problem (CSP)
the CSP algorithm tries to find a path by generating all optional paths and checking if they satisfy a set of constraints. 
In this project, the constraints include:

    Total Distance: The path must not exceed a specified maximum distance.
    Duration Between Intermediate Cities: Each segment of the journey must not exceed a specified maximum duration.
    
## Installation
Clone the repository to your local machine:
Use: 
```bash
git clone 
```

The following cell contains the Python libraries needed to work with the code. They need to be installed in the running environment with e.g:

```bash
pip install pandas
```

```python
import json
import pandas as pd
import matplotlib.pyplot as plt
import heapq
import math
```

## Usage 


## Data
The provided data is a JSON file containing essential information for representing a map. It consists of two main sections:

    Cities: Provides the name, address, country, latitude, and longitude of the cities.
    Connections: Describes the distance and duration between pairs of cities

## License
You can use VSC program to clone the program for free - see the LICENSE file for details.

[MIT](https://choosealicense.com/licenses/mit/)
