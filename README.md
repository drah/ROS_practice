## To run simple mover
```shell
$ catkin_make
$ source devel/setup.bash
$ roslaunch simple_arm robot_spawn.launch
$ rosrun simple_arm simple_mover
```

```shell
$ catkin_make
$ sudo apt-get install ros-kinetic-controller-manager
$ sudo apt-get install ros-kinetic-gazebo-ros-control
$ source devel/setup.bash
$ rosdep install simple_arm
$ catkin_make
```

