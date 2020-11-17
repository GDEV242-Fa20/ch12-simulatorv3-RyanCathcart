Project: foxes-and-rabbits-v2
Authors: Michael Kölling and David J. Barnes
Modified by: Ryan Cathcart

This project is part of the material for chapter 10 of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Sixth edition
   David J. Barnes and Michael Kölling
   Pearson Education, 2016

A predator-prey simulation involving foxes and rabbits in
an enclosed rectangular field.

This is the first version of the simulation. This version
does not use inheritance.

How to start:
    Create a Simulator object.
    Then call one of:
        + simulateOneStep - for a single step.
        + simulate - and supply a number (say 10) for that many steps.
        + runLongSimulation - for a simulation of 500 steps.

- **Exercise 12.45** Moved the age field from Fox and Rabbit to Animal. Initialized
it to zero in the constructor. Provided accessor and mutator methods for it and
used these in Fox and Rabbit rather than in direct accesses to the field. Made
sure the program compiles and runs as before.
- **Exercise 12.46** Moved the canBreed method from Fox and Rabbit to
Animal, and rewrote it as shown in Code 12.8. Provided appropriate versions of
getBreedingAge in Fox and Rabbit that return the distinctive breeding age values.
- **Exercise 12.47** Moved the incrementAge method from Fox and Rabbit to
Animal by providing an abstract getMaxAge method in Animal and concrete
versions in Fox and Rabbit.
- **Exercise 12.48** Moved the breed method to Animal.
- **Exercise 12.51** Created a Bear Class. Bears age, move, eat only foxes 
(rabbits must not be worth it to the bear!), and die. My goal was to have a 
bigger, more 'robust', and rarer type of animal that can last a while before 
needing to eat again.