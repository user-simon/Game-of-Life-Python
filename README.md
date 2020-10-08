# An implemenation of Conway's (R.I.P) Game of Life in Python.

Game of Life implementation with a randomized initial grid state and drawn using TKinter.

![gol](https://i.imgur.com/H2IqvIF.gif)

Settings are placed at the top of the file for tinkering.

## Bitwise stuff
Typically, Game of Life grids are stored in a 2D bool array but I decided to store it in an array of integers wherein one bit represents one cell and different bitwise operations are used to access specific cell data. This *could* be more efficient than using a 2D boolean array, I wouldn't know. It's a lot more fun, however. 
