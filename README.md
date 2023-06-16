# calibration_camera_lidar

calibration between camera and 2d lidar

## setup

> ubuntu 18.04

> ros melodic

> cmake 1.10

## nlopt install

select 2.7.0 version because of cmake version in ros1

```
sudo apt-get install ros-melodic-nlopt
```

```
git clone git@github.com:stevengj/nlopt.git
mkdir build
cd build
cmake ..
make
sudo make install
```

## calibr package install

```
git clone git@github.com:aibo-Ryan/calibration_camera_lidar.git
cd catkin_ws
catkin_make
source devel/setup.bash
rosrun calibration_camera_lidar calibration_toolkit
```
