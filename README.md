# Satellite pose estimation

## Goals

No deep learning based approachs.

Playing around with some basic image processing functions in order to estimate the 6-dof pose of a satellite (known model) using a monocular calibrated camera.

The code is in C++ and based on OpenCV functions.

## Results

### First tests

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

### Second tests: another "cost function" + illumination correction

<!-- |   | Old vs New |
|---|---|
| Dark background 1 | <video controls src="Results/Dark_background/Poses_Dark_background_3_video4.mp4"></video> |
| Dark background 2 | <video controls src="Results/Dark_background/Poses_Dark_background_4_video6.mp4"></video> |
| Earth background 1 | <video controls src="Results/Earth_background/Poses_Earth_background_3_video2.mp4"></video> |
| Earth background 2 | <video controls src="Results/Earth_background/Poses_Earth_background_4_video5.mp4"></video> | -->

|   | Old vs New |
|---|---|
| Dark background 1 | <video controls src="https://github.com/user-attachments/assets/152ed986-c7e4-4036-8ace-8a28d45af314"></video> |
| Dark background 2 | <video controls src="https://github.com/user-attachments/assets/df0caf30-a24e-4285-a8ed-0588e66aec8f"></video> |
| Earth background 1 | <video controls src="https://github.com/user-attachments/assets/c61cb47e-008f-4b36-9668-e6d341022219"></video> |
| Earth background 2 | <video controls src="https://github.com/user-attachments/assets/829195f2-7822-4cae-9128-81421f53db5e"></video> |

### Third tests: old vs fix merge line segments

<!-- |   | Old vs New |
|---|---|
| Dark background 1 | <video controls src="Results/Dark_background/Poses_Dark_background_5_video4.mp4"></video> |
| Dark background 2 | <video controls src="Results/Dark_background/Poses_Dark_background_6_video6.mp4"></video> |
| Earth background 1 | <video controls src="Results/Earth_background/Poses_Earth_background_5_video2.mp4"></video> |
| Earth background 2 | <video controls src="Results/Earth_background/Poses_Earth_background_6_video5.mp4"></video> | -->

|   | Old vs New |
|---|---|
| Dark background 1 | <video controls src="https://github.com/user-attachments/assets/7d20ff76-904a-43f3-aff4-8624338a667d"></video> |
| Dark background 2 | <video controls src="https://github.com/user-attachments/assets/be09ff78-919b-4006-b4ae-5da59b8b755c"></video> |
| Earth background 1 | <video controls src="https://github.com/user-attachments/assets/1ac61e0d-908d-4be0-b167-2b73189e6ca4"></video> |
| Earth background 2 | <video controls src="https://github.com/user-attachments/assets/d726c376-1307-4541-9022-9b372bdccb9a"></video> |