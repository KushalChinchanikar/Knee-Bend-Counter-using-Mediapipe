# Knee-Bend-Counter-using-Mediapipe

Note- You need to install opencv and mediapipe for the Knee Bend Counter to work. 

Input Video-
https://user-images.githubusercontent.com/75407056/156762718-fac91747-bdf3-485b-9259-cb348464c7a0.mp4

Output Video-

https://user-images.githubusercontent.com/75407056/156762938-063a590e-ce60-4052-9866-7c4174601aca.mp4


https://user-images.githubusercontent.com/75407056/156762793-a17c2df1-f8b0-45e7-a9c6-c827ca2f5099.mp4



Procedure-
1) The input video is read using opencv.
2) The frames are recoloured and then the detections are made by mediapose.
3) The left hip, left knee and left ankle landmarks are stored and the angle between them is calculated.
4) Then using 160 degree as the critical angle it is determined if leg is bent or not.
5) In case it is bent the timer of 8 seconds starts.
6) If in between the leg goes down the timer is cancelled and “Keep your knee bent" is displayed.
7) The count and the stage – up/down is displayed on the output image. 
8) Finally the frames are combined back into a video.



