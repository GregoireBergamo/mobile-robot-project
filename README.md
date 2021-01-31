# mobile-robotics-project

This project was done during the 'Basics of Mobile Robotics' course in the Robtics master curriculum at EPFL. 

A camera takes a photo of an environment consisting of a robot, obstacles and a destination placed randomly, and we use computer vision to detect the different elements. An optimal path for the robot to arrive at the destination while avoiding the obstacles is computed using the A* algorithm. At any time, a new object can be put in the robot's path, and thus it has to use IR sensors in order to avoid the object and get back on its course. The trajectory is always corrected with a Kalman Filter. 

A quick demo video can be seen here : 

![Demo](figures/demo.gif)
