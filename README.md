# PIXELATE_TECHNEX2020
Winning solution of Pixelate_Technex_2020 -an image processing event ,with hardware implementation of robot for solving maze by applying Dijikstra's algorithm

# Problem Statement:
Pixelate of Technecx2020 ,expected us to develop a robot for solving a maze using the live feed from a over head webcam feed.The detailed PS:(https://drive.google.com/open?id=1Ce5YPxhNc1LwUZp86alKOLzDNbr6lFp6).

# Our Solution:
1)We used opencv and other image processing techniques for shape and color segmentation from video feed.

2)A matrix was made from each detected shapes and a unique node number was given to each of the detected shape and dijikstra's algorithm was applied to get the shortest path.

3)Each color shape was given certain priority level which was used later to avoid that shape from the path given by dijikstra.

4)Then an optimal graph/path was plotted to get the optimal trajectory ,connecting the centroids of all the shapes along the way to the destination shape.

5)Once the path was recieved we used aruco marker and PID control system to make our robot to follow the line conecting all this dots.

6)Individual PID parameters were used to make the robot to go straight and as well take sharp 90 degree turns.

# Our Final Run:
# Background processing:
# Robot Used:
![8bc10981-e114-4d2b-bdeb-da8ac0134584](https://user-images.githubusercontent.com/43948945/75630637-9c51e180-5c12-11ea-9d2e-3fe17faf9937.jpg)

