# ROS 2 TurtleBot3 Navigation & A* Path Planning

A ROS 2 project built on **Ubuntu 22.04 (Humble)** featuring TurtleBot3 simulation, mapping, and custom A* path planning in Gazebo and RViz.

## 🎥 Demo
![Demo GIF](assets/demo.gif)

## 🛠️ Installation & Setup
1. Clone the repository into your workspace `src` folder:
```bash
   cd ~/your_ws/src
   git clone [https://github.com/aparna7ap7/my-robot-navigation-project.git](https://github.com/aparna7ap7/my-robot-navigation-project.git)
```

2. Build the workspace:
```bash
   cd ~/your_ws
   colcon build --symlink-install

```

3. Source your environment:
```bash
   source install/setup.bash
   source /usr/share/gazebo/setup.sh

```


## 🚀 Usage

```bash
   ros2 launch launch/mapping_astar.launch.py goal_x:=1.5 goal_y:=-1.0
```

