# Grid-World
Creates NxM grid-world.
Each grid-world contains 3 types of cells: (i) cell-wall, (ii) cell-grass, and (iii) cell-land.
Each cell has a "cost of traverse": for cell-wall is set Int.MAX_VALUE, for cell-grass is adjustable, and for cell-land is set to 1.

The grid-world may be random (it creates a new one and stores it in a "newRandomLevel.world" file), or upload an existing grid world from a file.

Visualizes the wold as:
![alt text](https://raw.githubusercontent.com/ageorgara/Grid-World/master/world.png)
