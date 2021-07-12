# ROs-Navigation_Issue
here is the problem 
https://drive.google.com/file/d/1DZjreA01EzTN2tPMd2PM6qgXtFwt7OC-/view?usp=sharing

![](http://i.imgur.com/Ssfp7.gif)
 
 
The main issue here as you can see is the robot movement to a defined goal the robot moves right and left but we need it to move straight forward 

## How we call launch files in ``` launch folder ```

- we call tb3_simulation_launch.py and it will cal a set of launch files 
- bringup_launch.py  -----> it will call the follwing 
- slam_launch.py
- localization_launch.py
- navigation_launch.py

- each launch file call a specific node this node parameters can be adjusted through param.yaml which can be found in ```param folder``` 


