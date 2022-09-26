# Welcome

This will be the home for my EE 300W project, **Collision Avoidance Quadcopter**

## Introduction

The goal of this project is to recreate a typical 4 propeller UAV but give it the capabilities to avoid obstacles and collsions in its path. This will be done by configuring the flight controller to react to inputs from ultrasonic sensors mounted on the frame of the quadcopter. The build will consist of generic ESCs, 3 phase motors, a frame, an Arduino Uno as the flight controller.

![Quadcopter1](https://github.com/sameerkhan7/Collision-Avoidance-Quadcopter/blob/main/quadcopter1.jpg)
![Quadcopter2](https://github.com/sameerkhan7/Collision-Avoidance-Quadcopter/blob/main/quadcopter2.jpg)

## Progress

As the semester came to an end, we came up with a fucntioning design for a quadcopter. It relied on 4 brushless motors as the propeller motors with 4 essc controlling them. We used an Arduino as aour main microcontroller with all of the code that was run on it available in the repo. We used a poer distribution board to distribute power among the motors and arduino from our 12V battery source. An IMU is also installed to allow for our motional control and inputs so we can stabilize accordingly.   

![Labeled Quadcopter](https://github.com/sameerkhan7/Collision-Avoidance-Quadcopter/blob/main/quadcopterLabeled.png)

This is the design we currently have. Everything is labeled accordingly.

We also created a schematic to detail the electrical components and hwo they interact:

![Electrical Schematic](https://github.com/sameerkhan7/Collision-Avoidance-Quadcopter/blob/main/quadcopterSchematic.png)


## Results

We tested our design but as the class quickly approached its end, our collision avoidance system never came to fruition. The brunt of this project was focuesed into making this contraption fly and adjusitng the PID controls of the code to allow for smoothing ascent and flying.

This [video](https://www.youtube.com/watch?v=0BLUjkkE03M&t=1s&ab_channel=SameerKhan) details our progress in pairing and reading controls from our controller and seeing the outputs that the quadcopter would calculate without allowing it to fly. Most of these tests went very well. We were seeing some issues with the gyroscopic readings of the IMU but nothing we knew how to fix until we fully tested the system

Our outdoor testing [video](https://www.youtube.com/watch?v=fZN6v_t0DUQ&ab_channel=SameerKhan) details the majority of our issues. When we tried to ascedn with the quadcopter, there seemed to be a large issue with the balancing and PID control of the robot. We presumed that the robot was continuously overcorrecting its balance and causing the large oscillations in the pitch of the robot. Sadly, the class came to an end before we could flesh out a plan for fixing this and progress halted here. 

If any more updates occur they will be added below but we learned a lot about controlling an aerial robot and the work that goes into designing and creating software for this sort of project and would love to continue this project time permitting.

