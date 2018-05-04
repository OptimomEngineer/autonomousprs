# Autonomous power racing 

## quick compile
```
git submodule update --init
catkin_make
```

## Start control stack
This is everything at the moment. Launches the sweep node and the potential field based controller
 
Will also launch up rviz to display debug info

```
roslaunch control autonomouspr-debug.launch
```

## start scanse node
```
roslaunch sweep_ros sweep2scan.launch 
```


