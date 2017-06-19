# Extended Kalman Filter and Sensor Fusion for tracking LiDAR and radar measurements

![result](img_result/Result%20with%20Radar%20and%20Laser.png)

Simple implementation in C++ of sensor fusion with an Extended Kalmar Filter in order to track a moving object with LiDAR and Radar sensors at the same time.

We calculate the root mean squared error of each measurement prediction with the real state position(Px,Py) and velocity(Vx,Vy) of the object.



**Project Files**:

- `main.cpp` Used to connect with a simulator that provides telemetry data packs and visualize the state prediction and error.
- `kalman_filter.cpp` Full implementation of regular and extended Kalman Filter operations and matrices.
- `FusionEKF.cpp` Controls the EKF workflow and measures using sensor fusion.
- `tools.cpp` Helper functions for EKF and the workflow.
