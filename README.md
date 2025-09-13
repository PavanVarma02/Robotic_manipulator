
Simulation of a simple robotic arm to perform pick-and-place tasks.

The manipulator is created in Matlab with the Robotics Toolbox.  
A ROS state-machine, running locally or remotely, instructs the robot to move to the position of the target object; the arm reaches the desired location by means of a computed-torque controller, picks the item and eventually places it where desired with fair precision.
