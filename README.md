# Trajectory-mapping-and-curev-fitting-using-opencv
Centroid Detection and Mapping. Fitted a parabolic curve to trace the trajectory of the object by minimising outliers in the image using a mask.

Plotting the trajectory involves 
1. Filtering the image by first applying erosion and dilation morphology to remove noise
2. Obtaining the required object pixels
3. Obtaining the centroid for the object pixels.
   
<img width="428" alt="image" src="https://github.com/robosac333/Trajectory-mapping-and-curve-fitting-using-opencv/assets/143353582/b5e94222-7101-4c33-87c8-031bf384fa15">

Applying this to all the images in the video frame and fitting a parabolic curve to it using Least Squares Method

<img width="429" alt="image" src="https://github.com/robosac333/Trajectory-mapping-and-curve-fitting-using-opencv/assets/143353582/12ac94be-603b-42d3-966a-01dcabed3d44">
