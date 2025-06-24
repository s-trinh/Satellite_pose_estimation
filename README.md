# Satellite pose estimation

## Goals

No deep learning based approachs.

Playing around with some basic image processing functions in order to estimate the 6-dof pose of a satellite (known model) using a monocular calibrated camera.

The code is in C++ and based on OpenCV functions.

## Results

<!-- |   | Canny | Poses |
|---|---|---|
| Dark background 1 | <video controls src="Results/Dark_background/Canny_Dark_background_1_video4.mp4"></video> | <video controls src="Results/Dark_background/Poses_Dark_background_1_video4.mp4"></video> |
| Dark background 2 | <video controls src="Results/Dark_background/Canny_Dark_background_2_video6.mp4"></video> | <video controls src="Results/Dark_background/Poses_Dark_background_2_video6.mp4"></video> |
| Earth background 1 | <video controls src="Results/Earth_background/Canny_Earth_background_1_video2.mp4"></video> | <video controls src="Results/Earth_background/Poses_Earth_background_1_video2.mp4"></video> |
| Earth background 2 | <video controls src="Results/Earth_background/Canny_Earth_background_2_video5.mp4"></video> | <video controls src="Results/Earth_background/Poses_Earth_background_2_video5.mp4"></video> | -->


|   | Canny | Poses |
|---|---|---|
| Dark background 1 | <video controls src="https://github.com/user-attachments/assets/767a5991-d9e9-4aec-b2b7-2894d09dd526"></video> | <video controls src="https://github.com/user-attachments/assets/0ddf9356-31f4-4fb6-bf75-406c37abd5b1"></video> |
| Dark background 2 | <video controls src="https://github.com/user-attachments/assets/fec9b982-2c7b-4cb4-9441-736692ea2529"></video> | <video controls src="https://github.com/user-attachments/assets/3eedd59f-0c80-4210-965c-5a75e8b54ff0"></video> |
| Earth background 1 | <video controls src="https://github.com/user-attachments/assets/08014431-fecc-4ca5-a93f-6811a043e130"></video> | <video controls src="https://github.com/user-attachments/assets/06a88f3a-1191-4847-8702-5b410639a6aa"></video> |
| Earth background 2 | <video controls src="https://github.com/user-attachments/assets/38373ecb-3aee-43fd-a163-523cf2232b1a"></video> | <video controls src="https://github.com/user-attachments/assets/c9674f13-1f93-4fe1-888f-0ec092c12cf9"></video> |