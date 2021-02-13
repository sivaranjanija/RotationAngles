# RotationAngles
## Pixel Co-Ordinates to Rotation angles
Refer [Milestone1](Milestone1.ipynb)

Input:

 * 2 videos - mockPitch.avi, mockYaw.avi. Approximate movement of 90 degrees each - consecutive frame analysis gives only per degree change in pitch/ yaw
* 4 images - p1.PNG, p2.PNG, y1.PNG, y2.PNG - 2 images for pitch and yaw respectively. - these frames assumed to have 2 degree change in pitch/ yaw

Output:

* Stage 1 - csv file with extracted features from given videos / images
* Stage 2 - NN model for training the pixels to rotation angles
