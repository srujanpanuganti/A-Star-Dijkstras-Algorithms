# enpm661_project2
Implementation of Dijkstra and A star algorithms for point and rigid robot


This codes are written in python3
make sure opencv 3.4 or above is installed
make sure the following packages are imported/installed in order to run the codes

numpy
copy
math
matplotlib
queue
cv2
itertools
argparse


How to execute:


for Dijkstra_point.py and A_star_point.py you need to give the input in the terminal as
python [file name] [start_position] [goal_position] [grid_size]


example input for running Dijkstra for the point robot is given below
python Dijkstra_point.py 12,12 140,100 5

example input for running A* for the point robot is given below
python A_star_point.py 12,12 140,100 5


for Dijkstra_rigid.py and A_star_rigid.py you need to give the input in the terminal as
python [file name] [start_position] [robot_radius] [clearance] [grid_size] [goal_position]

example input for running Dijkstra for the rigid robot is given below
python Dijkstra_rigid.py 12,12 5 3 5 140,100

example input for running A* for the rigid robot is given below
python A_star_rigid.py 12,12 5 3 5 140,100
