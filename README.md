# Knee-Bend-Counter-using-Mediapipe

Note- You need to install opencv and mediapipe for the Knee Bend Counter to work. 

Input Video-

https://user-images.githubusercontent.com/75407056/156766187-09616d6c-0ad8-4bd6-b80a-6c287f1593dc.mp4



Output Video-

https://user-images.githubusercontent.com/75407056/156766265-a0d0a58a-276e-473f-95a9-4b1aa42fa23d.mp4



Procedure-
1) The input video is read using opencv.
2) The frames are recoloured and then the detections are made by mediapose.
3) The left hip, left knee and left ankle landmarks are stored and the angle between them is calculated.
4) Then using 160 degree as the critical angle it is determined if leg is bent or not.
5) In case it is bent the timer of 8 seconds starts.
6) If in between the leg goes down the timer is cancelled and “Keep your knee bent" is displayed.
7) The count and the stage – up/down is displayed on the output image. 
8) Finally the frames are combined back into a video.



