# Autonomous Mobile Robots – Fall 2024  

## **LAB-1: Sensor Data Processing**  

In this lab, you'll explore ROS2 components and libraries, focusing on reading and writing sensor data.  

You'll gain an understanding of how middleware like ROS2 facilitates handling processes across both local and remote machines.  

Additionally, you'll learn how to log sensor outputs while controlling actuators to execute different trajectories. Logging is a critical aspect of robotics, as it provides detailed insights into the intended goals, enabling more informed downstream decisions.  

## **LAB-2: Closed-Loop Control**  

This lab introduces a foundational version of the overall control stack, beginning with the implementation of a closed-loop controller.  

The concept of a closed-loop controller has been covered in previous control courses (ME/MTE360 or an equivalent course for non-MME students). Here, you'll implement it without relying on proprietary software like MATLAB.  

A key takeaway from this lab is learning how to compute derivatives and integrals from a continuous stream of incoming data—an essential technique in real-world engineering applications, particularly in control systems.  

You'll also gain experience in applying Object-Oriented Programming (OOP) principles in robotics using Python.  

## **LAB-3: Localization**  

This lab focuses on various estimation methods for localization.  

First, you'll implement a Kalman Filter (KF) to improve localization accuracy and filter out noise from the IMU's acceleration data.  

Next, you'll record a standard trajectory within a maze and use a particle filter to localize the robot.  

## **LAB-4: Path Planning**  

This lab brings together all the components of the system.  

You'll begin by implementing two different path-planning algorithms to navigate the maze. Then, your controller will follow waypoints generated from the planned path, using the localization module for feedback.  

As the robot moves, you'll log its state and the planned waypoints. This data will allow you to analyze and quantify the performance of your system.  
