# Satellite pose estimation

## Goals

No deep learning based approachs.

Playing around with some basic image processing functions in order to estimate the 6-dof pose of a satellite (known model) using a monocular calibrated camera.

The code is in C++ and based on OpenCV functions.

## Naive approach

### Description of the approach

TODO

### Results

#### Dark background

##### Canny

<!-- <video controls src="Results/Dark_background/Canny_dark_background.mp4" title="Canny results"></video> -->

<div align="center">
  <video src="https://github.com/user-attachments/assets/bf4f8014-6ea6-404a-8f60-a219fcf7bbdd" type="video/mp4" controls/>
</div>

##### Estimated pose

<!-- <video controls src="Results/Dark_background/Poses_dark_background.mp4" title="Estimated poses"></video> -->

<div align="center">
  <video src="https://github.com/user-attachments/assets/6e6bdbaa-1a86-4bef-81b3-6e98a29c7e08" type="video/mp4" controls/>
</div>

There is an ambiguity in the object model, thus the frame axis flipping in some frames.

#### Earth background

##### Canny

##### Estimated pose
