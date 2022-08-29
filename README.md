# 3-RRS_chains_Climbing_Parallel_Robot
Final Project of Course 6614 ADV Topics in Robotics

The project is applying for a patent, the patent application number is：

## Project Presentation in Youtube
https://youtu.be/2ys7bdeC44U

## The schematic diagram of the robot leg
Since the robot leg structure is a planar four-bar linkage and the axis of the hip pitch actuator and the axis of the knee actuator are collinear, we can achieve gravity balance with two springs as follows:

<p align="center">
    <img src="https://github.com/Qincheng-Sheng/3-RRS_chains_Climbing_Parallel_Robot/blob/main/pictures/structure.png" alt="system" width= "250">
</p>


## Robot Leg Rotation Simulation
In below figures, the red line represents the spring, the green line represents the rotating link, and the red dot means the joint that needs to be fixed on the robot body. Then, by doing simulation we find that different motion patterns can be realized.

Rotating joint 1 makes the upper leg swing, and rotating joint 2 makes the lower leg swing. If rotating these two joints at the same time would realize the actions of standing and squatting. Rotating joint 3 will make the robot legs swing left and right, so that the robot legs are able to turn left or turn right.

Hip pitch and knee Rotation. 
<p align="center">
        <img src="https://github.com/Qincheng-Sheng3-RRS_chains_Climbing_Parallel_Robot/blob/main/pictures/curve.gif" alt="system" width= "350" />
        <img src="https://github.com/Qincheng-Sheng/3-RRS_chains_Climbing_Parallel_Robot/blob/main/pictures/straight.gif" alt="system" width= "350" />
</p>
 
Hip roll and Mixed Rotation.
<p align="center">
        <img src="https://github.com/Qincheng-Sheng/3-RRS_chains_Climbing_Parallel_Robot/blob/main/pictures/curve2.gif" alt="system" width= "350" />
        <img src="https://github.com/Qincheng-Sheng/3-RRS_chains_Climbing_Parallel_Robot/blob/main/pictures/straight2.gif" alt="system" width= "350" />
</p>
