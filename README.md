# Mars Rover using DDD

## About
The Purpose of this repo is

Develop an API that moves a rover around on a grid.
 You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
 - The rover receives a character array of commands.
 - Implement commands that move the rover forward/backward (f,b).
 - Implement commands that turn the rover left/right (l,r).
 - Implement wrapping from one edge of the grid to another. (planets are spheres after all)
 - Implement obstacle detection before each move to a new square.
   If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point and reports the obstacle.


Clone the repository and run.

## Run

Go to the program directory and Run

```ruby
ruby lib/mars_rover.rb rover_input.txt
```

To run specs

```ruby
rspec
```


**NOTE: input file is included in the repository as rover_input.txt.
