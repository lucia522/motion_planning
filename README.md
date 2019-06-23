# Motion Planning
Computational Motion Planning course from Penn. Matlab implementation of the tasks can be found in matlab_src folder.
Each of the subfolder includes run.m script for simulation launching and subfunctions.
In order to launch the algorithms simply execute:
```matlab
run.m
```
in your Matlab command line.

Python code that is aimed to apply path planning algorithms for real mobile robots is located in pthon_src folder.
In order to get familiar with the Artificial Potential Filds (APF) algorithm:
```bash
jupyter-notebook GradientBasedPlanning.ipynb
```
- Real time potential fields-based obstacle avoidance method for robots formations with moving or static obstacles.
```bash
python python_src/adaptive_formation/gradient_interactive.py
```
- Road map and path construction with Rapidly exploring Random Tree (RRT) algorithm:
```bash
python python_src/rrts/main_rrt2D.py
```
in 3D environment:
```bash
python python_src/rrts/3D/rrt3D.py
```
- Multi-layered planner for formation of robots navigation based on RRT+APF algorithms. Take a look on the [package](https://github.com/RuslanAgishev/adaptive_swarm "RRT+APF layered planner")
 for more details: 
```bash
python python_src/layered_planner/main_rrt_gradient.py
```
