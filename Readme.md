Ruby - Robot Test
===================

- - - - 

# Rules #

The application is a simulation of a toy robot moving on a square tabletop, of dimensions 5 units x 5 units.

There are no other obstructions on the table surface.

The robot is free to roam around the surface of the table, but must be prevented from falling to destruction. Any   movement that would result in the robot falling from the table must be prevented, however further valid movement commands must still be allowed.

## Valid Commands ##

PLACE X,Y,F

MOVE

LEFT

RIGHT

REPORT

## How to use ##

curl [file containing commands] | ruby simulator.rb
