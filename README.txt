The topic of my 2nd-semester project was laser-welding of Grundfos pump impeller with Universal Robots UR5 robot. 
The first step was making a CAD model in Solidworks, Then I imported the CAD model into RoboDK simulation software,
where I selected welding paths and waypoints and checked for potential collisions and singularities of the robot model.

Using the simulation, a pre-processor generated a Python-based URscript, which was then used in a UR5 robot teach pendant.
Then I 3D-printed fixtures to hold the impeller on the table and a to attach the laser pointer to the end-effector.
I executed the program with the laser pointer "welding" the part on the welding paths.

The URscript source code containing welding paths is located in /working_inside_out and /working_outside_in

Video of robot:
https://www.youtube.com/watch?v=1Pe1Ph-JeZw
