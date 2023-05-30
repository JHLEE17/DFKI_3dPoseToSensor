# DFKI_3dPoseToSensor
3D pose estimation for generating sensor data


### Meaning of the file names

subject1_walking_15_17_11_2_MFthr5.csv:
Only the information of 15 (L_shoulder), 17 (L_elbow), 11 (Neck), 2 (spine1) are used from the 3D body pose data.
Frames with more than 5 missing frames have been deleted from both the 3D body pose and sensor data.
Frames with fewer than 5 missing frames have been interpolated.

acc_walking_forearm_18455_s1.csv:
This file contains accelerometer sensor data, walking scene of subject1, and uses only 18455 frames that have had missing frames deleted and interpolated.
