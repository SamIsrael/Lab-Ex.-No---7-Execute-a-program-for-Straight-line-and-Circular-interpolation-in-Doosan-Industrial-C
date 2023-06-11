# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/bf34c611-fcdb-43f7-a9c0-245eb9eddd91)

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/d7a0c1c9-0c71-49b4-a9a9-8d34050fdbf5)

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/c4cfeb12-d785-421f-aa13-49a3105ad6b7)

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/62424065-62f2-4fa7-9cfd-398b117b89bb)

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/740d46d1-bd52-4ee6-a978-550da73a38ba)


### Linear Interpolation

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/86986a97-f9ab-4fed-be56-c746a12b7f6f)








### Circular Interpolation

![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/2e489dc1-38dd-41a9-9a9e-264c327f659c)

## Output

### Linear Interpolation
![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/9c4ce457-da11-4528-b7cd-58ea5b8ab71f)

### Circular Interpolation
![image](https://github.com/SamIsrael/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118707037/b75705db-8809-496d-a7d7-f926c7d5d483)




## Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.

 
