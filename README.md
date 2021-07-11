# Using-SLAM-map-to-launch-the-navigation
follow the steps:
## Open the gazebo as gazebomap.png
* $ export TURTLEBOT3_MODEL=burger
* $ roslaunch turtlebot3_gazebo turtlebot3_world.launch
* **or** follow **here** https://github.com/ZainabElzainy/Use-Turtlebot3-with-SLAMTurtlebot3-with-SLAM-approach-to-create-and-save-a-map.git
## Run Navigation Node
* $ export TURTLEBOT3_MODEL=burger
* $ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
 * Click ON 2D Pose Estimation button  as **2D Pose Estimate.png** to Put the initial place before running 
 * Click on 2D Nav Goal button   **as 2D Navigation goal.png** you can draw the direction of the turtlebot3  where it will go as **final Look turtulebot3.png**
