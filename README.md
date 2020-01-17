Udacity Robotics Software Engineer Nanodegree Project 5 Home Service Robot by Michael Strobl

1- Install Packages

	$ cd ~/catkin_ws/src
    $ git clone https://github.com/ros-perception/slam_gmapping
    $ git clone https://github.com/turtlebot/turtlebot
    $ git clone https://github.com/turtlebot/turtlebot_interactions
    $ git clone https://github.com/turtlebot/turtlebot_simulator

2- Build the project:
    
    $ cd ~/catkin_ws
    $ catkin_make


3- Launch the Home Service Robot

    $ cd ~/catkin_ws
    $ source devel/setup.bash
    $ chmod +x ./src/shellScripts/home_service.sh
    $ ./src/shellScripts/home_service.sh


Sources:

- Udacity Robotics Software Engineer Nanodegree Project 5
