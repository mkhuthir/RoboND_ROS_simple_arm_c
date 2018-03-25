[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# ROS Simple Arm control in C++
A `simple_arm_c` package to demonstrate how ROS publisher works in C++.  

<p align="center"> <img src="./misc/simple_arm.png"> </p>


### How to Launch the simulation?
Make sure you already have a catkin workspace to work in!

#### Navigate to the src folder in your catkin workspace:
```sh
$ cd ~/catkin_ws/src
```

#### Clone the package:
```sh
$ git clone https://github.com/udacity/simple_arm_c.git
```

#### Source your environment:
```sh
$ cd ~/catkin_ws
$ source devel/setup.bash
```

#### After sourcing your environment, build the packages:
```sh
$ catkin_make
```

#### Make sure to install the missing system dependencies:
```sh
$ rosdep install -i simple_arm_c
```

#### Once the `simple_arm_c` package has been built, you can launch the simulation environment using:
```sh
$ roslaunch simple_arm_c robot_spawn.launch
```

Now, you should be able to see each revolute joint rotating between -pi/2 to pi/2 over time!
