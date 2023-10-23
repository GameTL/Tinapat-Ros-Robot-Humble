# for controlling turtlebot as slave + master (with keyboard)


# Basic walking
![rqt](rqt.svg)
![Image of sucessful connection](basic_teleop_sucess.png)

## SLAVE:

ros2 launch turtlebot3_bringup robot.launch.py

## HOST:
ros2 run turtlebot3_teleop teleop_keyboard
