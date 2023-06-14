# Akade
A game of cubes needs to be packed according to their identical colours

```python
import random

# Define the colors
colors = ["red", "green", "blue", "yellow", "purple"]

# Define the size of the grid
grid_size = 5

# Create a list of lists to represent the grid
grid = [[None for _ in range(grid_size)] for _ in range(grid_size)]

# Fill the grid with random colors
for row in range(grid_size):
    for col in range(grid_size):
        grid[row][col] = random.choice(colors)

# Print out the grid
for row in range(grid_size):
    for col in range(grid_size):
        print(grid[row][col], end=' ')
    print()
```
 
