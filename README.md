# Part 2 - Reinforcement Learning in Navigation Goal
This is an assignment for my Industrial Automation course. The detials to recreate this project is at below.

## Reinforcement Learning
This is a modified repo from [ROBOTICS-GIT](https://github.com/ROBOTIS-GIT/turtlebot3_machine_learning)

This project code is run with ROS-kinetic.

## To recreate this project
You can follow the tutorial from [Robotics e-manual](https://emanual.robotis.com/docs/en/platform/turtlebot3/machine_learning/#machine-learning) (Change the repo for clonning in step 1.1.5 Machine Learning packages) to recreate this project by cloning this repo.
```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/ccxuan123/machine_learning_assignment.git
$ cd ~/catkin_ws && catkin_make
```
## Details of the code
The code the edited to have the turtlebot to move from 'charging station' which is origin to another 2 loccation is at [respawnGoal.py](https://github.com/ccxuan123/machine_learning_assignment/blob/main/turtlebot3_dqn/src/turtlebot3_dqn/respawnGoal.py)

The 3 target location for the turtlebot is assigned to (1,1), (-1,1), (-1,-1) as follow
```
goal_x_list = [1, -1, -1]
goal_y_list = [1, 1, -1] 
```

The path for the saved model which stored in [here](https://github.com/ccxuan123/machine_learning_assignment/tree/main/turtlebot3_dqn/save_model) should specify correctly at line 31 of [respawnGoal.py](https://github.com/ccxuan123/machine_learning_assignment/blob/main/turtlebot3_dqn/src/turtlebot3_dqn/respawnGoal.py) if the save folder name for this repo is changed
