# RoboFlipper
This was the final project for MIT's Robotic Manipulation class (6.4212) by Aarush Gupta and Rayna Arora.

Here we present Python notebooks that use Pydrake to make a robotic Kuka iiwa arm to perceive, pick up, and flip an object so it lands upright. It is demonstrated in the simulation environment. We achieve this on a box and a can from the YCB dataset.

[perception + throw.ipynb]("perception + throw.ipynb") contains code for the robot to perceive and flip the box.
[throw_box_static.ipynb](throw_box_static.ipynb) contains code for the robot to flip a box when the box is initialized in a fixed location.
[throw_can_static.ipynb](throw_can_static.ipynb) contains code for the robot to flip a can when the can is initialized in a fixed location.

The other files help to set up the simulation environment with the table on which the object is flipped and the object to be flipped.
For a more detailed explanation on the techniques used along with the calculations to flip the object, read [our paper](RoboFlipper.pdf).

We also include videos of the robot successfully flipping the box with and without perception.
