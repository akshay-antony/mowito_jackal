# mowito_jackal

## For Mapping

In a terminal (Source the files)

```  $ roslaunch jackal_gazebo jackal_world.launch config:=front_laser  ```

In a new terminal (Source the files) 

``` $  roslaunch jackal_navigation jackal_mw_mapping.launch ```

Move the robot around using InteractiveMarkers, which can viewed in rviz.

## For navigation with map

In a terminal run

```$ roslaunch jackal_navigation jackal_mw_nav.launch ```

## For navigation without map

In a terminal (Source the files)

```  $ roslaunch jackal_gazebo jackal_world.launch  config:=front_laser ```

In a terminal (Source the files)

```  $  roslaunch jackal_navigation jackal_mw_nav_no_map.launch ```

## For exploring with map generation

In a terminal (Source the files)

```  $ roslaunch jackal_gazebo jackal_world.launch  config:=front_laser ```

In a terminal (Source the files)

```  $  roslaunch jackal_navigation jackal_mw_explore_mapping.launch ```





