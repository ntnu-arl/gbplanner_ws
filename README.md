# gbplanner_ws
This workspace includes relevant packages to run with the [gbplanner_ros](https://github.com/unr-arl/gbplanner_ros).

### Clone the package
```
git clone https://github.com/unr-arl/gbplanner_ws
```

### Setup the workspace
```
cd gbplanner_ws
wstool init
wstool merge packages_https.rosinstall
wstool update
```

### Build the whole workspace
```
catkin config -DCMAKE_BUILD_TYPE=Release
catkin build
````

The whole workspace has been tested in Ubuntu 16.04 and ROS Kinetic. We will test and update further with respect to Ubuntu18 and ROS-Melodic.
