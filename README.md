# UR10_RG2_Pick-Place_ROS2
This repository provides codes for control and interface of On-Robot's RG2 gripper with ROS2, MoveIt using UR10 manipulator.

# UR10 Setup
Please follow the steps available in the https://github.com/UniversalRobots/Universal_Robots_ROS2_Driver repository.

To use the MoveIt Plugin in rviz2 to plan and execute trajectories with the robot 
ros2 launch ur_moveit_config ur_moveit.launch.py ur_type:=ur10 launch_rviz:=true 
