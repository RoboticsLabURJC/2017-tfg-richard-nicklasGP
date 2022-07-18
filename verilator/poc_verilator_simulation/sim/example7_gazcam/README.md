This example reads from ROS topic "/image_raw" and feeds the data to our simulated verilog modules. 
The processed image data is returned, transformed and published to "/cmd_vel" 


I use a gazebo world with a camera to publish simulated video recording to ROS topics. 



roslaunch display.launch


rosrun gazebo_ros gazebo --verbose car.world