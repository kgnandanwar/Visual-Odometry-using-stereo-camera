# Visual Odometry for Localization in Autonomous Driving

This project implements [visual odometry](https://en.wikipedia.org/wiki/Visual_odometry) to estimate the trajectory of a self-driving car.

**The steps of this project are the following:**

- Acquire an image and extract features using a feature detector.
- Find corresponding features in another image with feature matching.
- Determine the camera pose from the Perspective-n-Point solution using the RANSAC scheme.
- Build the vehicle trajectory from the camera pose estimation.

<p align="center">
<img src="output/camera-motion.gif" width=67% height=67%/>
</p>
