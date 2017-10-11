# gazebo_cars
Gazebo Models for 15 different cars 

**Author** *Ayush Gaud*

![gazebo_cars](https://user-images.githubusercontent.com/4923897/31460826-30ceb24e-aee5-11e7-8edd-51c4e5cabeb0.jpg)

## Instructions

* Clone the repository in your catkin workspace and rebuild it
* Add the following text in your launch file 
```
<env name="GAZEBO_MODEL_PATH" value="${GAZEBO_MODEL_PATH}:$(find gazebo_cars)/models"/>
<env name="GAZEBO_RESOURCE_PATH" value="${GAZEBO_RESOURCE_PATH}:$(find gazebo_cars)/models"/>
```
* If not using with ROS then just append the enviroment variables for ```GAZEBO_MODEL_PATH``` and ```GAZEBO_RESOURCE_PATH``` with the model directory path

**PS:** Some cars are not scaled properly 

