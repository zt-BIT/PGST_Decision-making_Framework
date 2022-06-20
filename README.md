# PGST_Decision-making_Framework
A planning framework using prediction-guided strategy tree to make decisions for autonomous vehicles at uncontrolled intersections.

## Introduction
This is a planning framework using prediction-guided strategy tree to make decisions for autonomous vehicles at uncontrolled intersections, typically considering the interaction and uncertainty during the driving process. The framework exploits the neural network-based prediction model predict the future situations, then develops a tree structure to search for the optimal action sequences with explicit risk assessment. 


## Simulation Results
The simulation experiments are carried out using the [INTERACTION dataset](https://interaction-dataset.com/), visualized by the [tool](https://github.com/interaction-dataset/interaction-dataset). We show the example scenarios recorded in package 'DR_USA_Intersection_MA', which depicts an uncontrolled intersection without traffic signals. The results show that our proposed framework is able to deal with the complex driving behavior of other social behicles, including the negotiations, inexplicit right-of-way, irrational behavior and aggressive maneuvers. 

We denote the driver-driven ego vehicle as a red rectangle and the corresponding ground truth as the red curve. The ego vehicle controlled by our method is represented by a green rectangle marked 'ego', and the planned trajectory in each decision round is the curve, whose speed profile is measured by a color bar. The candidate trajectories aligned with the road geometry are yellow dotted lines. The social vehicles are described as blue rectangles (with safe margin), and the rainbow colors represent the prediction results generated by the neural network, with red to purple representing the ranking scores from high to low.

* Turning Right  
<p align="center">
    <img src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/RightTurn.gif" width="700"><br/>
    <em>Turning Right.</em>
</p>

<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/RightTurn.mp4.mp4" controls="controls" width="500" height="300"></video>

* Going Straight 
<p align="center">
    <img src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/GoStraight.gif" width="700"><br/>
    <em>Going Straight .</em>
</p>
<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/GoStraight.mp4" controls="controls" width="500" height="300"></video>

* Turning Left
<p align="center">
    <img src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/LeftTurn.gif" width="700"><br/>
    <em>Turning Left.</em>
</p>
<video src="https://github.com/zt-BIT/PGST_Decision-making_Framework/blob/main/videos/LeftTurn.mp4" controls="controls" width="500" height="300"></video>

