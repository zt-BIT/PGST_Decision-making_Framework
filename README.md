# PGST_Decision-making_Framework
A planning framework using prediction-guided strategy tree to make decisions for autonomous vehicles at uncontrolled intersections.

## Introduction
This is a planning framework using prediction-guided strategy tree to make decisions for autonomous vehicles at uncontrolled intersections, typically considering the interaction and uncertainty during the driving process. The framework exploits the neural network-based prediction model predict the future situations, then develops a tree structure to search for the optimal action sequences with explicit risk assessment. 


## Simulation Results
The simulation experiments are carried out using the [INTERACTION dataset](https://interaction-dataset.com/), visualized by the tool (https://github.com/interaction-dataset/interaction-dataset). We show the example scenarios recorded in package `DR_USA_Intersection_MA', which depicts an uncontrolled intersection without traffic signals. The results show that our proposed framework is able to deal with the complex driving behavior of other social behicles, including the negotiations, inexplicit right-of-way, irrational behavior and aggressive maneuvers. 

* Turning Right  
<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/TurnRight.mp4" controls="controls" width="500" height="300"></video>

* Going Straight 
<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/GoStraight.mp4" controls="controls" width="500" height="300"></video>

* Turning Left

<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/TurnLeft.mp4" controls="controls" width="500" height="300"></video>

