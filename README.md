# Depth-Estimation

**Short description of what each code file does:**

\
*Dimension_learning:*

- Converts pixel distance regions to mm 

- Computes real dimensions in x, y, and z from pixel to mm 

- 2 functions for each direction 

  - 1 of them is my implementation with distortion error 

  - The other is a found implementation which is invariant to distortion

\
*Epipolar geometry:*

- Depth estimation from stereo image pair using image rectification with x direction window search for disparity 

 
\
*Images to mp4 file:*

- Converts a folder of jpg or png images into a mp4 video with a chosen fps 
 
\
*Mucking around with stereo camera:*

- Notebook with many different functions for capturing videos, images, depth, stereo video, disparity and a few more options using an Intel Realsense d435 stereo camera 

- Used these methods for capturing my data 

\
*Npy array to mp4 video:*

- Converts an imported npy array into a mp4 video with a chosen fps 

\
*Opencv depth:* 

- More depth estimation techniques, implementing OpenCV's methods and mixing them with my methods, testing too see what works in depth estimation 

\
*Stereo-KLT:*

- Keypoint estimation using Superpoint and Superglue 

- Keypoint tracking over a video using Lucas Kadane Tracking (KLT) 

- Computing depth estimation over tracked keypoint, returning a 3D graph of the points 3D displacement 

- View the vibrations of the tracked points in x, y and z 

\
*Video_stabilization:*

- Video stabilization using 2D affine transformations elimination or smoothing 

- Transforms found by either KLT or Superpoint and Superglue 

- Can also compute the stabilization accuracy by plotting vibration graphs of the basic and stabilized videos 
