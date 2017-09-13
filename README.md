# Human Motion Analysis Programming
*Supervised by Prof. [Tung-Wu Lu](http://oemal.bme.ntu.edu.tw/professor/professorE.htm), Dept. of BioMedical Engineering, NTU*

Implemented MATLAB programs with a motion capture system and force plates for motion analysis, including motion tracking, evaluation of body balance, and derivation of joint forces and torques of the lower body.

## Requirements
1. MATLAB 2015 (or newer versions)
2. [MTIMESX function](https://www.mathworks.com/matlabcentral/fileexchange/25977-mtimesx-fast-matrix-multiply-with-multi-dimensional-support)(Fast Matrix Multiply with Multi-Dimensional)
3. Programs are tested in Win10 & Ubuntu 16.04

## Functions & Execution Results
### Week1: Transformation between Global & Local Coordinate  
The transformation of marker position between global & local coordinate of lower body segemnts.  

### Week2: COP Tracking  
Derive the COP from signals of two force plates and display the positions relative to force plates.  
  
![COP Tracking](/results/COP.gif) 

### Week3: Euler Angle & Fixed Angle
1. Represent the rotations of body segemnts with Euler angle and fixed angle.  
2. Display the difference of Euler angle before and after static calibration of indivisual during motion.  

![Static calibration](/results/hw3.png)  

### Week4: Curve Fitting
1. Smoothen the data curve and display the angular velocity and angular acceleration.  
![AngVel](/results/hw4_AngVel.jpg)  ![AngAcc](/results/hw4_AngAcc.jpg)  





