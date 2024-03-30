march 30, 2024

home/dev_ws
<br/> 
rebuild when file is changed:
    
    colcon build --symlink-install
<br/> 
source install/setup.bash from jergra43@jergra43:~/dev_ws$

ros2 launch bot rsp.launch.py
<br/> 
source install/setup.bash

rviz2 -d src/bot/config/view_bot.rviz
<br/> 
source install/setup.bash
<br/>
<br/> 
ros2 run joint_state_publisher_gui joint_state_publisher_gui






source /opt/ros/iron/setup.bash from jergra43@jergra43:/$





## Robot Package Template

This is a GitHub template. You can make your own copy by clicking the green "Use this template" button.

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `bot` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has direcctories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).