## **Introduction** ##
We propose to make an 1-Dimensional Inverted Pendulum which is a pendulum having its mass above its pivot point. An inverted pendulum is inherently unstable, and must be actively balanced by moving the pivot point horizontally as part of a feedback system.

## **Problem Statement** ##
The problem involves a cart, able to move backwards and forwards, and a pendulum, hinged to the cart at the bottom of its length such that the pendulum can move in the same plane as the cart, shown below. That is, the pendulum mounted on the cart is free to fall along the cart's axis of motion. The system is to be controlled so that the pendulum remains balanced and upright, and is resistant to a step disturbance.


## Proposed Solution ##
To mount the pendulum following can be used

  * cart (preferred), or
  * sliding platform,
  * rotating platform


To obtain data concerning the angle of rotation of the pendulum, potentiometer, accelerometer and gyroscopes are the possible options. As of now we will use potentiometers considering the convenience. Once we are successful with this mechanism we might use inertial sensors if required.

## Control: ##
We will use the PID controller to stabilize the system. The controller design would be trail and error to start with and we aim to apply formal methods if are able to keep ourselves on track.  Standard control equation of PID :
The PID control we are planning to stablize our pendulum

For processing we will use_AVR Microcontrollers_.

## Timeline: ##
> We are planning to do all the major reading stuff and collect necessary details about the problem during first two weeks of may when we are at home. And then seriously engage ourselves in project from may 20. We are expecting to ready our first model using potentiometers providing satisfactory results by 15th of june. Then we can make it better.

### Real-Life Applications utilizing Principle of Inverted Pendulum ###

  * Missiles and rockets
  * Self balancing robots
  * Future Transport Vehicles like Segways, jetpacks etc

## Demonstration: ##
We expect our final robot to be capable enough even to balance the pendulum even when delibrately disturbed. So, we can demostrate it by showing How the cart balances the pendulum. Else we can make this more fancy by making our robot compete against a volunteer ...who can balance stick for greater time.?
who can balance the stick even when disturbed.?



Mentor - Manav Kataria

