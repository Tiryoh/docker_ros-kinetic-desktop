# docker_ros-kinetic-desktop

![](https://img.shields.io/docker/automated/tiryoh/ros-kinetic-desktop.svg)
![](https://img.shields.io/docker/build/tiryoh/ros-kinetic-desktop.svg)
![](https://img.shields.io/docker/pulls/tiryoh/ros-kinetic-desktop.svg)

## Docker Hub

https://hub.docker.com/r/tiryoh/ros-kinetic-desktop/

## Usage

building ROS package `<package_name>` located in `~/repo/ros_ws/`:
```
$ docker run --rm -it -v ~/repo/ros_ws/<package_name>:/home/ubuntu/catkin_ws/src/<package_name> tiryoh/ros-kinetic-desktop catkin_make
$ 
```

## License

The MIT License

2018 (C) Tiryoh
