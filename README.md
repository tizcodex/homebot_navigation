# homebot_navigation
Adding basic functionality to my home robot (Turtlebot 2, with Astra RGB-D camera)

Current functionality:

Currently there is a basic launch file (with some custom turtlebot parameters), which starts up the turtlebot and performs 3 goals. 
This script will soon be updated to be a turtlebot/map calibration script.

Planned functionality:

Map Object - Map segmentation with zone identification (e.g. turtlebot will "know" where it is in the house) <br /> 
Robot speech - Basic feedback from the robot to tell the user where it thinks it is (e.g. "I am in the living room") <br />
User speech - Allow a set of basic commands to be sent to the robot. Currently I plan to add just "Where are u?" and "Go to..."
commands.

*Improve map:

Could use hector_mapping in combination with robot_pose_ekf to generate better and cleaner maps.
