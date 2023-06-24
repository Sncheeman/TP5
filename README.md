#To visualise the robot in vriz

Go to path ...\ri_arm_description\urdf and run the command below in the terminal
roslaunch urdf_tutorial display.launch model:=robot.urdf

#To run the ri_arm_config run in a new terminal
roslaunch ri_arm_config demo.launch rviz_tutorial:=true


#To run the package ri_arm_control
roslaunch udm_hand_control direct.launch
OR
roslaunch udm_hand_control indirect.launch
