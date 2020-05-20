The topic of my 2nd-semester project was laser-welding of Grundfos pump impeller with Universal Robots UR5 robot. 
The first step was making a CAD model in Solidworks, Then I imported the CAD model into RoboDK simulation software,
where I selected welding paths and waypoints and checked for potential collisions and singularities of the robot model.

I made a robot simulation in a software RoboDK https://robodk.com/ named final_robot_station.rdk
A built-in pre-processor generated a Python-based URscript files containing trajectories for the robot. 
These are located in /working_inside_out and /working_outside_in
Then I 3D-printed fixtures to hold the impeller on the table and a to attach the laser pointer to the end-effector.
I uploaded the URscript files to a UR5 teach pendant, and executed them on UR5 robot with the laser pointer "welding" the part with the given trajectories


Video of robot:
https://www.youtube.com/watch?v=1Pe1Ph-JeZw
