# auto_nav

This is a description folder that contains the UDRF transformation, footprints of a two wheel, differential robot.

This folder also contains a extended kalman filter node that produces robot's odometry based on imu and wheel encoder data

The project uses ros2 foxy, and ros2 intelrealsense wrapper to publish and receive the imu and laserscan data from D415 and t265 cameras.

The project uses navigation 2 and ros slam_tool_box to visualize the navigation using Rviz and create route planner.

Currently working to create a controller for the robot.
