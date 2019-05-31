# udacity-robond-project5
Project 5 submission for Udacity Robotics Software Engineer Nanodegree Program


Download catkin_ws folder

1. Build the packages and launch the world

  catkin_make
  
  source devel/setup.bash
  
  roslaunch my_robot world.launch
  
2. Run teleop_twist_keyboard

  source devel/setup.bash
  
  rosrun teleop_twist_keyboard teleop_twist_keyboard.py
  
3. Launch the mapping node

  source devel/setup.bash
  
  roslaunch my_robot mapping.launch
  
4. Teleoperate robot around world and open map

  rtabmap-databaseViewer ~/.ros/rtabmap.db
  
  (To view map already constructed, unzip rtabmap.db and run:
  
    rtabmap-databaseViewer /catkin_ws/src/my_robot/maps/rtabmap.db)
