# gbplanner_ws
This workspace includes relevant packages to run with the [gbplanner_ros](https://github.com/unr-arl/gbplanner_ros).

The workspace has been tested in Ubuntu 16.04 and ROS Kinetic. If you are using Ubuntu18 and ROS Melodic (or Gazebo 9), please use the branch [melodic](https://github.com/unr-arl/gbplanner_ws/tree/melodic). For Ubuntu 20 with ROS Noetic use the branch [noetic](https://github.com/unr-arl/gbplanner_ws/tree/noetic)


### Clone the package
```
git clone https://github.com/unr-arl/gbplanner_ws
```

### Setup the workspace
```
cd gbplanner_ws
git checkout <ros-distro> # melodic / noetic 
wstool init
wstool merge packages_https.rosinstall
wstool update
```

### Build the whole workspace
```
catkin config -DCMAKE_BUILD_TYPE=Release
catkin build
````
