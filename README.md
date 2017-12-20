# ROBOT SYSTEM HOMEWORK

## This repository is a ROS tutorial
-------------------------------------------------------------
**Initialize the ros workspace**   
 `catkin_init_workspace`  
**Environment setup**  
 `catkin_make`    
`source ~/catkin_ws/devel/setup.bash`  
**check rospackage path**  
   `echo $ROS_PACKAGE_PATH`  
 **if it shows like the following :**  
  ` /home/usrname/catkin_ws/src`  
 it means the environment setting is **success**  
 **Create a package**  
 `catkin_create_pkg packagename rospy`  
 `mkdir scripts`  
 `cd scripts`  
 `vi count.py  %create a publisher`  
 `rosrun packagename count.py`  
 `rostopic echo /count_up     %execute this command at another terminal window`  
  `vi twice.py  %create a subscriber`  
  
 
