# Please help me (ros kinetic, gazebo7, MoveIt!) #

## How to launch this package (compiled with catkin_make command) ##

* Don't forget to source the catkin_workspace containing those folders
* Open 2 or 3 terminal tabs or windows (use ctrl+SHIFT+t into a terminal)
* Into the first, type

```
roslaunch rosbook_arm_gazebo rosbook_arm_grasping_world.launch
```

* Into the second, type

```
roslaunch rosbook_arm_moveit_config moveit_rviz.launch config:=true
```

* Third terminal could be used for grep (finding occurences), compiling, replacing occurences, using git, etc...
