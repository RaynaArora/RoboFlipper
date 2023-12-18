# RoboFlipper
##Python code that uses Pydrake for a robotic Kuka iiwa arm to perceive, pick up, and flip an object so it lands upright.

Here we present notebooks that set up a simulation environment for the robot to flip both a can and a box from the YCB dataset.

perception + throw.ipynb contains code for the robot to perceive and flip the box.
throw_box_static.ipynb contains code for the robot to flip a box when the box is initialized in a fixed location.
throw_can_static.ipynb contains code for the robot to flip a can when the can is initialized in a fixed location.

The other files help to set up the simulation environment with the table on which the object is flipped and the object to be flipped.
For a more detailed explanation on the techniques used along with the calculations to flip the object, read our paper: RoboFlipper.pdf.
