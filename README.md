# ROS-ChainerCV-GPU

This is ROS wrapper of ChainerCV using `catkin_virtualenv` with GPU dependencies.

This project depends on [locusrobotics/catkin_virtualenv](https://github.com/locusrobotics/catkin_virtualenv).

## Build 

```bash
mkdir catkin_ws/src -p
cd catkin_ws/src
git clone https://github.com/locusrobotics/catkin_virtualenv.git
git clone https://github.com/knorth55/ros_chainercv_gpu.git
cd ..
catkin build
```

## Run demo

Please build this using the standard build procedure of ROS.

```bash
# after build
source devel/setup.bash
rosrun chainercv_gpu ssd_demo.py image.jpg
```
