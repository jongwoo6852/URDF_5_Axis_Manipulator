# URDF_5_Axis_Manipulator

  1) xacro file convert to urdf file
   --> rosrun xacro xacro -o <xacro file name>.urdf <file name>.xacro

  2) Check urdf file(in catkin workspace)
   --> check_urdf <file name>.urdf

  3) Run MoveIt Assistant
    --> roslaunch moveit_setup_assistant setup_assistant.launch

  4) Check Manipulator demo in rviz (rviz에서 실행)
    --> roslaunch<package_file_name> demo.launch
