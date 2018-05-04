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

## Configuration
The only thing we can configure right now is the potential field controller x/y sensitivity

The config file is at 
```
src/racecar-controllers/racecar_potential_field_controller/config/default.yaml
```

The axes are in lidar space - so x is looking in front of the lidar, y to the sides

## start scanse node
```
roslaunch sweep_ros sweep2scan.launch 
```


