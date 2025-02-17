This package relies on ROS Iron to be previously installed

in workspace, add files to src folder


#source ros

source install/setup.bash


#build package

colcon build


#to run rviz simulator:

ros2 launch lunabotics2025_urdf display.launch.py


#to run gazebo simulator:

ros2 launch lunabotics2025_urdf gazebo.launch.py
