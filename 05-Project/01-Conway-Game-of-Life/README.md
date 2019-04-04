# John Conway's Game of Life

Today you'll build a game, the [Game of
Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) by John Conway.
It's a [zero-player game](https://en.wikipedia.org/wiki/Zero-player_game).

You will reuse a lot of Python's elements that you've learned previously. We
give you some guidelines but no hard fixed rules, you're free to go the
direction you want as long as you have a working implementation at the end of
the day!

This is a project, so **team work is highly recommended!**


## Guidelines

### 1. Build and display a grid
You should first make sure you can display a grid on your screen. We're using a
50 by 35 grid but feel free to choose a size that will fit well on your screen.

We will use the console to display the grid. We'll use `*` to represent living
cells and `.` for when there is no cell. (You're free to choose anything else
you want by the way).

**This is the way we want to represent the grid to the user, but how will you
store it in your program?**

Our first implementation will initialize the grid at random, you'll have to
make sure it has enough points with positive values.

### 2. Access a single element of the grid
* How can you access the value of a single element of the grid?
* How about updating its value?
* How can we access the neighbors of a point?
* How can we update a point based on its neighbors values

### 3. Update your grid with time
* Build the game of life!

## Improvements
* Add ability to load specific patterns
* Keep track of the game state with time (value of every point at every time), how would you do that?
* Add some colors! In particular, change the color of cells has their life spans increases
