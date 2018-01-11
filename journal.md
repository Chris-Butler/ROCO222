# ROCO222
## Lab 2 ##

In the second lab we started to build our DC motor (version 1). We made the commutator and then wrapped the copper wire round, getting 118 windings.
We built the supports but had some problems with the polar direction of our magnets as it would affect whether or not our shaft would rotate.
We set up two brushes made from copper tape to stay in contact with our commutator when power was applied.


[Working DC Motor](https://www.instagram.com/p/BZ9pTwrhgyO/?hl=en&taken-by=robot_butler1 "Instagram")

## Lab 3 ##

We created an optical encoder using cardboard with a wedge missing for the rotating disk and stuck it on the end of the pin we were using as part of the shaft.
We then souldered an LDR and an LED to a small piece of board leaving enough space to place the roatating disk inbetween.
Unfortunately our encoder ended up breaking so we didn't manage to calculate the algular velocity.

## Lab 4 ##

During this lab we were supposed to control our second motor design with the arduino. After numerous issues with our designs being too big to print we ended up spending too long trying to fix our designs and having to move on to the next lab due to time restrictions (we had problems where the dimensions would cancel any adjustments upon saving).
We had planned to create a design using three lots of windings as the current design would not produce as much torque when the windings were vertical, i.e. away from the brushes.
We were also planning on increasing the number of windings as this would improve the speed of our motor, from the equation B=µNI/l.

## Lab 5 ##

The first step for stepper motors was to control their movement using the arduino. [Servo Control 1](https://www.instagram.com/p/Bd0GCOEjIaW/)
[Servo Control 2](https://www.instagram.com/p/Bd0GAmHj-hB/)
[Servo Control 3](https://www.instagram.com/p/Bd0F-_sDzwl/)
[Servo Control 4](https://www.instagram.com/p/Bd0F87jjSMd/)
[Servo Control 5](https://www.instagram.com/p/Bd0F7S-DDTa/)

From the images above you can see that we used the arduino to set the servo motor to different modes: full-step, double-step, half-step and micro-step.
Below is a video of us controlling the servo motors using the arduino board.

[Controlling servo's using arduino](https://www.instagram.com/p/Bdz1pbJDdxg/)

## Lab 6 ##

With our first design of the robot arm we were told that it would not work as there were too many weak points and that it would not be able to be 3D printed.
The second design we got the design right but were told that we could get rid of some of the materials without losing any of the strength in each piece, so that is what we did for the third design.

Originally, we opted for a four-motor arm to provide more directions of movement but the design became too complex and would not be possible to 3D print.
Our final design now has just two directions of movement to simply the design whilst still being able to perform the required tasks.

We then started to use ROS to connect our arm to a simulation software so it would move the servos in time with the simulation.
[Simulation Code](https://www.instagram.com/p/Bd0Iv7zDqGz/)
[Start of Simulation Model](https://www.instagram.com/p/Bd0I1MujoC0/)
