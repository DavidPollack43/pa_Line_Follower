# pa_Line_Follower
Git Repository for pa_Line_Follower programming assignment. 

To run this, just use the launch file (roslaunch PA_Line_Follower pa_line_follower.launch) or rosrun the follower_p.py file (rosrun PA_Line_Follower pa_line_follower). 

This program makes a robot follow a line by isolating a yellow line (by isoloating yellow colored pixels), calculating the centroid of that line, and then following that line using error measurements