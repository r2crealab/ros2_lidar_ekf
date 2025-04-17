(optionnel)
source /opt/ros/humble/setup.bash
colcon buil

------------
source install/setup.bash

------------
map + mpu : ros2 launch ldlidar_node ldlidar_slam_ekf.launch.py
map : ros2 launch ldlidar_node ldlidar_slam_map.launch.py
