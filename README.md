# Status
This project is on hold for now..

# Homebot_navigation
Adding basic functionality to my home robot (Turtlebot 2, with Astra RGB-D camera)

Functionality:

HOMEBOT_NAVIGATION: <br /> 
Script robot_controller: Starts up the turtlebot and performs 3 goals. <br /> 
Script calibrate_robot: Turns the robot, about 360 degrees.

SIMULATION: <br /> 
Scripts: HOMEBOT_NAVIGATION (The scripts I plan to test will all be made in the HOMEBOT_NAVIGATION package) <br /> 
Launch home_single_robot.launch: This is the main launcher for the simulation. It loads the world and turtlebot but there are base_link problems.

Planned functionality: <br /> 
Map Object - Map segmentation with zone identification (e.g. turtlebot will "know" where it is in the house) <br /> 
Robot speech - Basic feedback from the robot to tell the user where it thinks it is (e.g. "I am in the living room") <br />
User speech - Allow a set of basic commands to be sent to the robot. Currently I plan to add just "Where are u?" and "Go to..."
commands.

*Future improvements: Could use hector_mapping in combination with robot_pose_ekf to generate better and cleaner maps.
