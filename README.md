# Extended Kalman Filter Project 

I have implemented the extended Kalman filter in C++.I have been provied the simulated lidar and radar measurements detecting a bicycle that travels around the vehicle. 
I have used a Kalman filter, lidar measurements and radar measurements to track the bicycle's position and velocity.


## Dependencies

* cmake >= 3.5
* make >= 4.1
* gcc/g++ >= 5.4


[//]: # (Image References)

[image1]: ./output_images/tracking_with_lidar.png "tracking_with_lidar"

![alt text] [image1] 


The algorithm runs against "sample-laser-radar-measurement-data-1.txt". The algorithm outputs the positions and gets compared to ground truth data. 
The px, py, vx, and vy RMSE should be less than or equal to the values [0.08, 0.08, 0.60, 0.60].

I was able to achieve the required RMSE with:

Accuracy - RMSE:
0.0651648
0.0605379
0.533212
0.544193

The algorithm runs against "sample-laser-radar-measurement-data-2.txt". Here also, the algorithm outputs the positions and gets compared to ground truth data.  
The px, py, vx, and vy RMSE should be less than or equal to the values [0.20, 0.20, .50, .85].


I was  able to achieve the required RMSE with:

Accuracy - RMSE:
0.185465
0.190254
0.476509
0.810803