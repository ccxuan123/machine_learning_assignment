# AGV Assignment Part 2
## Machine Learning
This is a modified repo from [ROBOTICS-GIT](https://github.com/ROBOTIS-GIT/turtlebot3_machine_learning)

This project code is run with ROS-kinetic.

The code the edited to have the turtlebot to move from 'charging station' which is origin to another 2 loccation is at [respawnGoal.py](https://github.com/ccxuan123/machine_learning_assignment/blob/main/turtlebot3_dqn/src/turtlebot3_dqn/respawnGoal.py)

The 3 target location for the turtlebot is assigned to (1,1), (-1,1), (-1,-1) as follow
```
goal_x_list = [1, -1, -1]
goal_y_list = [1, 1, -1] 
```

You can follow the tutorial from [Robotics e-manual](https://emanual.robotis.com/docs/en/platform/turtlebot3/machine_learning/#machine-learning) to recreate this project by cloning this repo.
```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/ccxuan123/machine_learning_assignment.git
$ cd ~/catkin_ws && catkin_make
```
