# ros2_practice

This is my [ROS2](https://index.ros.org/doc/ros2/) practice repository.

## Prerequisites

* [Vagrant](https://www.vagrantup.com/) `2.2.5`
* [Virtual Box](https://www.virtualbox.org/) `6.0.8`
* Python 3.5.6 or more
* CMake 3.14.5
* ROS2 Dashing Diademata

## Setting up

* Install dependency python modules

```bash
pip install -U pip
pip install -r requirements.lock
```

* setting up ros2

```bash
colcon build
source ./install/setup.zsh 
```