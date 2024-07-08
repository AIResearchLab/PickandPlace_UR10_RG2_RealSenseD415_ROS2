# PickandPlace_UR10_RG2_RealSenseD415_ROS2
This repository provides codes for control and interface of On-Robot's RG2 gripper with ROS2, MoveIt using UR10 manipulator.

# UR10 Setup
Please follow the steps available in the https://github.com/UniversalRobots/Universal_Robots_ROS2_Driver repository.

# Plan UR10 with MoveIt

First start the driver as described above. Then start to use the MoveIt Plugin in rviz2 to plan and execute trajectories with the robot:
 
```bash
ros2 launch ur_moveit_config ur_moveit.launch.py ur_type:=ur10 launch_rviz:=true
