# Grid-World

## created using java

Creates NxM grid-world.
Each grid-world contains 3 types of cells: (i) cell-wall, (ii) cell-grass, and (iii) cell-land.
Each cell has a "cost of traverse": for cell-wall is set Int.MAX_VALUE, for cell-grass is adjustable, and for cell-land is set to 1.

The grid-world may be random (it creates a new one and stores it in a "newRandomLevel.world" file), or upload an existing grid world from a file.

### How to run: 
```
  java GridGenerator
```
generates a random grid-world of dimensions 13x9,

```
  java GridGenerator -d 15 8
```
generates a random grild world of dimensions 15x8,

```
  java GridGenerator -i example_worlds/default.world
``` 
uploads the grid wolrd from file.


### Visualize

![Alt text](world.png?raw=true "Title")
