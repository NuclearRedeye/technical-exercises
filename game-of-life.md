# Conway's Game of Life

The [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

## Rules

The universe of the Game of Life is a two-dimensional grid of cells, each of which is in one of two possible states, _live_ or _dead_. Every cell interacts with its eight _neighbours_, which are the cells that are directly horizontally, vertically, or diagonally adjacent. 

At each _tick_ in time, the following transitions occur:

1.  Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2.  Any live cell with two or three live neighbours lives on to the next generation.
3.  Any live cell with more than three live neighbours dies, as if by overpopulation.
4.  Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the 'seed' of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed — births and deaths happen simultaneously, and the discrete moment at which this happens is called a _tick_. (In other words, each generation is a pure function of the one before.) 

The rules continue to be applied repeatedly to create further generations.

## Task
- [ ] Create a basic implementation of Conway's Game of Life.