# 2R-Robotic-Arm-Simulator
**OBJECTIVE:**

To create a program in python to simulate the forward kinematics of a 2R Robotic Arm and to create a animation file of the plot.

PROBLEM STATEMENT:

To find the end-tip position of a manipulator in a coordinate space given its joint parameters (i.e., joint angles for revolute joints and link offset for prismatic joints).This means that given a certain pose of a robotic arm, the xy coordinates of the hand must be determined.

**THEORY:**

Forward kinematics refers to the use of the kinematic equations of a robot to compute the position of the end-effector from specified values for the joint parameters.

                                

Drived Formulae,

      X1=Xo+L1 cosθ1

      Y1=Yo+L1 sinθ1

      X2=X1+L2 cosθ2

      Y2=Y1+L2 cosθ2

**PROCEDURE:**

**Step 1:** Firstly , we have to import the requried module . Here I have imported 'math' and 'matplotlib.pyplot' as py inorder to perform maths calculation and to plot the result respectively.

**Step2:** Then we have to define the set of values for angles and initial using variables

**Step 3:** We have to introduce a empty array inorder to store different value of angles

**Step 4:** We introduce a counter variable inorder to make the result plot filenames in order.

**Step 5:** We use for loop to calculate the desired and answers.And then we convert counter variable to string inorder to give a filename.

**Step 6:** Then we indroduce figure(),plot() ,title(),grid(),xlim() and xlim() inorder to create a image of the plot with a title and with x and y axis limits.

**Step 7 :** I have installed cygwin and imagemagick inorder to animation the obtained pictures as a gif


**OUTPUT:**<br /> 
![1](https://user-images.githubusercontent.com/104487026/179734790-170b4e39-4a72-457a-bbdf-bcfd87913844.gif)<br /> 

**RESULT:**

We have create a program in python to simulate the forward kinematics of a 2R Robotic Arm and created a animation gif file of the plot.
