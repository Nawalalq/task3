# task3
Programming a package to run and emulate the arm

 # The first step is to create an urdf:
 1- Download Ros
 
 2- Download the arm package
 
 Link :

 https://s-m.com.sa/ros.txt
 
 3- Download Blender to extract urdf using phobos library
 
Blender download video:

Part1:

https://youtu.be/JGPyNxzVlYA

Part2: 

https://youtu.be/CrMvtlZl3LI

 4- After opening blender, go to file, then import, and choose stl for the parts files in the training portal.
 
 5- The order of the pieces and the definition of the joint for each piece we must know
 
 6- We can now export urdf

# The second step is to make a package:

 Command Link:

 http://wiki.ros.org/ROS/Tutorials/CreatingPackage

 1- Go to ws folder, then src, and right-click
 and choose open terminal
 
 Copy the following:
$ catkin_create_pkg beginner_tutorials std_msgs rospy roscpp
 
 3- Type this command to update the ws . folders
 
 command:
 
 Cd..
 
 Catkin.make
 
 4- This command:

$ roslaunch beginner_tutorials check_motors.launch
 
 Thus, the first movement method will be run through a joint stat
 
 5- Another way to move is through movit
 
 Type the following command in the terminal to 
 
Link:

http://docs.ros.org/en/kinetic/api/moveit_tutorials/html/doc/setup_assistant/setup_assistant_tutorial.html

run:

$ roslaunch moveit_setup_assistant setup_assistant.launch
