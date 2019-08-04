# SFND_Unscented_Kalman_Filter
Course project for Udacity Sensor Fusion Engineer Nanodegree Program

<img src="media/ukf_highway_tracked.gif" width="700" height="400" />

In this project we implemented an Unscented Kalman Filter to estimate the state of multiple cars on a highway using noisy lidar and radar measurements. 


I've done a similar UKF implementation in the Self Driving Car nanodegree program. This project helps me review some of the content in UKF course, especially the part about motion model derivation. We can project a system state forward in time by deriving the change rate of the state, and then integrate the state change rate.
