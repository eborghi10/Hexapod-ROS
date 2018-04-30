# Hexapod ROS

An Hexapod robot for ROS Kinetic.

## Some notes

Display robot model: `roslaunch crab_description display_model.launch`

Display gait kinematics: `roslaunch crab_description gait_disp_mode.launch`

Leg IK: `rosservice call /crab_leg_kinematics/get_ik TAB-TAB`