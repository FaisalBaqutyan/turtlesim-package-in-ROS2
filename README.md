# turtlesim-package-in-ROS2
running and manipulating turtlesim package in ROS2

turtlesim is a simplified 2D simulation of a turtle and to run it on ROS2 we have to first install it by copying this code and paste it in the terminal 

```
sudo apt update
sudo apt install ros-humble-turtlesim
```

next we can run the turtlesim easily by copying this code and paste it in the terminal 

```
ros2 run turtlesim turtlesim_node
```
as we can see in the picture turtlesim is working 

![Screenshot from 2024-07-04 15-28-19](https://github.com/FaisalBaqutyan/ROS2-humble-installation/assets/174335196/9f1acdf1-3256-422a-818a-cd169f13c2c4)

to manipulate the turtle we should open a new terminal then paste this code in the terminal 

```
ros2 run turtlesim turtle_teleop_key
```

finally, we can manipulate it easily by using the arrows as seen in the picture 

![Screenshot from 2024-07-04 15-33-55](https://github.com/FaisalBaqutyan/ROS2-humble-installation/assets/174335196/8b0a93ed-e133-434d-95da-1b6399f5dee4)
