# Move_twist
 
The repo aims to give speed through /cmd_vel topic for the robot to move in the gazebo 
simulation.
To test the repo:
**Don't forget to source the workspace{source ~/{worspace_name}/install/setup.bash}** 



In terminal-1:
```bash
   ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py 

```
In terminal-2:

```bash
  ros2 run locomotion move_twist 

```

![Screenshot from 2022-07-04 21-28-12](https://user-images.githubusercontent.com/22745024/177189311-80bff727-3389-411d-83d5-cb6e6bf9e8bb.png)
