
To build the plugin:
```
cd plugin  
mkdir build  
cd build  
cmake ../  
make  
```
Now, to launch the package:

```
roslaunch stewart stewart.launch
```

To view the IMU and Joint forces,

  In Gazebo press Ctrl+T 
  
  select the gazebo.mgsd.IMU or gazebo.msgs.WrenchStamped messages respectively




## Note: This requires ROS kinetic (ubuntu 16.04) to run correctly
