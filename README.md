# Robotic-Arm-simulation

## Abstract

A simulation of Robotic Arm in Gazebo Environment, made 3-D model with SolidWorks and controlled by ROS and Moveit framework.

![Final](https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/finalarm.png)

## Motivation

From manufacturing to automotive to agriculture, industrial robotic arms are one of the most common types of robots in use today.<br>
Robotic arms are fast, reliable, and accurate and can be programmed to do an infinite number of tasks in a variety of environments. They are used in factories to automate execution of repetitive tasks, such as applying paint to equipment or parts; in warehouses to pick, select, or sort goods from distribution conveyors to fulfill consumer orders; or in a farm field to pick and place ripe fruits onto storage trays. And as robotic technologies develop and industrial environments become more connected, the capabilities of robotic arms expand to enable new use cases and business operation models.

## Mechanical Aspects 

3-D model of robotic arm was made in Solidworks part by part.

Base of the arm-

<p align="center">
    <ing src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/base.png"/></p>

Links of the arm-

<p align="center">
    <img src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/link1.png"/></p>

<p align="center">
    <img src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/link2.png"/></p>

<p align="center">
    <img src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/link3.png"/></p>

<p align="center">
    <img src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/link4.png"/></p>

Gripper-

<p align="center"><img src="https://github.com/Aviral2002/Robotic-Arm-simulation/blob/main/Images%20And%20VIdeos/gripper.png" /></p>

## Software Aspects

### SolidWorks

SOLIDWORKS is used to develop mechatronics systems from beginning to end. At the initial stage, the software is used for planning, visual ideation, modeling, feasibility assessment, prototyping, and project management. The software is then used for design and building of mechanical, electrical, and software elements.

### ROS (Robot Operating System)

ROS is an open-source, meta-operating system for your robot. It provides the services you would expect from an operating system, including hardware abstraction, low-level device control, implementation of commonly-used functionality, message-passing between processes, and package management.

### MoveIt!

MoveIt! is a framework package of Ros. The basic task of the MoveIt! system is to provide the necessary trajectories for the arm of a robot to put the end effector in a given place.

## Applications

Robotic arm can be used for multiple industrial applications, from welding, material handling, and thermal spraying, to painting and drilling. With some modifications they can be used for servicing nuclear power stations, welding and repairing pipelines on the ocean floor, remote servicing of utility power lines, or cleaning up radioactive and other hazardous wastes.
Another example where Robotic-arm can be used is in the auto-manufacturing industry. Robots have been a boom to the auto-manufacturing industry. Most industrial robots work in auto assembly lines, putting cars together.Robots can do a lot of this work more efficiently than human beings because of its speed and relative precision. It also will significantly reduce worker injuries, including repetitive stress injuries. Additionally, the robot will turn out a more consistent product at a significantly cheaper cost than can humans.

## Limitations

A this is a simulation, real model of the arm will have to be made with high precision and have a high chance of inaccuracy.<br>Also the arm moves in rough trajectories with very less precision and the weight distribution and weight limit wil also a problem an weight of components and external weight could increase the stress on links and motors, and these situations could create a big problem in real life model.

## Improvements

Our aim would be to to improve the trajectory of the arm using planners in MoveIt and control it to pick various objects in simulation. And to make an interactive remote control for the arm.

## Team Members

1. [Ajay Sonwani](https://github.com/ajaysonwani)
2. [Aviral Jain](https://github.com/Aviral2002)
3. [Harsh Kumar](https://github.com/Harshkr03)
4. Saksham Jaiswal

## Mentors

1. Diwahar
2. Harshini S.

## References

1. [For installation of ROS noetic](http://wiki.ros.org/noetic/Installation/Ubuntu)
2. [For installation of MoveIt](https://moveit.ros.org/install-moveit2/source/)
4. [For installation of Gazebo](https://dev.px4.io/v1.10_noredirect/en/simulation/gazebo.html)

