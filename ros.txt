# Notes for installation
sudo apt-get install ros-humble-cartographer-ros

# init
ros2 launch turtlebot3_bringup robot.launch.py


# run a keyboard package
ros2 run turtlebot3_teleop teleop_keyboard


# GTA Joy
ros2 run joy joy_node _dev_name:="*"
ros2 run gta_joy_pkg gta_joy_node


# SLAM
ros2 launch turtlebot3_bringup robot.launch.py
ros2 run turtlebot3_teleop teleop_keyboard
ros2 launch turtlebot3_cartographer cartographer.launch.py
