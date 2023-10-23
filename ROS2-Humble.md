# Learning Nav2

## launch
ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py

## control the bot
ros2 run turtlebot3_teleop teleop_keyboard 

## RQT
rqt_graph

## mapping 
ros2 launch turtlebot3_cartographer cartographer.launch.py use_sim_time:=True

## Saving Map 
mkdir maps
ros2run nav2_map_server map_saver_cli -f maps/my_map1
