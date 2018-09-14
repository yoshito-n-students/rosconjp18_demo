# rosconjp18_demo

## Install & build
```
mkdir rosconjp18_demo_ws
cd rosconjp18_demo_ws
git clone git@github.com:yoshito-n-students/rosconjp18_demo.git src
cd src
git submodule update --init --recursive
cd ..
catkin_make
```

## IMU demo
```
roslaunch rosconjp18_demo bno055.launch
```

## Virtual camera (image reprojection) demo
```
roslaunch rosconjp18_demo virtual_camera.launch
```

## Turtle detection demo
```
roslaunch rosconjp18_demo turtle_detection.launch
```