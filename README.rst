RaspBillard
===========
The RaspBilliard is Low-cost Virtual Realistic Billiard Simulator, 
running on Raspberry Pi

Acknowledgements
================

0.  **A modified copy of the project Copyright (c) 2016 Utthawut Bootdee**
    see https://github.com/utthawut/RaspBilliard

Development of this project would not have been possible without following document and library. 

1.  AN EVENT-BASED POOL PHYSICS SIMULATOR http://web.stanford.edu/group/billiards/AnEventBasedPoolPhysicsSimulator.pdf  

2.  POOL PHYSICS SIMULATION BY EVENT PREDICTION II: COLLISIONS http://web.stanford.edu/group/billiards/PoolPhysicsSimulationByEventPrediction2Collisions.pdf  

3.  pi3d <https://github.com/tipam/pi3d>  


Dependencies
============
- pi3d
- numpy

Usage
=====

At command prompt

$ python3 main.py

control keys

camera points at cue ball
w. rotates upward
s. rotates downward
a. rotates leftward
d. rotates rightward
i. moves nearer
o. moves away
k. increases cue impulse
l. reduces cue impulse

down.  + back spin
up.    + forward spin
left.  + left spin
right. + right spin

f. draws cue trajectory line
g. plays shot

esc. quit game

Known issues
============

- when cue ball goes into pocket its trajectory moves to floor level so
  it no longer interacts with other balls and the trajectory line is drawn
  on the floor
