# Autonomous-Navigation-ROS
Simulation of a robot that is capable of autonomous navigation of a given map while avoiding collision with statics obstacles.

## How to Run
1- Add "betabot" package in your home/catkin_ws/src path.<br/>
2- Type the following commands in the terminal:<br/>
`source ~/catkin_ws/devel/setup.bash`<br/>
`roslaunch betabot gazebo.launch`<br/>
3- Open a new terminal and type:<br/>
`roslaunch betabot amcl.launch`<br/>
4- Open a new terminal and type:<br/>
`rosrun rviz rviz`<br/>
5- Click on "2D Nav Goal" button and click on the goal that you want the robot to navigate to.<br/>

### Check the pdf file for further details.
